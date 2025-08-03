---
title: "Using AI to Prototype Tab Components"
date: 2025-07-30T23:45:49-06:00
draft: false
tags: ["#Design Systems", "Design Ops", "Prototyping", "Interaction design"]
categories: ["blog"]
---

## The Challenge of Tabs

When our team took on the task of designing a tab component, we knew it would be more complicated than it seemed. Tabs are deceptively simple, but under the surface they come with complex usability and accessibility considerations.

Some of the questions we had to solve:
- What happens when tabs exceed the width of the screen?
- Should tabs work with in-page navigation or update the URL?
- How do we support users at 400% zoom or on screens narrower than 320px?

## Exploring Overflow Solutions

We considered three possible patterns:
1. **Stacked Tabs** – overflow creates a second row.
2. **Horizontal Scroll** – tabs slide side-to-side.
3. **Dropdown Menu** – excess tabs move into a select-style list.

Each option had trade-offs depending on content density, accessibility, and implementation constraints.

## Enter AI-Assisted Prototyping

Rather than mock each version in Figma, I turned to ChatGPT to prototype them directly in code. I described the desired behavior, and it returned HTML, CSS, and JavaScript that I pasted into CodePen.

It wasn’t entirely hands-free—I still had to style and refine the code—but the AI-generated base saved hours of work. The end result was:
- A working prototype I could test at different screen sizes
- Real code I could hand off to developers
- A shareable demo for async feedback from the team

## Why It Worked

Some components are better tested in code than in static mockups. Tabs are one of them. This process made the handoff smoother and the design decisions clearer.

Using AI to assist in prototyping helped me move from idea to interaction quickly. It also made me rethink when and where we prototype: in Figma or in the browser.

---

*Note: This article was co-written with the help of AI to improve clarity and structure.*
