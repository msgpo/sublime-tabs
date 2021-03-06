# sublime-tabs

This enables sublime-style tabs in Atom.

Normally, the Tabs package will open a new tab for each file, and it will stay open even if you don't edit it.

sublime-tabs enables you to click a file through the Tree View on the left, it will open it as a "temp" file like sublime does,
and will close the tab if another tab is opened without you editing it.

[![Build Status](https://travis-ci.org/ddavison/sublime-tabs.svg?branch=master)](https://travis-ci.org/ddavison/sublime-tabs)

![example](https://raw.githubusercontent.com/ddavison/sublime-tabs/master/images/example.gif)

## To Use
Install either through the Atom package search, or by:
```sh
$ apm install sublime-tabs
```
**Note...** This package will replace the `Tabs` and `Tree View` package and disable them.  

## If for some reason...
sublime-tabs is not working... try:
* Making sure sublime-tabs is installed, enabled, and up to date
* Making sure the `Tabs` package is disabled.
* Making sure the `Tree View` package is disabled.
* Restart Atom
* Right click somewhere in an open file, and click `Reveal in tree view`

## Uninstall
If sublime-tabs isn't your thing, you can uninstall by following these steps:

1. Open your Settings
2. Search for `"Sublime Tabs"` and Uninstall
3. For the `Tabs` and `Tree View` packages, do the following:
  1. Search for the package
  2. Click `"Enable"`
