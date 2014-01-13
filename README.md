cover-extract
=============

A tool to extract cover from a cbr of cbz file.

    Usage:
	cover-extract <CBR or CBZ file>

cover-extract will extract the first image jpg in alphabetical
order from the CBR or CBZ, rename it as the CBR file (with different extension)
and place it in the same directory.

Note: modify the following variables at the top of the script to match your configuration

    UNRAR=/usr/bin/unrar-nonfree
    UNZIP=/usr/bin/unzip
    TMPDIR=/tmp

