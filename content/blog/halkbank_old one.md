---
title: "Halkbank (Halk Bank) - TVC"
subtitle: ""
excerpt: "In 2018, Halkbank which is a well-known Turkish Bank, was celebrating It's 80th years. As the advertising of the brand, we created a campaign that include TVC, Radio and print media."
date: 2020-07-10
author: "Sinem Celenk"
draft: false
images:
- /blog/assets/halkbank_tumbnail.png
series:
- Getting Started
tags:
- portfolio
categories:
- Case Studies
# layout options: single or single-sidebar
layout: single-sidebar
---
### In 2018, Halkbank which is a well-known Turkish Bank, was celebrating It's 80th years. As the advertising of the brand, we created a campaign that include TVC, Radio and print media.

---

[Watch the commercial](https://www.youtube.com/embed/0zP8lFqNvtY)


Since I began building websites in Y2K, I've lost count how many times the phrase "...there's got to be a better way to do this" has passed my lips. Most times, while fighting with floats and widths of content and sidebars or just basically trying to get something beside something else without using a stupid `TABLE`.

Well, technology sure has come a long way since slicing up images to match the table-based layout that was just created in Dreamweaver. You'd be surprised (or maybe you wouldn't) how challenging the standard header, content, sidebar, footer layout could be to actually get right.

{{< figure src="/blog/assets/css-grid-cover.png" alt="Traditional right sidebar layout" caption="A visual example of the traditional right sidebar layout" >}}

<iframe width="560" height="315" src="https://www.youtube.com/embed/0zP8lFqNvtY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

### <dfn title="Ermahgerd is a humorous version of the phrase oh my god, written as though pronounced with a heavy influence of extra Rs. It's meant to imitate the sound of someone speaking through a retainer.">ERMAHGERD</dfn>

A proper grid is what we always wanted, no ... _needed_ to build websites with a solid, unbreakable structure. And that's why I used it in this theme. I call this feature a "scaffold" because none of the _content_ is laid out on this grid. Only the main _structure_: consisting of the `header`, `footer`, `main`, `aside`, and `footer`. As you can tell by this quote from the [W3C](https://www.w3.org/TR/css-grid-1/) on the candidate recommendation itself, Grid is the perfect tool for the job:

> ##### CSS Grid Layout Module


>
> This CSS module defines a two-dimensional grid-based layout system, optimized for user interface design. In the grid layout model, the children of a grid container can be positioned into arbitrary slots in a predefined flexible or fixed-size layout grid.
>
> — _W3C_

CSS Grid is a total game changer, IMHO. Compared to the bottomless pit of despair that is the old way, the new way of building a site structure can be done in as little as 5 lines of CSS. Of course, it always takes more than that, but not much. I mean this is really the meat of the deal:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(3, auto);
}
```

#### What an amazing time to be a web developer. Anyway, I hope you enjoy this "feature" that you'll probably never notice or even see. Maybe that's the best part of a good user interface – the hidden stuff that just works.

[^1]: The original article cited here is now updated and maintained by the staff over at CSS-Tricks. Bookmark their version if you want to dive in and learn about CSS Grid: [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
