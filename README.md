
sketch-text-align
=================

Properly align text layers regardless of their rectangle box in Sketch

![demo][demo-image]


# Motivation

Because Sketch v3.x still has less than ideal support for font-size and line-height, especially when you are dealing with CJK language (Some say it's a limit of OSX). This plugin allow you to align text as imagined, ignoring those incorrectly calculated text rectangles.

This plugin has been tested on Sketch v3.2 and v3.3 beta


# Install

1. Download ZIP of this repo.
2. Extract and rename folder to suit your taste.
3. Put the folder in your Sketch plugin folder (Use `Plugins>Reveal Plugins Folder` to find it).

Folder name and plugin filename will show up as items in Sketch `Plugins` menu.


# Usage

1. Select multiple text layers.
2. `Alt + Cmd + L` or use `Plugins` menu.
3. Follow the dialog prompt.


# Note

This plugin does not fix multiline text layer or weird padding issues, it makes aligning multiple text layers much easier instead (so you can avoid wordwrap in Sketch).


# License

MIT

[demo-image]: http://i.imgur.com/Bx1hpLA.png
