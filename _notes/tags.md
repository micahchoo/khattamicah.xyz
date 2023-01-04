---
layout: note
tags: 
source:
compiler:
category:
title: All Tags
permalink: /tags
---

# tags

<div style="scroll-margin: 20px;" class = "tags">	
	<h1>See notes tagged under</h1>
	<p>
	 {% assign tags = site.notes | map: 'tags' | join: ' '  | split: ' ' | uniq | sort %}
	 {% for tag in tags %}
		<a class="tag" href="#{{tag}}" target="_self">{{ tag | replace: "-", "&nbsp;" }}</a>
	 {% endfor %}
	
<main align="center" style="scroll-margin: 20em;">
	    {% assign tags =  site.notes | map: 'tags' | join: ' '  | split: ' ' | sort %}
    	{% for tag in tags %}
			<h2 id="{{ tag }}">{{ tag | captalize }}</h2>
			
			{%- for note in site.notes -%}
				{%- if note.tags contains tag -%}
					<ul class = "internal-link"><li style="padding-bottom: 0.6em; list-style: none;">
					        <a href="{{note.url}}" target="_self">{{ note.title }}</a>
					</li></ul>
				{%- endif -%}
			{%- endfor -%}
		<a href="#" target="_self">All Tags</a>
		<p style="min-height: 100vh;">
		{%- endfor -%}
    <br/>
    <br/>
</main>