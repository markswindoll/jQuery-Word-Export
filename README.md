jQuery-Word-Export
==================

jQuery plugin for exporting HTML and images to a Microsoft Word document

Dependencies: [jQuery](http://jquery.com/) and [FileSaver.js](https://github.com/eligrey/FileSaver.js/)

This plugin takes advantage of the fact that MS Word can interpret HTML as a document. Specifically, this plugin leverages the [MHTML](http://en.wikipedia.org/wiki/MHTML) archive format in order to embed images directly into the file, so they can be viewed offline.

Unfortunately, LibreOffice and, probably, other similar word processors read the output file as plain text rather than interpreting it is a document, so the output of this plugin will only work with MS Word proper.

Click here for demo: [http://markswindoll.github.io/jquery-word-export/](http://markswindoll.github.io/jquery-word-export/)
