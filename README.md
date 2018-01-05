According to Hoyt Comments
============================================

From the original version of this code:
> Some of the best discussion on the net (if you like a very particular kind of discussion) happens in the comments of Scott Alexander's blog, [Slate Star Codex](http://slatestarcodex.com/). Unfortunately the thread system doesn't make it easy to see when new comments have been posted. This is a bit of code to fix that: comments posted since your last visit (or a time you specify) are outlined, and (if using the UserScript or extension) a small floating window lists them.

This is a fork to add the same new features
to the comment systems at
[According to Hoyt](http://accordingtohoyt.com/),
a site that offers some more of the best discussion on the ’net.

In particular:

- New comments are highlighted and given the searchable text “~new~”
  so that you can C-f through them in the order they appear on the page.
- An expandable box appears in the upper-right,
  which allows you to set the time after which comments are highlighted
  and gives you a list of new comments.
  Clicking an entries in the list will bring you to that entry.
See [screenshots here](http://imgur.com/a/ThOgM).

Installation
------------

Tested only on recent versions of Firefox and Chrome.

Firefox users:
Install [Greasemonkey][greasemonkey]
and open [ATH-Comments/ath.user.js][ath] in Firefox.

Chrome users:
Save [ATH-Comments/ath.user.js][ath] to disk,
go to `chrome://extensions`,
and drag the script onto the main body of the window.

Very Special Users (_i.e._, the site admins of ATH):
If you include a link to [ATH-Comments/ath.user.js][ath] in the site header,
then everyone gets to use it
(whether they want to or no; there is that caveat).

[ath]: http://jcsalomon.github.io/ATH-MGC-Comments/ath.user.js
[greasemonkey]: http://greasespot.net/
