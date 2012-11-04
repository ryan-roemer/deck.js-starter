Deck.js Starter
===============

A simple, opinionated starter kit for [deck.js][deckjs] presentations.

Introduction
============

[Deck.js][deckjs] is a fantastic HTML-based approach to presentations. This
project provides some basic Deck boilerplate, plugins and enhancements that I
find really help quick authoring of presentations.

Features:

* **[CodeMirror][cm]**: Live JavaScript code sample execution.
* **[CoffeeScript][cs]**: Support for CoffeeScript code execution.
* **[Jade Templates][jade]**: Can optionally build using Jade
  (with Markdown) support.

You can see a live [demo][demo] of the starter kit, or review / fork the
source at the starter [GitHub][gh] repository.

Installation / Use
==================

The easiest way to start with the starter git is to download a [tarball][tb] or
fork the [GitHub][gh] repository:

    $ git clone https://github.com/ryan-roemer/deck.js-starter.git my-presentation

To author using Jade, you will need Node.js installed, and to install the
required packages:

    $ cd my-presentation
    $ npm install

From here, you can edit "index.jade" to add slides using either Jade or Jade
with the Markdown enhancements (see source for demo on how to do this). Run the
"watch" script to automatically build all of your changes into the final
"index.html" file:

    $ npm run-script watch

Or, you can do manual one-off builds:

    $ npm run-script build


Licenses
========
All code not otherwise specified is Copyright 2012 Ryan Roemer.
Released under the MIT License.

[deck.js][deckjs] is Copyright Caleb Troughton and dual licensed under the
MIT and GPL licenses.

The [CodeMirror deck.js extension][cm] is Copyright Irene Ros and dual licensed
under the MIT and GPL licenses.

The [mnml deck.js theme][mnml] is Copyright Laurens Duijvesteijn and dual
licensed under the MIT and GPL licenses.

Included libraries:

* jQuery: MIT and GPL
* Modernizr: MIT and BSD
* CoffeeScript: MIT

[tb]: https://ryan-roemer.github.com/deck.js-starter/archive/master.tar.gz
[demo]: http://ryan-roemer.github.com/deck.js-starter
[gh]: https://github.com/ryan-roemer/deck.js-starter
[deckjs]: https://github.com/imakewebthings/deck.js
[jade]: http://jade-lang.com
[cm]: https://github.com/iros/deck.js-codemirror
[cs]: http://coffeescript.org/
[mnml]: https://github.com/duijf/mnml
