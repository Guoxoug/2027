---
layout: distill
title: "A Minimal ICLR 2027 Blogpost Title"
description: "A short two-sentence abstract belongs here. It should summarize the post in plain text, without mathematics or hyperlinks, to mirror the website description field."
date: 2027-04-30
future: true
htmlwidgets: true
authors:
  - name: Anonymous
bibliography: 2027-04-30-anonymous-blogpost.bib
toc:
  - name: "A First-Level Heading"
    subsections:
      - name: "A Second-Level Heading"
  - name: "Figures and Interactive Elements"
---
## A First-Level Heading

This is minimal placeholder text showing the body typography and paragraph rhythm. Inline mathematics such as $p(y\mid x)$ should sit naturally on the baseline, and a numerical citation can appear at the end of a sentence <d-cite key="gregor2015draw"></d-cite>.

A second paragraph demonstrates the spacing between blocks of prose. Replace all dummy text with the blogpost after settling its structure; this file intentionally contains no substantive submission content.

### A Second-Level Heading

Displayed mathematics uses ordinary LaTeX environments:

$$\left(\sum_{k=1}^{n} a_k b_k\right)^2
  \leq
  \left(\sum_{k=1}^{n} a_k^2\right)
  \left(\sum_{k=1}^{n} b_k^2\right).$$

#### A third-level heading

The third level is compact and uppercase, matching the website hierarchy. Standard LaTeX lists remain available when needed:

- a short placeholder item;

- another short placeholder item.

## Figures and Interactive Elements

{% include figure.liquid path="assets/img/2027-04-30-anonymous-blogpost/example-image.svg" class="img-fluid" %}
<div class="caption">A minimal static-image example. Replace the bundled placeholder with an image stored alongside the manuscript.</div>

Figure 1 demonstrates a cross-reference and the subdued caption style used by the Distill layout.

<div class="l-page">
  <iframe
    src="{{ 'assets/html/2027-04-30-anonymous-blogpost/widget-title.html' | relative_url }}"
    title="Widget title"
    loading="lazy"
    style="width: 100%; height: 360px; border: 0;"
  ></iframe>
</div>
<div class="caption">Interactive widget placeholder. In the website version, replace this box with an HTML include or iframe and record the intended asset path here.</div>
