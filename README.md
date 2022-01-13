# A fork version of the `tree` command for Linux

This repository contains a modified version of `tree`---the well-known recursive directory listing program in Linux.

## Information

* Homepage of `tree`: http://mama.indstate.edu/users/ice/tree/.
* Modified from version: 2.0.1. [[source](http://mama.indstate.edu/users/ice/tree/src/tree-2.0.1.tgz)]

## Changes

* Added `--print-info-side` and `--print-info-tooltips` options to print out the comments of a file in the HTML output, either right next to the file or as mouse over tooltips.
* Added `--simple-html` option to print out only HTML body (no doctype, metadata, or css). 
* Added `--footer M` option to print out a message `M` before `tree`'s copyright information.
* Removed the appending of `/00Tree.html` to the end of the URL to a directory.

