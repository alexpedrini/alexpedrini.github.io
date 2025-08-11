---
title: "Discover my Research"
layout: splash
permalink: /research/
header:
  overlay_image: /assets/images/ngc628_NIRCAM.jpg  # full-width background image
  overlay_filter: 0.4 # darkens the background so text is readable
  overlay_color: "#000"
  caption: "Credit: ESA/Webb, NASA & CSA, A. Adamo (Stockholm University) and the FEAST JWST team"
excerpt: "I'm a member of the FEAST (Feedback in Emerging extragAlactic Star clusTers) program, studying star formation and stellar feedback in nearby galaxies."
intro: 
  - excerpt: >
      My research is embedded within the **[FEAST](https://feast-survey.github.io)** program, 
      which investigates how stellar feedback from massive stars shapes the surrounding 
      interstellar medium and influences galaxy evolution. I focus on the morphological 
      and physical characterization of star-forming regions in nearby galaxies, combining 
      observations from the **James Webb Space Telescope** and other facilities. 
feature_row:
  - image_path: /assets/images/galaxies.jpg
    alt: "FEAST"
    title: "FEAST galaxies"
    #excerpt: "Identifying and mapping ionized gas (HII regions) and photodissociation regions (PDRs) in nearby galaxies to trace the influence of massive stars."
    #url: "#hii-pdrs"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/paper1_screen.jpg
    alt: "HII regions and PDRs"
    title: "Mapping HII Regions and PDRs in NGC 628"
    excerpt: "Identifying and mapping ionized gas (HII regions) and photodissociation regions (PDRs) in nearby galaxies to trace the influence of massive stars."
    url: "#hii-pdrs"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/M83_clusters.png
    alt: "Star Clusters"
    title: "Star Cluster Identification"
    excerpt: "Detecting and classifying young star clusters using multi-band imaging to study their ages, masses, and environments."
    url: "#star-clusters"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/934_best_model.pdf
    alt: "SED fitting"
    title: "Spectral Energy Distribution Fitting"
    excerpt: "Deriving physical properties of star clusters and star-forming regions from UV to infrared data using SED fitting techniques."
    url: "#sed-fitting"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/slug.png
    alt: "SLUG modelling"
    title: "SLUG Modelling"
    excerpt: "Using SLUG (Stochastically Lighting Up Galaxies) to simulate stellar populations and interpret cluster properties."
    url: "#slug"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
## The FEAST Program

![FEAST Logo](/assets/images/logoFEASTvec.svg){: .align-right width="200px"}

My research is embedded within the FEAST project, a James Webb Space Telescope Cycle 1 program (PI Angela Adamo) that aims to understand how stellar feedback from massive stars shapes the surrounding interstellar medium and influences galaxy evolution. To achieve this, we have observed six galaxies within 10 Mpc: the well-studied M51, M83, NGC 628, NGC 4449, NGC 4490, and NGC 4495. These galaxies feature rich catalogs of archival observations collected from the largest ground- and space-based telescopes.
In my research, I focus on the morphological and physical characterization of star-forming regions and emerging young star clusters in these galaxies, seeking to uncover the emergence phase of star formation and its impact across galactic scales.

[Explore FEAST](https://feast-survey.github.io){: .btn .btn--primary}

---

## Mapping HII Regions and PDRs {#hii-pdrs}
<div style="float:left; margin-right:20px; width:400px;">
  <img src="/assets/images/paper1_screen.jpg" alt="Example Map" style="width:100%;">
</div>

With the **James Webb Space Telescope**, we can now identify HII regions and photodissociation regions (PDRs) at resolutions of just a few parsecs in nearby galaxies. These regions are direct products of stellar feedback from emerging young star clusters. In the near-infrared, HII regions are traced by hydrogen recombination lines (e.g., Pa&alpha; at 1.87 &mu;m). PDRs are colder and denser, where molecules such as polycyclic aromatic hydrocarbons (PAHs) can survive; these are observable at 3.3 &mu;m with JWST/NIRCam and 7.7&mu;m with JWST/MIRI.
I have developed a methodology to identify these regions and studied how PAHs are destroyed in intense stellar environments. You can find the corresponding paper **[here](https://iopscience.iop.org/article/10.3847/1538-4357/ad534d)**, where I am the corresponding author.
The figure, taken from this paper, shows a star-forming complex with HII regions marked by orange contours and PDRs in white.


<div style="clear:both;"></div>

---

## Identification of emerging young star clusters {#star-clusters}
<div style="float:right; margin-left:20px; width:400px;">
  <img src="/assets/images/M83_clusters.png" alt="Star Cluster Zoom" style="width:100%;">
</div>

Within the FEAST team, we have developed a pipeline to identify and extract emerging young star clusters across our sample of galaxies. These clusters are selected to be bright and compact in Pa&alpha; and in the 3.3 &mu;m PAH emission, and are classified as eYSCI. Sources that show bright and compact Pa&alpha; emission but lack a compact PAH counterpart are classified as eYSCII. In FEAST, we are also studying a particular group of sources that display compact PAH emission without a corresponding Pa&alpha; detection.
The identification process is followed by multiple visual inspections, which ultimately result in the production of various catalogs. I am an active member of the catalog production effort for the FEAST team.
In the figure, we show the young cluster population in M83 from the **[paper](https://arxiv.org/abs/2505.08874)** led by Alice Knutas, for which I am the third author. Here, we additionally show in cyan the population of optical young star clusters, identified using archival images from the Hubble Space Telescope.

<div style="clear:both;"></div>

---

## Spectral Energy Distribution Fitting {#sed-fitting}
<div style="float:left; margin-right:20px; width:400px;">
  <img src="/assets/images/934_best_model.pdf" alt="SED Plot" style="width:100%;">
</div>

I apply **SED fitting** to multi-wavelength photometry (UV to IR) to estimate ages, masses, and extinctions of clusters and regions. 
This is crucial for reconstructing the star formation history.

<div style="clear:both;"></div>

---

## SLUG Modelling {#slug}
<div style="float:right; margin-left:20px; width:400px;">
  <img src="/assets/images/slug.png" alt="SLUG Schematic" style="width:100%;">
</div>

I use **SLUG** simulations to model stochastic effects in stellar populations, compare them to observations, and understand cluster evolution.

<div style="clear:both;"></div>
