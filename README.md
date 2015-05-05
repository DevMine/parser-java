# Parsers

DevMine parsers are meant to parse source code repositories and produce an
extended custom abstract syntax tree as JSON, as defined by
[srcanlzr](http://devmine.ch/doc/srcanlzr/).

Each parser is required to be able to read either directly from a folder
containing the source code as text files or directly from a tar archive.

The output of the languages parsers can be redirected to `srcanlzr` or
[repotool](http://devmine.ch/doc/repotool/) for further processing.

## Installation

Each of the language parser can be installed using
[srctool](http://devmine.ch/doc/srctool/) with the `install` command.
See `srctool help` for more details.
