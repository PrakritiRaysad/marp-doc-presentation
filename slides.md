---
marp: true
paginate: true
headingDivider: 2
theme: custom-theme
class: lead
---

<!-- Custom Theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

section h1 {
  color: #1e88e5;
}

section p {
  font-size: 1.1rem;
}

/* Page number styling */
footer {
  font-size: 0.8rem;
  color: #777;
}

/* Background image slide */
.bg-slide {
  background-image: url('https://source.unsplash.com/1600x900/?technology');
  background-size: cover;
  color: white;
  text-shadow: 1px 1px 4px black;
}
</style>

<!-- Custom Theme Registration -->
<style>
@import 'https://unpkg.com/@marp-team/marp-core/themes/default.css';

:root {
  --primary-color: #1e88e5;
  --accent-color: #1565c0;
  --text-color: #333;
}
</style>

# Product Documentation Presentation  
### **Technical Writer: 24f2006582@ds.study.iitm.ac.in**

---

## Overview

- Version-controlled documentation  
- Easily exportable (PDF, PPTX, HTML)  
- Marp-based workflow  
- Theming + custom styles  
- Background imagery  
- Math support  

---

## Algorithmic Complexity Example (Math)

Using Marp's KaTeX support:

\[
T(n) = 4T\left(\frac{n}{2}\right) + n^2
\]

By Master Theorem:

\[
T(n) = \Theta(n^2)
\]

---

## Slide with Background Image

<!-- _class: bg-slide -->
# Documentation Pipeline  
### Git → Markdown → Marp → Outputs

---

## Key Features in This Documentation

- Custom theme  
- Page numbers  
- Background image  
- Math support  
- Modular Markdown structure  
- Version-controlled for CI/CD  

---

## Thank You

For issues or contributions:

**Email:** 24f2006582@ds.study.iitm.ac.in  
