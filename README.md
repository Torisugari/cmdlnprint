Firefox Extension for Command-Line Print
========================================

This is a fork of Torisugari's code, which adds a `-noheadfoot`
option.  See [his documentation of an older
version](http://sites.google.com/site/torisugari/commandlineprint2).

When this extension is installed in your Firefox you can use it like this:

    firefox -print http://www.example.com/index.html
    firefox -print http://www.example.com/index.html -printmode PNG
    firefox -print http://www.example.com/index.html -printdelay 10
    firefox -print http://www.example.com/index.html -printmode pdf -printfile ../foo.pdf
    firefox -print http://www.example.com/index.html -printmode pdf -printfile ../foo.pdf -noheadfoot

The new `-noheadfoot` options suppresses the header and footer that
would otherwise be added to the printed page.
