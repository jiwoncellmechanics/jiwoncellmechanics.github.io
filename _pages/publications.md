---
layout: single
title: "Selected Publications"
permalink: /publications/
classes: wide
---


{% assign pubs = site.publications | sort: "date" | reverse %}

<ul class="pub-list">
  {% for post in pubs %}
  <li class="pub-item">
    <div class="pub-image">
      {% if post.header.teaser %}
        <img src="{{ post.header.teaser | relative_url }}">
      {% endif %}
    </div>

    <div class="pub-text">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </li>
  {% endfor %}
</ul>


<hr>


<h2>All Publications</h2>

**JOURNAL ARTICLES**
1.	Hyuntae Jeong, Jiwon Kim, Zhuoyang Lyu, and Ian Wong, “Partial EMT Drives Persistent Collective Migration that is Robust to Cell State Heterogeneity,” in preparation.
2.	Hyuntae Jeong, Pushkaraj Joshi, Jiwon Kim, Yinshi Hu, Ian Wong, and Jacob Rosenstein, “Label-Free All-Electrical Tracking of Individual and Collective Cell Migration using a Megapixel CMOS Capacitance Sensor,” in preparation.
3.	Lily A. Cordner, Hyuntae Jeong, Jiwon Kim, Paul Cao, Vera Fonseca, Alper Uzun, Ece D. Gamsiz Uzun, Shyamala Maheswaran, Blanche C. Ip, and Ian Y. Wong, “Adhesion of Patient-Derived Circulating Tumor Cells to Decellularized Matrix Activates Intermediate Early and Metallothionein Gene Expression Associated with Metastatic Colonization,” in preparation.
4.	Jiwon Kim, Hyuntae Jeong, Carles Falcó, Alex M. Hruska, W. Duncan Martinson, Alejandro Marzoratti, Mauricio Araiza, Haiqian Yang, Vera C. Fonseca, Stephen A. Adam, Christian Franck, José A. Carrillo, Ming Guo, and Ian Y. Wong, “Collective Transitions from Orbiting to Matrix Invasion in 3D Multicellular Spheroids,” Nature Physics, 22, 275-286, 2026.
5.	Camille Rodriguez, Hyuntae Jeong, Jiwon Kim, Lily A. Cordner, Paul Cao, Suganya Sivagurunathan, Stephen A. Adam, Robert D. Goldman, Ian Y. Wong, Ming Guo, “Expression of vimentin intermediate filaments in epithelial cells promotes cell migration and cell-matrix interaction in 3D”, Biophysical Journal, 125, 4, 1185-1193, 2026.
6.	Jiwon Kim, Hyuntae Jeong, Chanhong Min, and Jennifer H. Shin, “Collective Mechanical Memory Encoded by Long-Lasting Supracellular Cytoskeletal Structures in Multicellular Spheroids,” ACS Applied Materials and Interfaces, 17, 46, 63089–63102, 2025
7.	Jiwon Kim§, Kun-Young Park§, Sungwoo Choi, Unghyun Ko, Dae-Sik Lim, Jae Myoung Suh, and Jennifer H. Shin, “Ceiling culture chip reveals dynamic lipid droplet transport during adipocyte dedifferentiation via actin remodeling,” Lab on a Chip, 22, 3920-3932, 2022 (§ Equal contribution).
8.	Youngbin Cho, Seung Jung Yu, Jiwon Kim, Ung Hyun Ko, Eun Young Park, Jin Seung Choung, Goro Choi, Daehyun Kim, Eunjung Lee, Sung Gap Im, and Jennifer H. Shin, “Remodeling of Adhesion Network within Cancer Spheroids via Cell-Polymer Interaction,” ACS Biomaterials Science & Engineering, 6, 10, 5632-5644, 2020.
9.	Jin-sung Park, Geunseob Oh, Jiwon Kim, Eun Young Park, and Jennifer H. Shin, “Reversible Thermal Gradient Device to Control Biased Thermotactic Response of C. elegans,” Analytical Sciences, 35, 12, 1367-1373, 2019.

**BOOK CHAPTERS**
1.	Lily A. Cordner, Alexxa C. Cruz-Bonilla, Hyeontae Jeong, Jiwon Kim, Anh Hoang Vu, Ian Y. Wong, “Profiling Collective and Individual Cell Migration Using Biomaterial and Microfluidic Technologies,” in Microfluidic Technologies for Cell Analysis and Beyond, CRC Press, 2026.

<hr>
