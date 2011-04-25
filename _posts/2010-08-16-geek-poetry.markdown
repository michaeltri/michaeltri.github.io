---
layout: post
title: Geek poetry
---
# {{ page.title }}

The time will come when I also have a web site that returns random quotes with the HTTP header. I wonder why nobody ever had the idea to use this place for extremely targeted developer ads ...

    $ curl -Is slashdot.org

    HTTP/1.1 200 OK
    Server: Apache/1.3.41 (Unix) mod_perl/1.31-rc4
    SLASH_LOG_DATA: shtml
    X-Powered-By: Slash 2.005001
    X-Bender: Fry, of all the friends I've had ... you're the first.
    X-XRDS-Location: http://slashdot.org/slashdot.xrds
    Cache-Control: no-cache
    Pragma: no-cache
    Content-Type: text/html; charset=iso-8859-1
    Date: Mon, 16 Aug 2010 18:37:36 GMT
    X-Varnish: 1374087910
    Age: 0
    Connection: keep-alive


    $ curl -Is slashdot.org | egrep '^X-(F|B)' | cut -d \- -f 2

    Bender: Senseless death! The folk singer's best friend!
