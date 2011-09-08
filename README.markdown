## Command line music tagger/renamer for Linux*

* might work on other OSes too.


Requires Python2.x and (TagPy)[http://mathema.tician.de/software/tagpy], which
is probably in your distro's repositories, perhaps as tagpy, or taglib-python
or something similar.

The basic premise is that every so often you try to rip a CD and either there's
no meta data or it's hideously incorrect. Many music players offer a way to
easily edit your tracks' tags, but sometimes the easiest way would be to copy
the tracklist from Wikipedia or Amazon and have a script do the rest.

It does quite a lot more as well; you can attempt to have it map "track01.flac"
to the nth track in the tracklist.

You don't need to specify a tracklist: you can update the artist/album/title/etc
fields on the command line.

It will also rename your files to reflect their new metadata, i.e. if you tag
"track01.flac" with a title/album/artist/etc, it can rename the file to, for
example, "artist/album/trackno - title.flac" (you can specify your own format)

Run with --help to get a feel for all the options, but make sure you first run
any operations with --saferun to get a summary of what will be done.