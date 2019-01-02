This is a fork of FuckFuckAdblock that fixes a bug, since the original repo is readOnly now.

Our site uses Rollbar to track Javascript issues, and evidently installling the `FuckFuckAdBlock` script in Microsoft edge generates thousands of errors every page load.  This version of the script should at least catch that error and avoid spamming us with unhandled exceptions.

I haven't tested this script, because fuck Microsoft Edge.  I get the feeling that FuckFuckAdBlock will never work at all in Edge, so why does this user even have it?


FuckFuckAdblock
===============

A simple userscript that acts like FuckAdBlock.js (A well known adblock detector) but always says that no adblock was detected. Just install it using [Tampermonkey][tampermonkey] (chrome) or [Greasemonkey][greasemonkey] (Firefox) by clicking [here][raw] and try it out at http://sitexw.fr/fuckadblock/. FuckFuckAdBlock works on any version of FuckAdBlock. [It's kinda like a trace buster buster][tracebusterbuster]

## This script will only counter FuckAdBlock.js and is not a general purpose anti-anti-adblocker

![screenshot](http://i.imgur.com/slDcOAI.png)
![screenshot beta](http://i.imgur.com/3neSZtH.png)

# License 

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 

Version 2, December 2004

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0. You just DO WHAT THE FUCK YOU WANT TO.
```

[tracebusterbuster]: http://www.youtube.com/watch?v=Iw3G80bplTg
[tampermonkey]: https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
[greasemonkey]: https://addons.mozilla.org/nl/firefox/addon/greasemonkey/
[raw]: https://raw.githubusercontent.com/Mechazawa/FuckFuckAdblock/master/FuckFuckAdBlock.user.js
