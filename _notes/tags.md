---
title: Tag Page
permalink: /tags
---

<div class = "tags">	
	<h1>Tags</h1>
	<p>
	{% assign tags = site.notes | map: 'tags' | join: ' '  | split: ' ' | uniq % | sort %}
	 {% for tag in tags %}
		<a class="tag" href="#{{tag}}" target="_self">{{ tag | replace: "-", "&nbsp;" }}</a>
	 {% endfor %}


<main>
	    {% assign tags =  site.notes | map: 'tags' | join: ' '  | split: ' ' | sort %}
    	{% for tag in tags %}
			<p style="min-height: 100vh;">
			<h2 id="{{ tag }}">{{ tag | captalize }}</h2>
			<p style="min-height: 1vh;">
			{%- for note in site.notes -%}
				{%- if note.tags contains tag -%}
					<ul class = "internal-link"><li style="padding-bottom: 0.6em; list-style: none;">
					        <a href="{{note.url}}" target="_self">{{ note.title }}</a>
					</li></ul>
            {%- endif -%}
        {%- endfor -%}
	<a href="#" target="_self">All Tags</a>
    {%- endfor -%}
    <br/>
    <br/>
</main>