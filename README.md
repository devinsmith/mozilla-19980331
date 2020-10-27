# mozilla

This repo contains the very first open source version of Mozilla with some
slight modifications.

The source is originally from here:
https://archive.mozilla.org/pub/mozilla/source/

and is based on mozilla-19980331-unix.tar.gz.

This is a version of Mozilla with the [Mariner layout engine](https://en.wikipedia.org/wiki/Mariner_(browser_engine)).

# Modifications

The original release of mozilla has a GCC 2.7.2 requirement, but these days we
are using newer compilers. This repo still compiles using the C++98 standard
(and there's no C++11 here)
but GCC 2.7.2 was a bit more "forgiving" about the C++ that was considered
valid and so small changes have been made to get it to work on newer compilers.

The other change we've made is allowing this to be built on the amd64/x86\_64
architecture.

