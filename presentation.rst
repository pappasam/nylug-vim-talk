:title: My Great Hovercraft Presentation
:author: John Doe
:date: January 1st, 3000
:abstract: This is an incredible abstract. Please enjoy reading it!
:css: style.css
:skip-help: true
:data-transition-duration: 0

----

:data-x: r2000
:data-y: r0

Neovim: the Kernel of text editing
==================================

Speaker: Samuel Roeca

----

Overview
========

Throughline: Neovim will both grow on you and with you. You need to approach it thoughtfully and treat it with respect.

1. Past: Vi -> Vim -> NeoVim
2. Present: you can code your way!
3. Future: the Kernel of text editing

.. note::

    In this talk, I cover the past, present, and future of NeoVim

    * Past: evolution, from now-ancient hardware to modern, remote servers
    * Present: handle editing needs for anyone willing to put in the effort
    * Future: power text editing everywhere, even for those who don't know what Neovim actually is

----

Past: Vi -> Vim -> NeoVim
=========================

----

VI
==

* Discuss VI, and the story behind it

----

Vim
===

* Give brief timeline of Vim

----

Vim -> Neovim
=============

* Discuss drama surrounding the fork
* Caveat that, from now on, I will refer exculsively to Neovim

----

Present: you can code your way!
===============================

----

* Vim does some things great, but it's up to you to choose good tools to do other stuff

----

Choose an operating system
==========================

* I'm on a POSIX-ish system (Ubuntu 18.04)

----

Choose a terminal emulator
==========================

* What is a terminal emulator?
* Discuss how Neovim is run from, and in, a terminal emulator
* Considerations for terminal emulator with Neovim in mind
    * Adherence to standards
    * Shell compatibility
    * Font compatibility (emojis, etc)
    * Speed
* I recommend Alacrity

----

Choose a shell
==============

* What is a shell?
* Different shells: Bash, Zsh, Fish, etc
* Considerations for shells with Neovim in mind
    * POSIX
    * Terminal features
* I recommend Zsh: has some features Bash cannot have withot sacrificing

----

Choose a terminal window manager
================================

* Difference between a terminal emulator and a terminal window manager
* I recommend tmux, since it's inspired by Vim and has similar key bindings

----

Finally, we can edit text!
==========================

----

Native Functionality
====================

START HERE!

----

Future: the Kernel of text editing
==================================

----

Tux
===

.. https://commons.wikimedia.org/wiki/File:TUX_G2.svg
.. Maxo based opoun the work File:Tux-G2.png [Public domain], from Wikimedia Commons
.. image:: ./img/tux.png
    :height: 500px
    :alt: This image is of Tmux. Locally stored.

----

:class: left-align

Watch, from https
=================

.. image:: https://upload.wikimedia.org/wikipedia/commons/4/45/MontreGousset001.jpg
    :height: 500px
    :alt: By Isabelle Grosjean ZA - Self-published work by ZA, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=144336

.. note::

    Notice how this slide is also left-aligned. Cool, right?

----

Diagram
=======

|uml_diagram|

.. |uml_diagram| image:: ./instance/diagram.svg
    :height: 500px
    :alt: You can substitute images using this syntax

.. note::

    See the image substitution. Don't be afraid!

----

Some Code
=========

.. code:: python

    def hello():
        return "world"

----

Some "Substep" Points
=====================

.. class:: substep

My first point

.. class:: substep

My second point

.. note::

    The points:

    * My first point
    * My second point

----

Any questions?
==============

.. note::

    Hopefully there are lots of questions!
