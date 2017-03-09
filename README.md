deluge-copycompleted-extract
====================

This plugin for [Deluge][1] copies downloaded files to another location with the option of extracting after copy.

This is a combination of the [deluge-copycompleted][2] plugin and [deluge-extractor][3] (or simpleextractor) plugin.

I wrote this only for my environment, so only .rar, .zip and .tar files are supported. And the plugin assumes the existence of the applications "unrar", "unzip" and "tar" with no checks or warnings if they are not present. Use at your own risk!

The option to enable extraction (checkbox), has only been added to the WEB UI, not the GTK UI.

There is no support for Windows.


  [1]: http://deluge-torrent.org
  [2]: https://github.com/ultnrg/deluge-CopyCompleted
  [3]: https://github.com/cvarta/deluge-extractor
