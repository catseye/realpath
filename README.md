`realpath`
==========

_Version 1.0-2022.0908_
| _Entry_ [@ catseye.tc](https://catseye.tc/node/realpath)
| _See also:_ [ellsync](https://github.com/catseye/ellsync#readme)
∘ [yastasoti](https://github.com/catseye/yastasoti#readme)
∘ [shelf](https://github.com/catseye/shelf#readme)

- - - -

This is Cat's Eye Technologies' `realpath`, a simple command-line tool that
resolves relative file paths to absolute ones.  It:

*   is written in Python 3 (tested with 3.8.10)
*   is small and has no dependencies besides Python
*   is in the public domain (see `UNLICENSE`)
*   is trivial
*   is not feature-compatible with GNU realpath
*   has no build/install system; either copy it to somewhere on your
    search path, or alter your search path to include the `script` directory
    in this repo, or use some system that solves this problem, like
    [shelf](http://catseye.tc/node/shelf).

Usage
-----

    realpath PATH

Related work
------------

*   [realpath_1](http://leapfrog.freeshell.org/Projects/real_path.shtml) —
    GPL'ed, and contains an unbuildable C version (nested comments) and an
    incompatible Perl version of realpath.
*   [dtjm/realpath](https://github.com/dtjm/realpath) — claims to be 
    "public domain" but is restricted to "non-profit use", which in my
    IANAL opinion is a contradiction in terms.
