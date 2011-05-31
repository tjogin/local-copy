Creates a local copy of a URL for inspection, debugging, whatever.
Optionally also downloads and links local copies of CSS and JavaScript.

Installation:

    Install nokogiri (http://nokogiri.org)
    Install jsbeautifier command line tool (http://jsbeautifier.com)
    git clone git://github.com/tjogin/local-copy.git
    cp local-copy/local-copy /usr/local/bin/local-copy

Usage:

    mkdir local-google
    cd local-google
    local-copy http://google.com

BSD license: go nuts
Author: tomas@jogin.com 31 May 2011
github.com/tjogin/local-copy
