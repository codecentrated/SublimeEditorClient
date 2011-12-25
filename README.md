This lets you use QuickCursor with Sublime Text 2.

= Installation

Download the [app](https://github.com/downloads/jaylevitt/SublimeEditorClient/SublimeEditorClient.app.tar.gz), uncompress it, and drag it to your Applications folder.  Restart QuickCursor and you should see SublimeEditorClient as an option.

= Credits

The code is a hacked version of Rob Tillotson's [EditorClient](https://github.com/robtillotson/EditorClient) for Emacs.
The icon is by [Nate Beaty](http://www.sublimetext.com/forum/viewtopic.php?f=2&t=1558&hilit=natebeaty+icon&start=110#p15413).

= Known bugs

* SublimeEditorClient will crash if given a Unicode character in the filename - for instance, if you are on a web page with a bullet in the title. Patches welcome; I don't know Objective C or Cocoa.

* Doesn't support the ODB ability to start at a specific line number. QuickCursor doesn't use this functionality, but other ODB applications might expect it.