jwm-config
======================================================================

A set of scripts and configuration files to configure JWM with dynamic
menus full of icons, sane keybindings, and a simple theme that leaves
plenty of screen space.

Requirements:
----------------------------------------------------------------------

Requires Python 3.  To work fully, expects tilda, nm-applet, and
fdpowermon to be installed.

Flaws:
----------------------------------------------------------------------

Causes a 5-second delay (on my slow machine) at start of JWM.  Before
the .onstart script was changed to generate XML files at JWM startup,
the 5-second delay happened every time the menu was shown, so it's an
improvement.  I don't know why it takes so long, as the scripts are
much faster than that to run manually.

Installation:
----------------------------------------------------------------------

Run `python3 deploy.py`.
