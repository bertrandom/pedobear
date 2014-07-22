pedobear
========

Patches Google Chrome for Mac OS X's resource file to replace the incognito icon with [Pedobear](http://en.wikipedia.org/wiki/Pedobear).

Basically, turn this:

![](https://github.com/bertrandom/pedobear/blob/gh-pages/images/incognito_original.png)

into this:

![](https://github.com/bertrandom/pedobear/blob/gh-pages/images/incognito_pedobear.png)

## Usage

Quit Google Chrome. (⌘-Q)

Run:

`./pedobear.py`

It should automatically find the resource file, back it up, and patch it with pedobear.

Open Google Chrome and open a new incognito window. You should see pedobear!

If you want to restore the original image from the backup, run:

`./pedobear.py --restore`

