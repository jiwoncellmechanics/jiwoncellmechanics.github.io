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
<div style="
  border:1px solid #e5e7eb;
  border-radius:8px;
  padding:1.2rem 1.5rem;
  margin:2rem 0;
  background:#fafafa;
">
  <p style="margin-top:0;">
    <strong>Kim, J.</strong>, et al. (2022).  
    <em>Ceiling culture chip reveals dynamic lipid droplet transport during adipocyte dedifferentiation via actin remodeling.</em>  
    <br>
    <span style="color:#555;">Lab on a Chip</span>
  </p>

  <div style="margin-top:1rem; text-align:center;">
    <a href="https://pubs.rsc.org/en/content/articlelanding/2022/lc/d2lc00428c"
       target="_blank"
       style="
         display:inline-block;
         padding:0.6rem 1.2rem;
         border:2px solid #333;
         border-radius:6px;
         text-decoration:none;
         font-weight:600;
         color:#333;
       ">
      Read the Paper →
    </a>
  </div>
</div>



It was once believed that fat cells (adipocytes) were *terminally* differentiated.
The term *terminal* implies that the form and function of the cells are fixed forever and cannot be reversed into a state with greater potentials (stemness).
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


