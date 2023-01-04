---
layout: note
title:
tags: 
source:
compiler:
category:
---

# To serve manifests from Omeka

To serve manifests from Omeka, you will need to follow these steps:

1. First, make sure that the Omeka installation is properly configured to serve content over the Internet. This may involve setting up a domain name and configuring your router to forward incoming traffic to your Omeka installation.
    
2. Next, create one or more items in Omeka that represent the digital assets that you want to include in your manifest. You can do this by adding files to the items and providing metadata for each file.
    
3. Generate the manifest file(s) for the items in Omeka. There are several ways to do this, including using a plugin or writing a custom script. Some options for generating manifests in Omeka include:
    

- The IIIF Server plugin: This plugin allows you to generate IIIF manifests for items in Omeka. You can find more information about the IIIF Server plugin at [https://omeka.org/s/docs/user-manual/plugins/iiifserver/](https://omeka.org/s/docs/user-manual/plugins/iiifserver/).
- The Omeka S Manifest plugin: This plugin allows you to generate IIIF manifests for items in Omeka using the Omeka S API. You can find more information about the Omeka S Manifest plugin at [https://omeka.org/s/docs/user-manual/plugins/omeka-s-manifest/](https://omeka.org/s/docs/user-manual/plugins/omeka-s-manifest/).

4. Once you have generated the manifest file(s), you can serve them from Omeka by providing the URL of the manifest file(s) to a viewer that supports IIIF manifests, such as Mirador or OpenSeadragon. The URL of the manifest file will typically be the URL of the item in Omeka, followed by the `/iiif-manifest` path. For example, if the URL of an item in Omeka is `https://example.com/items/show/123`, the URL of the manifest file for that item would be `https://example.com/items/show/123/iiif-manifest`.