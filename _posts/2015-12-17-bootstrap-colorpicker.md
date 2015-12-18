---
layout: post
title: "Bootstrap Colorpicker inside e107"
description: "Making hippy e107 babies since 2015"
tags: [e107, plugins, bootstrap]
comments: true
---

There's this really neat [script](https://github.com/mjolnic/bootstrap-colorpicker/) that allows you to gather an HTML hexcode from a popout box using JavaScript.

e107 does not contain any method for picking an HTML hexcode. I needed something like this for [Forecasty](http://github.com/septor/forecasty) and some other plugins I plan on writing in the future. I requested this be added to the core, since I think it's a great idea, but was shot down since it probably wouldn't be used by many people and isn't used in the core at all. I basically agree, so I did what any sensible programmer/coder would do in this situation. I wrote a plugin for it.

Using it is simple. Just grab the files form the repo (I might make a release to make this easier), upload, install, and then jump to the configuration > preferences. Now enable the toggle. Tada, it's ready. Adding the `colorpicker` class to any applicable form element now makes that element able to display a colorselector.

There's some examples in the [README](https://github.com/septor/bootstrap-colorpicker/blob/master/README.md) file that should help anyone intersted in using this out.
