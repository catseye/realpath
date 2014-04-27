realpath
========

This is Cat's Eye Technologies' `realpath`, a simple command-line tool that
resolves relative filenames to absolute ones.  It:

*   is written in Python
*   is small and has no dependencies besides Python
*   is in the public domain (see `UNLICENSE`)
*   is trivial
*   is not feature-compatible with GNU realpath
*   has no build/install system; either copy it to somewhere on your
    search path, or alter your search path to include the `script` directory
    in this repo, or use some system that solves this problem, like
    [toolshelf](http://catseye.tc/node/toolshelf).

Usage
-----

    realpath _path_

Related work
------------

*   [realpath_1](http://leapfrog.freeshell.org/Projects/real_path.shtml) —
    GPL'ed, and contains an unbuildable C version (nested comments) and an
    incompatible Perl version of realpath.
*   [dtjm/realpath](https://github.com/dtjm/realpath) — claims to be 
    "public domain" but is restricted to "non-profit use", which in my
    IANAL opinion is a contradiction in terms.
