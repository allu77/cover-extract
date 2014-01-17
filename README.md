cover-extract
=============

A tool to extract cover from a cbr of cbz file.

    Usage:
	cover-extract <CBR or CBZ file>

cover-extract will extract the first image (jpg,png,gif,bmp) in alphabetical
order from the CBR or CBZ, rename it as the CBR file (with different extension)
and place it in the same directory. If such file already exists, nothing is done.

The script currently accept a single file as input. You cas easily do a batch extraction
using find, e.g.:

    find . \( -name \*.cbr -or -name \*.cbz \) -exec /usr/local/bin/cover-extract {} \;

Note: modify the following variables at the top of the script to match your configuration

    UNRAR=/usr/bin/unrar-nonfree
    UNZIP=/usr/bin/unzip
    TMPDIR=/tmp

