![https://github.com/cmpilato/thotkeeper/blob/master/www/thotkeeper-logo.jpg](https://github.com/cmpilato/thotkeeper/blob/master/www/thotkeeper-logo.jpg)

## ThotKeeper — cross-platform personal daily journaling ##

ThotKeeper is a simple, open source, daily journal application created
by [C. Michael Pilato](http://www.cmichaelpilato.com) for his wife,
Amy. Amy was recording journal entries on paper or in a growing
Microsoft Word document. Each of these methods has its pros and cons,
but the cons frightened Mike. Paper is charming and personal, but gets
lost or damaged awfully easily. Word documents are digital and easy to
backup, but bind the user to the availability of software which parses
that proprietary format. Mike figured an XML storage format would work
just fine, and with enough GUI goodness to navigate the hunks of
information in the file, Amy might actually be encouraged to write
more. So in 2004, he began working on ThotKeeper.

ThotKeeper is written in the Python programming language, which means
it runs on many different platforms. It's built around the wxPython
toolkit, which uses native widgets on the various platforms. That
means that when you run ThotKeeper on a Windows machine, it looks like
a native Windows application; when running under Linux, it looks like
a Linux/GTK application.

Others have since come along to help Mike develop ThotKeeper.

## Features ##

  * Cross-platform functionality with native widgets
  * Simple, easy-to-navigate interface
  * XML storage format
  * Support for multiple entries per day
  * Per-entry authors
  * Hierarchical tag support

## Screenshots ##

(These screenshots are of ThotKeeper 0.1.)

| **Windows** | **Ubuntu Linux** |
|:------------|:-----------------|
| ![](https://github.com/cmpilato/thotkeeper/blob/master/www/thotkeeper-win32-thumb.jpg)| ![](https://github.com/cmpilato/thotkeeper/blob/master/www/thotkeeper-linux-thumb.jpg) |


## What You Need ##

To run ThotKeeper, you need a few bits of software:

  * [ThotKeeper](https://github.com/cmpilato/thotkeeper/releases) —
    This one's obvious, right?
  * [Python](http://www.python.org/) — the Python programming language
    (version 2.3 or greater)
  * [wxPython](http://www.wxpython.org/) — Python interfaces to the
    wxWidgets cross-platform GUI library (version 2.8 or greater, and
    compiled for the correct version of Python)