---
title: "Building a Scalable Design System: Integrating Multiple Products"
date: 2025-07-30T23:45:49-06:00
draft: false
tags: ["Design Systems", "Design Ops"]
categories: ["blog"]
---

### Problem: Multiple Products, One System

 The current design system I was working on had been created for a single product and we now needed to update the design system to support more products. Expanding it required rethinking how we could serve multiple brands under one umbrella. The new design system would have to allow unique guidance, components, and design resources for multiple products without overwhelming users with unnecessary complexity.

## The Solution: A Theming Approach to Product Diversity

To solve this challenge, we implemented a theming solution. Theming allows the design system to be flexible and adaptable, providing a seamless experience for users across different products. Here’s how it works:

- **Product-Specific Views**: Users can toggle between different products within the system, switching the theme to match the selected product. Components for that brand could be seen when selected. Selecting the see all option would show all components from every product.
  
- **Consistent Experience Across Products**: While each product has its own unique branding and design elements, the underlying structure of the design system remains consistent. This means that whether a designer is working on Product A or Product B, they are using the same core system components, ensuring a cohesive experience across all products.

- **Token structure** Having a token library helps create a single source of truth for colors and styles. Having consistent naming for each product ensure the token switching remains consistent. 

This theming solution allowed us to maintain a unified design system that could serve multiple products while respecting each product's individual branding requirements.

---

Note: Below is an example of the solution we implemented where the theme of the component can be changed depending on the option selected. This example was generated using Claude and added to CodePen.

 {{< codepen user="babsdenney" id="EaVmzgd" height="600" >}}

## Key Benefits of the Theming Solution

- **Scalability**: The theming approach made the design system more scalable, enabling us to easily add new products in the future without overhauling the entire system.
  
- **Consistency**: By standardizing the underlying components and guidelines, we ensured that all products maintained a consistent user experience, even as their visual identities varied.

- **Efficiency**: Designers and developers could focus on building and maintaining one design system rather than creating separate systems for each product, saving time and reducing complexity.

## Conclusion

Expanding a design system to support multiple products presents unique challenges, but it also offers opportunities for increased efficiency, consistency, and scalability. By implementing a theming solution, we were able to adapt our design system to meet the needs of multiple products while preserving the integrity of the overall system. This approach not only streamlined our workflow but also provided a flexible, scalable foundation for future growth. As we continue to expand and refine the system, we are confident that this theming solution will remain a key component of our design system’s success.

---

Note: This article was co-written with the help of AI to improve clarity and structure.