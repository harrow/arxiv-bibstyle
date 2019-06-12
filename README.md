# arxiv-bibstyle
The usual bibtex formats don't include an eprint field.
The arXiv has modified versions of some of the standard bibtex style files (habbrv.bst, hunsrt.bst, etc.) that include eprint fields but without hyperlinks.  You can find them at
https://arxiv.org/help/hypertex/bibstyles

This repository contains further modified style files in which the eprint fields have hyperlinks.  To use them just add "eprint" to your bibtex entries like this:

@article{ABC,
author = {Alpha and Beta and Gamma},
title = {A paper},
year = {2019},
journal = {Journal of Papers},
eprint = {1901.00000}
}
