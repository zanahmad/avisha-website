---
title: "Computational Modelling"
subtitle: "Investigating focused ultrasound wave propagation in patient-specific spinal cord anatomy"
excerpt: "Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites."
date: 2023-04-01
author: ""
featured: true
draft: false
tags:
- hugo-site
categories:

# layout options: single or single-sidebar
layout: single-sidebar
links:
- icon: door-open
  icon_pack: fas
  name: paper
  url: https://ieeexplore.ieee.org/abstract/document/10123718
- icon: door-open
  icon_pack: fas
  name: paper
  url: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12466/1246615/Computational-modeling-towards-focused-ultrasound-therapy-for-spinal-cord-injury/10.1117/12.2654357.short#_=_
---

### Generating acoustic phantoms of patient-specific spinal cords to investigate the theraputic efficacy of focused ultrasound transducer placement 


---

Spinal cord injury is a devastatingAn estimated 900,000 incident cases of spinal cord injury (SCI) were reported globally in 2019, predominantly resulting from falls, road injuries, and conflicts [1]. The clinical manifestations of SCI can worsen with secondary damage due to inflammation and swelling restricting blood flow to the cord, with devastating socioeconomic consequences for patients [2]. Surgical decompression techniques do not guarantee sufficient local blood flow restoration and other methods to increase tissue perfusion, like prolonged blood pressure elevation, can lead to negative downstream effects [2, 3].

The spinal cord is an acoustically heterogeneous medium, with each anatomy (i.e. dura, pia, cerebrospinal fluid, spinal cord) having varying acousitc properties (i.e., speed of sound, density, acoustic nonlinearity). Therefore, understanding focused ultrasound wave propagation through requires computational simulations. By using imaging processing pipelines, we can convert spinal cord images from patients into computational grids in numerical solvers. This



{{< figure src="css-grid-cover.png" alt="Traditional right sidebar layout" caption="A visual example of the traditional right sidebar layout" >}}

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
