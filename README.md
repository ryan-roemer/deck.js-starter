Deck.js Boilerplate
===================

TODO:

- Upload to GH
- GH pages.
- Slide: GH Pages, Repo
- Custom CSS (links, etc.)
- NPM: build, watch targets (and make work!).
- Add subtitle CSS for title slide.
- Fork me banner on all / first slide.

[Deck.js] is a fantastic HTML-based approach to presentations. This is some
basic boilerplate code for my talks, including the following tweaks and
plugins:

* CodeMirror:
* Jade: "index.jade" can be built to "index.html", or you can edit "index.html"
  directly without building.


Auto-build (watch) HTML:

    $ npm run-script watch

Build HTML manually:

    $ npm run-script build


Licenses
========
All slide code not otherwise specified is Copyright 2012 Ryan Roemer.
Released under the MIT License.

[deck.js][deckjs] is Copyright Caleb Troughton and dual licensed under the
MIT and GPL licenses.

The [CodeMirror deck.js extension][cm] is Copyright Irene Ros and dual licensed
under the MIT and GPL licenses.

Included libraries:

* jQuery: MIT and GPL
* Modernizr: MIT and BSD
* CoffeeScript: MIT

[deckjs]: https://github.com/imakewebthings/deck.js
[jade]: https://github.com/iros/deck.js-codemirror
[cm]: https://github.com/iros/deck.js-codemirror
