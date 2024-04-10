# TextformatterImgDataUri
Output small images as data URLs in ProcessWire CMS

Instead of linking to each image, the module outputs the actual image data inside the HTML in the form of a data: URL.
This can speed up the loading of pages by reducing the number of requests, especially when page caching is active.

# Status

This is a proof-of-concept module. Since I'm not actively using it, I have to rely on you to report any issues you find.

# Usage

- Install the module by downloading the zip and extracting it into site/modules in your ProcessWire installation;
- Configure the maximum size of images that should be included as data URLs in the source code;
- Add TestformatterImgDataUri in the configuration of the textarea fields this should be applied to.

# License

Licensed under the Unlicense (see README.md for details).
