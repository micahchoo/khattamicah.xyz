---
layout: post
---

<html>
<input type="file" id="file-input" />
</html>

<script>
  const fileInput = document.getElementById('file-input');

  fileInput.addEventListener('change', () => {
    const file = fileInput.files[0];
    
    if (!file) {
      return;
    }

    const reader = new FileReader();

    reader.onload = event => {
      const csv = event.target.result;
      const opml = generateOpml(csv);
      downloadOpml(opml);
    };
    reader.readAsText(file);
  });

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

</script>

      