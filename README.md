# pyzsigramble

A zsig scrambler for Zephyr messages, implemented in Python.

## Instructions

Copy `zsigramble` to somewhere in your `$PATH`; then, in `barnowl`, execute

    :startup set zsigproc 'zsigramble ~/path/to/your/zsigs'

to set the zsig generator program now and for restarts. The default location
for zsigs is `~/.owl/zsigs`, which is where `zsigramble` will look if called
without arguments.

As `zsigramble` is also in `slz`'s Athena locker, you can instead do

    :startup set zsigproc 'athrun slz zsigramble ~/path/to/your/zsigs'

If you have set zsigs before, make sure to

    :set zsig ''
    :set zsigfunc ''

