---
layout: note
title:
aliases: [2 Manifest]
tags: 
source:
compiler:
category:
linter-yaml-title-alias: 2 Manifest
---

The International Image Interoperability Framework (IIIF) is a set of open standards that allows for the delivery of digital images and other media resources over the web in a consistent and scalable way. It enables users to access and manipulate images and other media resources in a variety of ways, including zooming, panning, and rotating, and it supports a wide range of use cases, including digitization projects, cultural heritage institutions, libraries, and museums.

To make your files available through IIIF, you will need to set up a IIIF server. There are several IIIF servers available, both open source and commercial, and you can choose the one that best meets your needs. Some popular open source IIIF servers include:

- Loris: A lightweight, fast, and easy-to-use IIIF server written in Python
- DigiKam: A photo management application with an integrated IIIF server
- IIPImage: A high-performance image server that supports tiling, zoom, and region-of-interest features

Once you have set up your IIIF server, you will need to create IIIF manifests for your files. A IIIF manifest is a JSON document that describes the structure and content of a digital work, such as an image or a book, and provides information about how to access and manipulate it. You can create IIIF manifests manually, using a tool like the IIIF Manifest Editor, or you can use a script to generate them automatically from your files.

Once you have created your IIIF manifests, you can display your files on a website by using a IIIF viewer. There are several IIIF viewers available, both open source and commercial, and you can choose the one that best meets your needs. Some popular open source IIIF viewers include:

- Mirador: A feature-rich IIIF viewer that supports annotation, comparison, and book view modes
- Universal Viewer: A flexible and customizable IIIF viewer that supports audio and video as well as images
- OpenSeadragon: A JavaScript library that enables you to build zoomable, panning image viewers

# 2 Manifest

To generate a IIIF manifest from your images, you will need to write a script that can access the images and create the IIIF manifest in the appropriate format. There are several libraries and tools available that can help you do this, depending on the programming language you are using and the type of images you are working with.

For example, if you are using Python and your images are stored in a directory on your server, you could use the iiif-prezi library to generate a IIIF manifest. To do this, you would first install the library using pip:

Copy code

```
pip install iiif-prezi`
```

Then, you could use the following code to generate a IIIF manifest for all the images in a directory:

Copy code

```
import iiif_prezi

# Set the directory containing the images
image_dir = '/path/to/image/directory'

# Set the base URL for the IIIF server
base_url = 'https://example.com/iiif/'

# Create a new IIIF manifest
manifest = iiif_prezi.Manifest(base_url)

# Add the images to the manifest
for image_path in image_dir.glob('*.jpg'):
    manifest.add_image(image_path, base_url)

# Write the manifest to a file
with open('manifest.json', 'w') as f:
    f.write(manifest.to_json())
```

This code will generate a IIIF manifest for all the JPEG images in the specified directory and write it to a file called `manifest.json`.

You can then use this manifest to display the images on a website using a IIIF viewer.

I hope this helps! Let me know if you have any other questions.

# Cantaloupe to Mirador Pipeline

Cantaloupe is an open source IIIF image server written in Java, and Mirador is an open source IIIF viewer. Together, these two tools can be used to create a system for displaying images on a website using the IIIF protocol.

To set up a Cantaloupe-Mirador pipeline, you will need to follow these steps:

1. Install and configure Cantaloupe. This will involve setting up a Java runtime environment, downloading the Cantaloupe release package, and modifying the configuration file to specify the location of your images and the desired server behavior. You can find detailed instructions in the Cantaloupe documentation.
    
2. Install and configure Mirador. This will involve downloading the Mirador release package and modifying the configuration file to specify the location of your IIIF manifest and any other desired options. You can find detailed instructions in the Mirador documentation.
    
3. Create a IIIF manifest for your images. You can use the iiif-prezi library in Python or another tool to generate a IIIF manifest for your images.
    
4. Place the Mirador viewer on your website. You can do this by including the Mirador JavaScript and CSS files in the HTML of your website and adding an element to the page where you want the viewer to appear. You can then use the Mirador API to specify the location of the IIIF manifest and any other desired options.
    
	 