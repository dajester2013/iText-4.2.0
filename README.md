# iText is a Java PDF library originally dual licensed under MPL/LGPL #

## Background ##

Beginning with version 5.0 the developers have moved to the AGPL to improve their ability to sell commercial licenses. I fully respect the developers' wishes and rights. To assist those desiring to stick with the old license I'm making the final MPL/LGPL version more easily available.

## Changes ##
This repo has the following changes from forked and merged repositories:
 - upgraded compilation for java 8
 - repackaged together with bouncy castle 1.46 to quickly avoid conflicts with bouncy castle changed API (via class relocation to old.* package)
 - in case of unexpected end of PDF file the IOException is thrown (not PDFNull)
 - merged patch from Steven to fix NPE in XFA Form (escapeSom method)
 - merged UnembedFontPdfSmartCopy functionality from Vicente Alencar


## Contributing ##
This is a static mirror!
iText has moved on to its new license, and it's not my intention to continue to develop this repo as a fork.
If you'd like to contribute to iText, that's awesome! I encourage you to!

Here are some options:
- If you are okay with the AGPL, send your contributions [upstream](http://itextpdf.com/).
- If you want to stay with LGPL/MPL then you can maintain your own fork of this repo, or start a brand new project starting from this code base.

Good luck!

## [Javadocs](http://kulatamicuda.github.com/iText-4.2.0/) ##

