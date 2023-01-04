---
layout: note
title:
tags: 
source:
compiler:
category:
---

# Js to convert csv to xml

This is a script to turn a csv files like this 

```csv
  

title, htmlUrl, xmlUrl

xxiivv, https://wiki.xxiivv.com/, https://wiki.xxiivv.com/links/rss.xml
```

Feed url into a newsreader readable importable opml file

try it here.

[[csv2opml]]

```js
function generateOpml(csv) {
  // parse the csv data
  const rows = csv.split('\n');
  const data = rows.map(row => row.split(','));

  // create the XML document
  const doc = document.implementation.createDocument(null, null, null);
  
  // create the root element
  const root = doc.createElement('opml');
  root.setAttribute('version', '1.0');
  doc.appendChild(root);
  
  // create the head element
  const head = doc.createElement('head');
  root.appendChild(head);
  
  // create the title element
  const title = doc.createElement('title');
  title.textContent = 'Podcast Feeds';
  head.appendChild(title);
  
  // create the body element
  const body = doc.createElement('body');
  root.appendChild(body);
  
  // create the outline elements
  data.forEach(([text, xmlUrl]) => {
    const outline = doc.createElement('outline');
    outline.setAttribute('type', 'rss');
    outline.setAttribute('text', text);
    outline.setAttribute('xmlUrl', xmlUrl);
    body.appendChild(outline);
  });
  
  // convert the XML document to a string
  const serializer = new XMLSerializer();
  const opml = serializer.serializeToString(doc);
  
  return opml;
}

function downloadOpml(opml) {
  // create a link element
  const link = document.createElement('a');
  link.href = `data:text/xml;charset=utf-8,${encodeURIComponent(opml)}`;
  link.download = 'podcasts.opml';
  
  // append the link to the body and click it
  document.body.appendChild(link);
  link.click();
  
  // remove the link from the body
  document.body.removeChild(link);
}

// get the csv data from somewhere (e.g. a file input element)
const input = document.getElementById('file-input');

input.addEventListener('change', () => {
  const file = input.files[0];
  
  if (!file) {
    return;
  }

  const reader = new FileReader();

  reader.onload = event => {
    const csv = event.target.result;
    const opml = generateOpml(csv);
    

// generate the opml file
const opml = generateOpml(csv);

// download the opml file
downloadOpml(opml);

    // do something with the opml data (e.g. download it as a file)
  };
  reader.readAsText(file);
});


```