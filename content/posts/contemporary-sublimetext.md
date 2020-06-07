+++
title = "Using SublimeText in 2020"
date = 2020-05-20

draft = false

[taxonomies]
category = ["development"]
tags = ["editor","tools"]
+++

It may not have all the hype it once enjoyed, but SublimeText is still a fantastic option for developers. I have used most of the text editors out there for a time, but I always find myself coming back to Sublime.

<!-- more -->

## Plugins

### Terminus

One of the main reasons I spent a lot of time using other editors is wanting a better terminal integration. Whether that's Vim/Neovim literally running inside a terminal or something like VSCode which embeds its own terminal emulator. There were efforts in the past to add a terminal to Sublime but were fairly limited and understandably finicky. Terminus is on a different level from those. It is able to spawn terminal tabs as faithful as I could imagine within the confines of a SublimeText buffer. While I wouldn't use it for tailing huge logs or other high volume tasks, it's more than good enough for popping into to fire off some git commands, spawn a dev server, and run tests.

Speaking of tests, it's also usable as a output target for the SublimeText build system. Despite the name, The build system can be used for all sorts of tasks, including firing off your test suite. And with Terminus, you get fullc olor output, and even inline screenshots of failures

### [A File Icon](https://packagecontrol.io/packages/A%20File%20Icon)

A more expansive and colorful icon pack than the default. The readme uses the phrase "for improved visual grepping" and that's more succint than what I was attempting to write.

### [Origami](https://packagecontrol.io/packages/Origami)

Origami both supercharges and simplifies splitting panes. It adds a layer of keyboard shortcuts for quick creating/destroying/resizing panes within a window.

### [LSP](https://packagecontrol.io/packages/LSP)

Language Servers are the biggest innovation in the code editing space in the last decade. Instead of relying on plugins that are tied to one editor and one language, they provide a common API for IDE-like features (linting, autocompletion, goto definition, etc) for any langauge that has a corresponding server installed, which is nearly all of them now. LSP brings this power to SublimeText.

### Colorsublime

Preview and apply syntax colorschemes from the vast [ColorSublime](https://colorsublime.github.io/) gallery. I'm a fan of the Monokai and Dracula families.

### Theme: Fladaptive

Sublime comes with a theme called "Adaptive". Adaptive true to its name will take its color cues from your OS/Desktop theme. What Fladaptive does is take that and flattens out some of Sublime's default quirky UI bits, like the chunky tabs. It's something of an anti-theme, it really helps make Sublime feel more in line with your other desktop apps.

## Settings