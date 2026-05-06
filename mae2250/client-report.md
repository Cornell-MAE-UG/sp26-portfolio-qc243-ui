---
layout: default
title: Client Report
permalink: /projects/mae2250/client-report/
parent: mae2250
---

<style>
body,
.hero,
.section-card,
h1,
h2,
h3,
h4,
h5,
h6,
p,
li,
a,
table {
  font-family: "Times New Roman", Times, serif;
}

.wrapper,
.main-content,
.page-content {
  max-width: 1000px;
  margin: 0 auto;
  padding: 2rem;
}

body {
  background-color: #f4f6f2;
  line-height: 1.7;
}

.hero {
  background: linear-gradient(135deg, #355e3b, #7ea172);
  color: white;
  padding: 4rem 2rem;
  border-radius: 18px;
  margin-bottom: 2rem;
  text-align: center;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
}

.hero h1 {
  margin-bottom: 0.5rem;
  font-size: 3rem;
}

.hero p {
  font-size: 1.15rem;
}

.section-card {
  background: #f8faf7;
  border-left: 6px solid #5b8c5a;
  padding: 2rem;
  margin: 2rem 0;
  border-radius: 14px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
}

h2 {
  color: #355e3b;
  margin-top: 1rem;
  border-bottom: 2px solid #d7e5d2;
  padding-bottom: 0.3rem;
}

h3 {
  color: #4d7c4f;
}

h4 {
  color: #6d8f68;
}

strong {
  color: #355e3b;
}

ul li {
  margin-bottom: 0.5rem;
}

a {
  color: #3f6f45;
}

a:hover {
  color: #27452c;
}

img {
  width: 100%;
  max-width: 450px;
  height: auto;
  object-fit: contain;
  border-radius: 12px;
  display: block;
  margin: 1.5rem auto;
  box-shadow: 0 3px 10px rgba(0,0,0,0.12);
  background: white;
  padding: 0.5rem;
}

.image-row {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  margin: 2rem 0;
}

.image-row img {
  flex: 1 1 400px;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1rem;
}

table th {
  background-color: #5b8c5a;
  color: white;
  padding: 0.75rem;
}

table td {
  padding: 0.75rem;
  border: 1px solid #d7e5d2;
}

table tr:nth-child(even) {
  background-color: #eef4ea;
}
</style>

<div class="hero">
  <h1>Client Report</h1>
  <p>
    Final design summary and prototype evaluation for the Spotted Lantern Fly Trap project.
  </p>
</div>

<div class="section-card" markdown="1">

## Project Overview

**Team:** Team 003  
**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape  

### Team Members
- Lydia Woodall  
- Ben Sedran  
- Charlotte Huber  
- Esmeralda Bernal Martinez  
- Lisa Chen  

</div>

<div class="section-card" markdown="1">

## Problem Context

Spotted lantern fly (SLF) infestations pose a major threat to vineyards across the United States, causing up to **$8.8 million in damages over three years** due to:

- Vine damage  
- Reduced fruit quality  
- Product contamination  

Even small numbers of SLFs can contaminate an entire harvest, leading to rejected product loads.

During harvest:
- Pesticide use is not viable
- Manual removal is impractical at scale

Currently, there is **no effective mechanical system** to draw SLFs away from vines and concentrate them into a controlled location during harvest.

</div>

<div class="section-card" markdown="1">

## Proposed Solution

We developed a **low-cost mechanical trap** designed to attract, capture, and contain SLFs away from grapevines during harvest.

### System Components

- **Funnel-Flap Entry System**  
  Allows SLFs to enter easily but prevents escape  

- **Container with Sliding Drawer**  
  Collects SLFs and stores attractant liquid  

- **Adjustable Pole**  
  Positions the trap at optimal height (6–9 ft)

SLFs are attracted using tree-of-heaven sap. Once inside, they pass through a funnel that opens under small force but closes to prevent escape.

</div>

<div class="section-card" markdown="1">

## Prototype

### CAD Design

<div class="image-row">
  <img src="/assets/images/slf-cad-funnel.png" alt="Funnel CAD">
  <img src="/assets/images/slf-cad-container.png" alt="Container CAD">
</div>

### Physical Prototype

<div class="image-row">
  <img src="/assets/images/slf-prototype1.jpg" alt="Funnel Prototype">
  <img src="/assets/images/slf-prototype2.png" alt="Assembled System">
</div>

</div>

<div class="section-card" markdown="1">

## How It Works

1. SLFs are attracted using natural sap  
2. They enter through the funnel-flap mechanism  
3. Flaps open under small force (~0.05 N)  
4. Flaps close behind them  
5. SLFs are collected in a removable drawer  

</div>

<div class="section-card" markdown="1">

## Testing & Results

### Stability Test
- Pole inserted ~1 ft into soil and shaken  
- System was unstable  
- Requires deeper anchoring  

### Drawer Load Test
- Loaded with 5.4 kg and cycled 10 times  
- Operated smoothly with no deformation  

### Funnel Performance Test
- Opens at ~0.05 N  
- Prevents escape once inside  

**Result:** Real SLFs likely cannot escape after entry.

</div>

<div class="section-card" markdown="1">

## Key Performance Metrics

- Funnel opening force: **~0.05 N**  
- Drawer capacity: **12 kg**  
- Total supported load: **~14.25 kg**  

</div>

<div class="section-card" markdown="1">

## Design Details

### Drawer
- Wheel-based sliding system  
- Easy removal  
- High load support  

### Funnel
- Octagonal one-way valve  
- Adjustable flaps  
- Rubber band restoring force  
- Hard stops prevent overextension  

### Container
- Laser-cut acrylic housing  
- Removable base for cleaning/refilling  

### Pole
- Telescoping steel rails  
- Adjustable height (6–9 ft)  

</div>

<div class="section-card" markdown="1">

## Cost Breakdown

| Component | Cost |
|---|---|
| Steel framing | $96.65 |
| Fasteners & hardware | $24.03 |
| Acrylic materials | $45.00 |
| Manufacturing | $78.40 |
| **Total** | **$294.65** |

</div>

<div class="section-card" markdown="1">

## Conclusion

The prototype successfully demonstrates a mechanically viable solution for SLF capture and containment.

### Key Outcomes
- Funnel effectively prevents escape  
- Drawer operates reliably under load  
- System functions as an integrated design  

</div>

<div class="section-card" markdown="1">

## Recommendations & Next Steps

To prepare for vineyard deployment:

- Improve pole stability  
- Add weather protection  
- Refine funnel alignment and durability  
- Reduce manual funnel adjustment  

With these improvements, the system could be scaled for practical vineyard use.

</div>

[← Back to Project Overview]({{ '/sp26-portfolio-qc243-ui/projects/mae2250/' | relative_url }})