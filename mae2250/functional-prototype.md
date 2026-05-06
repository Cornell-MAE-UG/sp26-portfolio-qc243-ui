---
layout: default
title: Functional Prototype
permalink: /projects/mae2250/functional-prototype/
nav_exclude: true
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
  margin-top: 2rem;
}

h3 {
  color: #4d7c4f;
}

h4 {
  color: #5b8c5a;
}

strong {
  color: #355e3b;
}

ul li {
  margin-bottom: 0.5rem;
}

hr {
  border: none;
  height: 1px;
  background: #d7e5d2;
  margin: 2rem 0;
}

a {
  color: #3f6f45;
}

a:hover {
  color: #27452c;
}

img {
  width: 100%;
  max-width: 500px;
  height: auto;
  border-radius: 12px;
  display: block;
  margin: 1.5rem auto;
  box-shadow: 0 3px 10px rgba(0,0,0,0.12);
}

.image-row {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  flex-wrap: wrap;
  margin: 2rem 0;
}

.image-row img {
  width: 45%;
  min-width: 280px;
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
  <h1>Functional Prototype</h1>
  <p>
    Mechanical trapping system for capturing and containing spotted lantern flies during vineyard harvest.
  </p>
</div>

<div class="section-card" markdown="1">

## Overview

The functional prototype demonstrates a mechanical trapping system designed to capture and contain spotted lantern flies (SLFs) during vineyard harvest.

The system integrates four main subsystems:
- Container
- Drawer
- Funnel mechanism
- Extendable pole

</div>

<div class="section-card" markdown="1">

## Prototype Design

### CAD Models

<div class="image-row">
  <img src="/assets/images/slf-initial-cad.png">
  <img src="/assets/images/slf-initial-section-analysis.jpg">

</div>

</div>

<div class="section-card" markdown="1">

## Subsystem Breakdown

### Container

- **Function:** Outer housing for funnel and drawer  
- **Material:** Wood (Taylor Design Studio)  
- **Fabrication:** Cut using bandsaw and assembled using adhesive  

### Drawer

- **Function:** Stores captured SLFs and liquid attractant  
- **Material:** Wood + CA glue  

#### Fabrication
- Built box structure  
- Added internal rails for sliding  
- Designed for easy insertion/removal  

### Funnel Mechanism

<img src="/assets/images/slf-funnel-sketch.png" alt="Funnel Sketch">

- **Function:** One-way entry system preventing escape  
- **Materials:** Wire ring, wood flaps, rubber bands/string  

#### Fabrication
- Cut wooden flaps using bandsaw  
- Added notches for string/rubber band  
- Drilled holes for mounting  
- Bent wire into ring and attached flaps using zip ties  

### Extendable Pole

<img src="/assets/images/slf-system-sketch.jpg" alt="Pole Sketch">

- **Function:** Adjustable mounting system for height positioning  
- **Material:** Wood + cylindrical rods  

#### Fabrication
- Created telescoping horseshoe-shaped structure  
- Drilled holes every 2 inches  
- Used pin system for height locking  

</div>

<div class="section-card" markdown="1">
## McMaster Components (Future Iteration)

| Part Name | SKU | Price Per Unit | Units Desired |
|---|---|---|---|
| Spring Variety Pack | 98596A790 | $11.44 | 1 |
| Mini Drawer Slides | 3351N12 | $32.36 | 1 |
| 4 ft Aluminum U Channel | 9001K685 | $8.17 | 1 |
| Aluminum L Stock | 8982K96 | $2.40 | 16 |
| Aluminum 6061 Plates | 89015K171 | $6.39 | 2 |
| Pins for U Channel | 98381A047 | $3.33 | 2 |

</div>

<div class="section-card" markdown="1">

## Testing Plan

### Container
- Structural stability under ~10 mph wind load  
- No rotation, deformation, or displacement  

### Drawer
- Supports 12 kg load  
- Smooth operation without jamming  
- Survives 50 open/close cycles  

### Funnel
- Flaps meet within 1–3 cm  
- Allows entry but prevents escape  
- Adjustable tension using string/rubber band  

### Extendable Pole
- Adjustable without slipping  
- Withstands 50 adjustment cycles  
- Supports full system load (~14.25 kg)  

</div>

<div class="section-card" markdown="1">

## Testing Results

### Drawer Performance
- Successfully held 6 kg load  
- Smooth motion over 15 cycles  
- No visible damage observed  
- Handle design requires improvement  

### Funnel Performance

Successful:
- SLF model entered easily
- Escape prevented under correct alignment

Failure cases:
- Improper flap spacing
- Twisted flaps
- String interference

### Extendable Pole
- Successfully adjusted 50 times
- Stable under load
- No visible deformation  

</div>

<div class="section-card" markdown="1">

## Key Design Insights

- Funnel performance is highly sensitive to flap alignment  
- Drawer mechanism is reliable but ergonomics need refinement  
- Pole system is structurally sound and requires minimal redesign  

## Design Improvements (Next Iteration)

- Add spacers to maintain flap alignment  
- Introduce multiple flap attachment points  
- Limit flap overextension using secondary ring  
- Make flap length adjustable  
- Reduce flap thickness  
- Explore octagonal funnel geometry for improved sealing  

</div>

<div class="section-card" markdown="1">


## Success Criteria

The prototype is considered successful if:

- Drawer supports 12 kg without failure  
- Drawer operates smoothly for 50 cycles  
- Pole adjusts reliably without slipping  
- Funnel consistently allows entry but prevents escape  
- Flaps maintain controlled range of motion  

</div>

[← Back to Project Overview]({{ '/projects/mae2250/' | relative_url }})