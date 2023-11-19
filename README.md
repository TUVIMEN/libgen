# Archive

Any further development has been transfered to [torge](https://github.com/TUVIMEN/torge).

# libgen

A shell script for searching on libgen.

![example](example.gif)

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - xclip
 - [recode](https://github.com/rrthomas/recode)

## Installation
    install -m 755 libgen /usr/bin

## Usage

Just type 'libgen your search', choose what you want and the link will be copied to your clipboard.

Search for scientific articles about evolution on 2nd page

    libgen -p 2 -S 'evolution'

Search for Lovecraft's fiction in pdf format

    libgen -f pdf -F 'lovecraft'

Search search for 'The Road to Serfdom' ordered by size, reversed

    libgen -r -o size 'the road to serfdom'

Get some help

    libgen -h
