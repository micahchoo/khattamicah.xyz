---
layout: note
title:
tags: 
source:
compiler:
category:
---

# Cantaloupe tutorial

> what is the use of cantaloupe

Cantaloupe is an open-source, lightweight image server that allows you to serve images and other media assets over the Internet. It is designed to be easy to install and configure, and it supports various features such as image manipulation, authentication, and caching.

Cantaloupe can be used in a variety of contexts, including:

- Serving images for websites and web-based applications
- Serving images for digital collections and repositories
- Serving images for online publications and scholarly works

Cantaloupe can be integrated with a variety of applications and tools, such as content management systems, digital asset management systems, and image viewers. It can also be used in conjunction with other image servers and image processing libraries, such as the International Image Interoperability Framework (IIIF) server and the ImageMagick library.

I hope this helps! Let me know if you have any other questions.

![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2730%27%20height=%2730%27/%3e)![Micah Alex](https://chat.openai.com/_next/image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fa%2FAEdFTp4BN75sknBB-hUIvqcR57LUz0M2rA2QhaFOsI1D%3Ds96-c&w=64&q=75)

> Serving images for websites and web-based applications how to do this

To serve images for websites and web-based applications using Cantaloupe, you will need to follow these steps:

1. First, make sure that Cantaloupe is properly installed and configured on your server. You can find instructions for installing and configuring Cantaloupe at [https://cantaloupe-project.github.io/](https://cantaloupe-project.github.io/).
    
2. Next, upload the images that you want to serve to a directory on your server. You will need to specify the path to this directory in the Cantaloupe configuration file.
    
3. Modify the Cantaloupe configuration file to specify the location of the images and any other desired settings, such as the maximum image size or the allowed image formats. You can find more information about the configuration options for Cantaloupe at [https://cantaloupe-project.github.io/docs/configuration.html](https://cantaloupe-project.github.io/docs/configuration.html).
    
4. Start the Cantaloupe server. You can do this by running the `cantaloupe` command from the command line.
    
5. In your website or web-based application, use the URL of the Cantaloupe server to display the images. The URL of an image served by Cantaloupe will typically have the following format: `http://<cantaloupe-server-url>/iiif/<image-identifier>/<region>/<size>/<rotation>/<quality>.<format>`.
    

I hope this helps! Let me know if you have any other questions.

![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2730%27%20height=%2730%27/%3e)![Micah Alex](https://chat.openai.com/_next/image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fa%2FAEdFTp4BN75sknBB-hUIvqcR57LUz0M2rA2QhaFOsI1D%3Ds96-c&w=64&q=75)

> what to do when you have multiple directories

If you have multiple directories containing images that you want to serve using Cantaloupe, you can specify multiple directories in the Cantaloupe configuration file.

To do this, you will need to modify the `FilesystemResolver` section of the configuration file to specify the paths to the directories that contain the images. For example:

Copy code

`<FilesystemResolver>   <BaseDirectory>/path/to/directory1</BaseDirectory>   <BaseDirectory>/path/to/directory2</BaseDirectory>   <BaseDirectory>/path/to/directory3</BaseDirectory> </FilesystemResolver>`

Cantaloupe will search these directories in the order they are specified, so you may want to order them from most specific to least specific to ensure that the correct images are displayed.

You can also use the `<Pattern>` element to specify a pattern for matching image files within the directories. For example:

Copy code

`<FilesystemResolver>   <BaseDirectory>/path/to/directory1</BaseDirectory>   <Pattern>.*\.jpg</Pattern>   <BaseDirectory>/path/to/directory2</BaseDirectory>   <Pattern>.*\.png</Pattern> </FilesystemResolver>`

In this example, Cantaloupe will search for JPEG images in the `/path/to/directory1` directory and PNG images in the `/path/to/directory2` directory.

I hope this helps! Let me know if you have any other questions.

![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2730%27%20height=%2730%27/%3e)![Micah Alex](https://chat.openai.com/_next/image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fa%2FAEdFTp4BN75sknBB-hUIvqcR57LUz0M2rA2QhaFOsI1D%3Ds96-c&w=64&q=75)

> can i create collections with cantaloupe

Cantaloupe does not directly support the creation of collections of images. However, you can use Cantaloupe in conjunction with other tools to create collections of images that can be displayed in a viewer.

One option is to use the International Image Interoperability Framework (IIIF) to create and serve collections of images using Cantaloupe. IIIF is a set of standards and tools for sharing and displaying digital images on the web, and it includes a specification for collections of images called the IIIF Manifest specification.

To create and serve collections of images using IIIF and Cantaloupe, you will need to:

1. Generate IIIF manifests for the images that you want to include in your collection. You can use a tool such as the IIIF Server plugin for Omeka or the IIIF Manifest Generator to generate IIIF manifests for your images.
    
2. Serve the IIIF manifests using Cantaloupe. You can do this by modifying the Cantaloupe configuration file to specify the location of the IIIF manifests and by starting the Cantaloupe server.
    
3. Use a IIIF-compliant viewer, such as Mirador or OpenSeadragon, to display the collections of images. You can pass the URL of the IIIF manifest to the viewer to display the collection.
    

I hope this helps! Let me know if you have any other questions.

![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2730%27%20height=%2730%27/%3e)![Micah Alex](https://chat.openai.com/_next/image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fa%2FAEdFTp4BN75sknBB-hUIvqcR57LUz0M2rA2QhaFOsI1D%3Ds96-c&w=64&q=75)

> Serve the IIIF manifests using Cantaloupe. how?

To serve IIIF manifests using Cantaloupe, you will need to follow these steps:

1. First, make sure that Cantaloupe is properly installed and configured on your server. You can find instructions for installing and configuring Cantaloupe at [https://cantaloupe-project.github.io/](https://cantaloupe-project.github.io/).
    
2. Next, generate the IIIF manifests for the images that you want to include in your collection. You can use a tool such as the IIIF Server plugin for Omeka or the IIIF Manifest Generator to generate IIIF manifests for your images.
    
3. Upload the IIIF manifests to a directory on your server. You will need to specify the path to this directory in the Cantaloupe configuration file.
    
4. Modify the Cantaloupe configuration file to specify the location of the IIIF manifests and any other desired settings. You will need to add a `<FilesystemResolver>` element to the configuration file and specify the path to the directory containing the IIIF manifests. You may also want to specify a `<Pattern>` element to match the IIIF manifest files. For example:
    

Copy code

`<FilesystemResolver>   <BaseDirectory>/path/to/iiif-manifests</BaseDirectory>   <Pattern>.*\.json</Pattern> </FilesystemResolver>`

5. Start the Cantaloupe server. You can do this by running the `cantaloupe` command from the command line.
    
6. Use a IIIF-compliant viewer, such as Mirador or OpenSeadragon, to display the collections of images. You can pass the URL of the IIIF manifest to the viewer to display the collection. The URL of a IIIF manifest served by Cantaloupe will typically have the following format: `http://<cantaloupe-server-url>/ii
    

![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2730%27%20height=%2730%27/%3e)![Micah Alex](https://chat.openai.com/_next/image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fa%2FAEdFTp4BN75sknBB-hUIvqcR57LUz0M2rA2QhaFOsI1D%3Ds96-c&w=64&q=75)

> The URL of a IIIF manifest served by Cantaloupe will typically have the following format:

The URL of a IIIF manifest served by Cantaloupe will typically have the following format: `http://<cantaloupe-server-url>/iiif/<manifest-identifier>/manifest`.

For example, if the Cantaloupe server is running on `localhost` and the IIIF manifest file is stored in the `iiif-manifests` directory with the identifier `example-manifest`, the URL of the IIIF manifest would be: `http://localhost/iiif/example-manifest/manifest`.

You can pass this URL to a IIIF-compliant viewer, such as Mirador or OpenSeadragon, to display the collection of images.

I hope this helps! Let me know if you have any other questions.