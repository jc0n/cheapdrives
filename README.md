## Cheapdrives
### About

A brief Python script by John O'Connor to find reasonably priced hard drives
from popular vendors for a bulk storage array. The script works by parsing RSS
or Atom feeds and extracting the size and price of the drives to compute a
price/GB ratio which is then sorted.

### Installation

    $ python setup.py install
     (sudo) if necessary

### Usage

Specify a file that contains one feed URL per line

    $ cheapdrives spindles.list

or manually specify one or more URLs on the command line

    $ cheapdrives http://some_url/with_rss_feed

### Dependencies

- Python 2.5+ http://www.python.org
- Feedparser http://code.google.com/p/feedparser
