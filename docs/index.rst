Pelican
#######

Pelican is a static site generator, written in Python.

* Write your weblog entries directly with your editor of choice (vim!) in
  reStructuredText or Markdown
* A simple CLI tool to (re)generate the weblog
* Easy to interface with DVCSes and web hooks
* Completely static output is easy to host anywhere

Features
========

Pelican currently supports:

* Blog articles and pages
* Comments, via an external service (Disqus). (Please note that while
  useful, Disqus is an external service, and thus the comment data will be
  somewhat outside of your control and potentially subject to data loss.)
* Theming support (themes are created using `Jinja2 <http://jinja.pocoo.org/>`_)
* PDF generation of the articles/pages (optional)
* Publication of articles in multiple languages
* Atom/RSS feeds
* Code syntax highlighting
* Compilation of `LESS CSS <http://lesscss.org/>`_ (optional)
* Import from WordPress, Dotclear, or RSS feeds
* Integration with external tools: Twitter, Google Analytics, etc. (optional)

Why the name "Pelican"?
========================

Heh, you didn't notice? "Pelican" is an anagram for « Calepin » ;)

Source code
===========

You can access the source code at: http://github.com/getpelican/pelican/

Feedback / Contact us
=====================

If you want to see new features in Pelican, don't hesitate to chime in, clone
the repository, etc. That's open source, dude!

Send a message to "alexis at notmyidea dot org" with any requests/feedback! You
can also join the team at
`#pelican on Freenode <irc://irc.freenode.net/pelican>`_ (or if you don't have 
a IRC client handy, use `the webchat
<http://webchat.freenode.net/?channels=pelican&uio=d4>`_)
for quick feedback.

Documentation
=============

A French version of the documentation is available at :doc:`fr/index`.

.. toctree::
   :maxdepth: 2

   getting_started
   settings
   themes
   plugins
   internals
   pelican-themes
   importer
   faq
   tips
   contribute
   report
   changelog
