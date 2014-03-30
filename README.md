uline-zsh
=========

uline is a zsh plugin that provides a beautiful prompt.

Screenshot
----------

![Screenshot-2016-01-08](https://github.com/rhenium/uline/raw/images/20160108000230124.png)

Features
--------

* written in zsh script.
* runs faster than Powerline (although with very limited features).

Installation
------------

The only file you need is the 'uline' file. Copy it to somewhere (~/.zsh for
example), then append to the zsh configuration file:

    fpath+=(~/.zsh)
    precmd_functions=(uline)
    autoload -Uz uline; uline

Copyright
---------

Copyright (c) 2017 Kazuki Yamaguchi <k@rhe.jp>

uline is free software; you can redistribute it and/or modify it under the terms
of the MIT license. See COPYING for details.
