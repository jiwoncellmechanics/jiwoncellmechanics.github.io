---
layout: single
author_profile: false
read_time: true
share: false
comments: false
title: "Close-up: When a fat cell spits out its fat pocket and becomes a stem cell"
date: 2022-09-06
tags: [Microfluidics, Ceiling Culture, Live-cell Imaging, Adipocyte, Adipocyte Dedifferentiation, Lipid Droplet, Actin, PPARg]
classes: wide
header:
  teaser: /assets/image147.gif
---
<style>
.pub-btn {
  display:inline-block;
  padding:0.6rem 1.2rem;
  border:2px solid #333;
  border-radius:6px;
  text-decoration:none;
  font-weight:600;
  color:#333;
  background:#fafafa;
  transition: background-color 0.2s ease,
              color 0.2s ease,
              transform 0.15s ease;
}

.pub-btn:hover {
  background:#e5e7eb;
  color:#111;
  transform: none;
}
</style>


<div style="
  border:1px solid #e5e7eb;
  border-radius:8px;
  padding:1.2rem 1.5rem;
  margin:2rem 0;
  background:#fafafa;
">
  <p style="margin-top:0;">
    <u>Kim , J.</u>, Park, K. Y., Choi, S., Ko, U. H., Lim, D. S., Suh, J. M., & Shin, J. H. (2022).  
    Ceiling culture chip reveals dynamic lipid droplet transport during adipocyte dedifferentiation via actin remodeling.
    <em>Lab on a Chip, 22</em>(20), 3920-3932.
  </p>

<div style="margin-top:1rem; text-align:center;">
  <a class="pub-btn"
     href="https://pubs.rsc.org/en/content/articlelanding/2022/lc/d2lc00428c"
     target="_blank">
    Read the Paper →
  </a>
</div>
</div>

<div style="text-align:center;">
  <img src="/assets/waddington.jpg" width="300">
  <p style="font-size:0.8rem; color:#777;">Waddington’s epigenetic landscape. Nemec, S., Nature Reviews Materials (2021)</p>
</div>

#PREVIEW

It was once believed that fat cells (adipocytes) were *terminally* differentiated.
The term *terminal* implies that the form and function of the cells are fixed forever and cannot be reversed into a state with greater potentials (stemness).
However, recent studies have revealed that adipocytes can be reversed into stem cells under certain conditions. Dedifferentiated adipocytes (DFATs) can differentiate into bone cells, cartilage cells, muscle cells, and blood vessel cells: **_Someday, you might replace broken part of your body with your excess fat!_**

But nobody has witnessed how a fat cell expels its lipid droplet and becomes a stem cell, mainly for two reasons:

(1) Once an adipocyte discharges its lipid droplet, it just looks like a fibroblast. You can't tell if it's a dedifferentiated adipocytes or a fibroblast.
Our team resolved this issue using *Adipoq-Cre; mT/mG* system. Long story short, a cell with a history of being an adipocyte permanently expresses **<span style="color:green;">green</span>** fluorescences, while all the other cells remain **<span style="color:red;">red.</span>**

(2) Adipocytes have low specific gravity, so they float on the cell culture medium. However if they stay floating, they soon die, which makes them particularly challenging to culture. Sugihara came up with *ceiling culture* method (1986), where the culture flask is flipped and completely filled with medium so that the adipocytes can attach and grow on the surface.

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

To observe adipocyte behavior, we needed a system that could both immobilize floating adipocytes and fit under high-magnification objectives.

**_How about using microfluidic chips?_**

In a simple single-layered microfluidic channel, adipocytes were swept away, making it challenging to observe the dedifferentiation processes.

<div style="text-align:center;">
  <img src="/assets/image61.gif" width="300">
  <p style="font-size:0.8rem; color:#777;">Yes, the floating globules are the adipocytes.</p>
</div>

Our innovation was to make the microfluidic chip **two-layered**. This straightforward design efficiently trapped floating adipocytes. Now we have an imaging-friendly (transparent and only 200 μm high), cost-effective (10 μl volume), and tunable (via ECM coating) platform.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 1rem;">
  <div style="text-align:center; flex:1;">
    <div style="height:220px; display:flex; align-items:center; justify-content:center;">
      <img src="/assets/ceilingculturechipillustration.png"
           style="max-height:100%; max-width:100%; object-fit:contain;">
    </div>
    <p style="font-size:0.8rem; color:#777;">Ceiling Culture Chip</p>
  </div>

  <div style="text-align:center; flex:1;">
    <div style="height:220px; display:flex; align-items:center; justify-content:center;">
      <img src="/assets/celltrap.png"
           style="max-height:100%; max-width:100%; object-fit:contain;">
    </div>
    <p style="font-size:0.8rem; color:#777;">Floating adipocytes remain stably trapped in position.</p>
  </div>
</div>

With our chip (which we named *ceiling culture chip*), we explored different ECM conditions and molecular interventions. Interestingly, we found that conditions promoting adipocyte differentiation inhibit adipocyte **de**differentiation, and *vice versa.*

Furthermore, we could capture the dedifferentiating adipocytes undergo abrupt liposecretion.

<div style="text-align:center;">
  <img src="/assets/image147.gif" width="300">
  <p style="font-size:0.8rem; color:#777;">Ready and Pop!</p>
</div>

<div style="text-align:center;">
  <img src="/assets/image146.gif" width="300">
  <p style="font-size:0.8rem; color:#777;">Pop2</p>
</div>

A more quantitative version of "Ready and Pop" can be found in the paper.

Also, we could take a closer look at the actin structure (thanks to the thin channel structure) and figured out that the cells make *actin hole* through which they squeeze out the large lipid droplet, which once accounted for more than 90% of the cells' cytoplasm.

<div style="text-align:center;">
  <img src="/assets/actinhole.png" width="500">
  <p style="font-size:0.8rem; color:#777;">Actin hole (white arrowhead), prepared for liposecretion.</p>
</div>

One more interesting thing - we witnessed that the cells not only just secrete the lipid droplet, but also *exchange* them. In many cases, the donor cell shrank and died shortly after the transfer. This might represent a strategy to preserve valuable nutrients by transferring them from an unhealthy cell to a healthier one.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 1rem;">
  <div style="text-align:center; flex:1;">
    <div style="height:220px; display:flex; align-items:center; justify-content:center;">
      <img src="/assets/coculture.png"
           style="max-height:100%; max-width:100%; object-fit:contain;">
    </div>
    <p style="font-size:0.8rem; color:#777;">Cell with green lipid droplet transfer its lipid content to another cell with red membrane.</p>
  </div>

  <div style="text-align:center; flex:1;">
    <div style="height:220px; display:flex; align-items:center; justify-content:center;">
      <img src="/assets/image155.gif"
           style="max-height:100%; max-width:100%; object-fit:contain;">
    </div>
    <p style="font-size:0.8rem; color:#777;">Lipid droplet transport could be unidirectional.</p>
  </div>
</div>

Lipid droplet transfer also could be bidirectional.
<div style="text-align:center;">
  <img src="/assets/image163.gif" width="300">
  <p style="font-size:0.8rem; color:#777;">Bidirectional lipid droplet transfer.</p>
</div>

Cells do all the fascinating work. But sometimes, simply observing those moments requires the assistance of Engineering. **Designing platforms for observing, maintaining, and manipulating the living cells is one of the core research theme I'm passionate about.** This work is one small example of how the right engineering can let cells tell their own stories. Stay tuned for more!
