# SigilPlugin_headersAsBaseForTitles
Add/modify title tags of selected xhtml files of an epub using the text of the first most elevated h* tag inside the code of each file filtered by a custom regex.

If you want to add/overwrite title tags of all xhtml files, just don't select any file in the Book Browser (or select them all, it's the same).

The regular expression you want to use to filter the header's text must be copied to the clipboard: just write it somewhere and copy it with Cmd+C (on Mac) or Ctrl+C right before launching the plugin. If the regex doesn't match anything, the entire header will be written as title.
