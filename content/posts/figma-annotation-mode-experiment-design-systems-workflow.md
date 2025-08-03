---
title: "Experimenting with Annotation Mode in Figma"
date: 2025-07-30T23:45:49-06:00
draft: false
tags: ["#Design Systems", "Design Ops"]
categories: ["blog"]
---

## Background

Our design team recently began exploring a new way to annotate designs directly in Figma. While searching for examples of this technique online, we came up short—which made us wonder if other teams were thinking about this the same way we were.

Figma already supports switching between properties using **modes**—great for themes like light/dark mode or responsive layouts. We started asking: could we use this same functionality to annotate?

## The Problem with Static Spacing Annotations

In our current setup, we use custom spacing components to indicate padding and margin between UI elements. These are overlaid manually on top of mockups and toggled on or off as needed.

But here’s the catch: as soon as you change the layout, those overlays become inaccurate. That means manually fixing annotations every time the design changes.

## The Experiment

We tried something different. What if we embedded the spacing annotations directly into the mockups and used **modes** to toggle their visibility?

This way, we could:
- Edit spacing and layout without breaking the annotations
- Include other toggled visibility helpers (like spec labels, dev notes)
- Keep a clean default view for design reviews

It’s still a work in progress, but so far it’s proving to be a lightweight and flexible alternative to traditional annotation overlays.

## Open Question

We’re curious: is this something other design systems teams are doing? If you’ve explored annotation workflows in Figma, we’d love to hear how you’re handling it.

---

*Note: This article was co-written with the help of AI to improve clarity and structure.*
