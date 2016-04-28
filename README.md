# SigilPlugin_headersAsBaseForTitles
Add/modify title tags of selected xhtml files of an epub using the text of the first most elevated h* tag inside the code of each file filtered by a custom regex.

The plugin will parse the code of each selected file in search of an h1 tag, then of an h2 and so on until h6. At the first occurrence it will stop and use the text of founded tag, filtered by a search with a custom regex, to create/overwrite the title tag in the head of the document. If no occurrences will be found the title tag will be empty.

If you want to add/overwrite title tags of all xhtml files, just don't select any file in the Book Browser (or select them all, it's the same).

The regular expression you want to use to filter the header's text must be copied to the clipboard: just write it somewhere and copy it with Cmd+C (on Mac) or Ctrl+C right before launching the plugin. If the regex doesn't match anything, the entire header will be written as title.
