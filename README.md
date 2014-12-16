According to Hoyt & Mad Genius Club Comments
============================================

From the original version of this code:
> Some of the best discussion on the net (if you like a very particular kind of discussion) happens in the comments of Scott Alexander's blog, [Slate Star Codex](http://slatestarcodex.com/). Unfortunately the thread system doesn't make it easy to see when new comments have been posted. This is a bit of code to fix that: comments posted since your last visit (or a time you specify) are outlined, and (if using the UserScript or extension) a small floating window lists them.

This is a fork to provide the same functionality on
[According to Hoyt](http://accordingtohoyt.com/) &
[Mad Genius Club](http://madgeniusclub.com/),
sites that offer some more of the best discussion on the ’net.

As of the version 1.2, it also adds to every comment a new button next to the 'reply' button allowing you to collapse the comment and all of its children.

See [screenshots here](http://imgur.com/a/ThOgM).

Installation
------------

Tested only on recent versions of Firefox and Chrome.

Firefox users:
Install Greasemonkey and open [ATH-MGC-Comments/ath-mgc.user.js][ath-mgc] in Firefox.

Chrome users:
Save [ATH-MGC-Comments/ath-mgc.user.js][ath-mgc] to disk, go to `chrome://extensions`, and drag the script onto the main body of the window.

Very Special Users (_i.e._, the site admins of ATH & MGC):
If you include a link to [ATH-MGC-Comments/ath-mgc.user.js][ath-mgc] in the site header,
then everyone gets to use it
(whether they want to or no; there is that caveat).

Usage Tips
----------

Clicking the \[-\] (only displayed if there is a nonzero number of new comments) will show or hide the list of comments. Clicking on an entry in the list will scroll you to it (provided it isn't already on the page).

You can edit the date displayed in the textbox, and the highlighted comments and comments list will update accordingly.

[ath-mgc]: http://jcsalomon.github.io/ATH-MGC-Comments/ath-mgc.user.js
