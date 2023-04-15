+++
draft = false
date = 2020-08-13T05:08:21+01:00
title = "Sticky elements on mobile that work"
slug = "sticky-elements-on-mobile-that-work"
aliases = ["/blogg/sticky-elements-on-mobile-that-work"]
tags = []
categories = []
+++
In our investigation of this we found no other way to present *table of contents* to help people navigate and read long medical treatment texts. We decided to go for a sticky TOC on mobile and smaller screens.

Having gone back and forth for some time on sticky elements on *really* long pages, here's what we've learned:

* sticky elements are annoying
* as a rule they should not be used
* but exceptions do exist

So when do sticky elements on mobile actually help the user?

* they should not take up a lot of real estate on the screen
* they should be smooth and feel natural
* they should provide an entry point to something that is otherwise out of reach
* they should be fast and not hinder performance

In our case we think that providing a sticky table of contents prevent lostness. It helps the user to anchor the paragraph or section in focus. And it helps the transition from one area of the page to the next.

Preferably we avoid using the margins of the page and seek to use the bottom. That way we hope to provide a clear navigation pattern without disrupting the reading experience.


At the moment we're user testing these options to find the optimal solution.   
