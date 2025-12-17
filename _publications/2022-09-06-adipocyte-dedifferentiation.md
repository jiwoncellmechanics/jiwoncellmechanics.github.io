---
layout: single
author_profile: false
read_time: true
share: false
comments: false
title: "Close-up: When a Fat Cell Spits Out Its Fat Pocket and Becomes a Stem Cell"
date: 2022-09-06
tags: [Microfluidics, Ceiling Culture, Live-cell Imaging, Adipocyte, Adipocyte Dedifferentiation, Lipid Droplet, Actin, PPARg]
classes: wide
header:
  teaser: /assets/image147.gif
---

Kim, J., Park, K. Y., Choi, S., Ko, U. H., Lim, D. S., Suh, J. M., & Shin, J. H. (2022). [**Ceiling culture chip reveals dynamic lipid droplet transport during adipocyte dedifferentiation via actin remodeling.**](https://pubs.rsc.org/en/content/articlelanding/2022/lc/d2lc00428c) *Lab on a Chip, 22*(20), 3920-3932.


<div style="text-align:center; margin:1.5rem 0;">
  <a href="https://pubs.rsc.org/en/content/articlelanding/2022/lc/d2lc00428c"
     target="_blank"
     style="
       display:inline-block;
       padding:0.8rem 1.6rem;
       border:2px solid #1f2933;
       background-color:#f9fafb;
       border-radius:8px;
       text-decoration:none;
       font-weight:700;
       letter-spacing:0.02em;
       color:#1f2933;
     ">
    📄 View Publication
  </a>
</div>


It was once believed that fat cells (adipocytes) were *terminally* differentiated.
The term *terminal* implies that the form and function of the cells are fixed forever and cannot be reversed into a state with greater potentials (stemness).

<div style="text-align:center;">
  <img src="/assets/adipocyte_wiki.jpg" width="400">
  <p style="font-size:0.85rem; color:#777; margin-top:0.5rem;">
   Fat cells look like bubbles, filled with fat.
   Image from Wikipedia.
  </p>
</div>

However, recent studies have revealed that adipocytes can be reversed into stem cells under certain conditions. Dedifferentiated adipocytes (DFATs) can differentiate into bone cells, cartilage cells, muscle cells, and blood vessel cells: **_Someday, you might replace broken part of your body with your excess fat!_**

But nobody has witnessed how a fat cell spits out its fat pocket and becomes a stem cell, mainly because of following two reasons:

(1) Once an adipocyte discharges its lipid droplet, it just looks like a fibroblast. You can't tell if it's a dedifferentiated adipocytes or a fibroblast.
Our team resolved this issue using *Adipoq-Cre; mT/mG* system. Long story short, a cell that has a history of being an adipocytes expresses **<span style="color:green;">green</span>** fluorescences while all the other cells are **<span style="color:red;">red.</span>**

(2) Adipocytes have low specific gravity, so they float on the cell culture medium. However if they stay floating, they soon die (tricky ones!). Sugihara came up with *ceiling culture* method (1986), where the culture flask is completely filled with medium so that the adipocytes can attach and grow on the ceiling surface.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 1rem;">
  <div style="text-align:center; flex:1;">
    <img src="/assets/image48.png" width="150">
    <p style="font-size:0.8rem; color:#777;">Floating adipocytes (white layer) on the culture media.</p>
  </div>
  <div style="text-align:center; flex:1;">
    <img src="/assets/image52.png" width="250">
    <p style="font-size:0.8rem; color:#777;">Ceiling culture (Sugihara, H., <em>Differentiation</em> (1986))</p>
  </div>
</div>


The ceiling culture method is a clever solution. Unfortunately, standard culture flasks are too big to fit within the working distances of high-magnification objectives and are also rather wasteful.

**_How about using microfluidic chips?_**
In a simple single-layered microfluidic channel, adipocytes were swept away, making it challenging to observe the dedifferentiation processes.

<div style="text-align:center;">
  <img src="/assets/image61.gif" width="300">
  <p style="font-size:0.8rem; color:#777;">Yes, the floating globules are the adipocytes.</p>
</div>

Our innovation was to make the microfluidic chip **two-layered**. This staightforward design efficiently trapped floating adipocytes. Now we have an imaging-freindly (transparent and only 200 μm high), cost-effective (10 μl volume), and tunable (via ECM coating) platform.

With our chip (which we named *ceiling culuture chip*), we explored different ECM conditions, and molecular interventions. Interestingly, we found that conditions promoting adipocyte differentiation inhibit adipocyte **de**differentiation, and *vice versa.*


<div style="display: flex; justify-content: center; align-items: flex-start; gap: 1rem;">
  <div style="text-align:center; flex:1;">
    <img src="/assets/ceilingculturechipillustration.png" width="300">
    <p style="font-size:0.8rem; color:#777;">Ceiling Culture Chip</p>
  </div>
  <div style="text-align:center; flex:1;">
    <img src="/assets/celltrap.png" width="300">
    <p style="font-size:0.8rem; color:#777;">Floating adipocytes remain stably trapped in position.</p>
  </div>
</div>


