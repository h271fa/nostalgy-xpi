Summary
=======

Nostalgy is an extension for Mozilla Thunderbird whose purpose is to
save time by doing more operations with the keyboard. If you want to
use Thunderbird without sacrificing the productivity you had with good
old mutt/pine, this extension is for you!

It is especially useful if you have long folderlists and need to sort emails 
into those folders.

Nostalgy adds keyboard shortcuts to change folder, move/copy messages,
with folder name auto-completion (using only the keyboard).  It also
includes a system of rules to suggest a target folder for saving
messages; re-creates Eudora's Alt-Click; facilitates navigation in the
3-pane window; makes it easy to change between To/Bcc/Cc fields in the
composer. All that with the keyboard only!

Other keyboard actions include: changing focus between panes, scroll
the message while keeping the focus on the thread pane, changing
header in the composer (To/Cc/Bcc), adding an attachment, hide the
folder view.


Installation
============

The easiest way to install Thunderbird is through  Thunderbird`s addon page. It
will automatically update itself when new versions are released.

You can also try the latest development versions from https://github.com/nostalgy/nostalgy


Note: to produce an .xpi file from a git clone:

    git archive --format=zip --output nostalgy.zip HEAD


Authors
=======

Alain Frisch is the original author.

Many users contributed patches, in particular to adapt Nostalgy to run
with newer versions of Thunderbird.  They are credited in the [CHANGES.txt](CHANGES.txt) file.

Special thanks to Klaus Buecher, who contributed a significant rewrite of the code base
to make it run with TB 68, and to Claas Augner who helped in the reviewing effort.
