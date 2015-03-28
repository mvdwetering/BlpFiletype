BlpFiletype
===========

This is a filetype plugin for Paint.NET for an image file format used by several Blizzard games (e.g. World of Warcraft)

The plugin is just a tiny wrapper around the excellent SereniaBLPLib which does the actual BLP file reading.
SereniaBLPLib is available under the MIT license at https://github.com/WoW-Tools/SereniaBLPLib

To install the plugin perform the following steps:
 * Put the DLL in the <Paint.NET>/FileTypes directory (default location is C:\Program Files\paint.net\FileTypes)
 * Restart Paint.NET if you have it open

 
Fi you are interested in writing Paint.NET filetypes you might want to take a look at the following:

Basic filetype plugin:
http://www.codeproject.com/Articles/23898/Creating-Paint-NET-FileType-Plugins
 
Filetypes that can provide options in the save dialogs of Paint.NET:
http://forums.getpaint.net/index.php?/topic/26034-propertybasedfiletype-template-using-indirectui/
https://www.isimonbrown.co.uk/using-indirectui-rules/
 