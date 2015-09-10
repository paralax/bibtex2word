# bibtex2word

Processes Bibtex files, produces Word Source.xml output

# why?

Because I use Word for work, and I prefer to manage citations in Bibtex rather than Word's janky citation manager. I export citations from Google Scholar (or Mendeley) and process them.

# how?

simple usage:

    ~/bin/bibtex2word.py -i citations.bib

more advanced usage:

    ~/bin/bibtex2word.py -i citations.bib \
       -a "/Users/me/Library/Application Support/Microsoft/Office/Sources.xml" \
       -o /tmp/Sources.xml

then copy `/tmp/Sources.xml` into place, restart Word, and poof.

# bugs?

yeah, probably, please send a PR if you find any. or enhancements. 
