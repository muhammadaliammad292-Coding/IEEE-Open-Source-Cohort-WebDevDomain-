# Day 06 — Box Model, Sizing & Spacing

**IEEE Open Source Cohort — Web Development Domain**  
**Student Name:** Muhammad Ali Ammad  
**Date:** October 20, 2026

---

## 📋 Task Statement
Today's task is focused on improving the overall layout, sizing, and spacing of our existing University / IEEE Society webpage using the CSS Box Model (`content`, `padding`, `border`, `margin`), enforce universal `box-sizing: border-box`, and implement clean box/card styling.

---

## 🎯 Objective
The objective of today's task was to master layout engineering using the CSS box model, establish consistent section spacing, configure container sizing with `max-width`, introduce styled cards with padding, borders, and `border-radius`, and eliminate rigid fixed widths to ensure a responsive, maintainable design across screen sizes without third-party frameworks.

---

## 🚀 The Journey Continues
This task marks another important milestone in my Full-Stack Web Development journey.

Following our initial CSS introduction on Day 05 (Selectors, Cascade & Basic Hover States), Day 06 elevates the webpage visual architecture through disciplined layout structure. By resetting default browser spacing, applying universal `box-sizing: border-box`, implementing gradient containers, dynamic event cards (`.event-article`), rounded borders, subtle drop-shadows, and scalable form containers (`.cohort-form`), I have transformed raw styled text into a modern, card-based web layout.

---

## ✅ Task Requirements & Completed Milestones
I have successfully implemented all requirement criteria specified in the briefing using pure CSS (`task06-style.css`) and semantic HTML5:

* **Universal Reset & Box-Sizing:** Applied `box-sizing: border-box` along with zeroed margins and paddings across all elements (`*`) for predictable element dimensions.
* **Centered Container Layout:** Implemented flexbox wrapping and centered layout blocks across header components, navigation bars, main content, and footer sections.
* **Consistent Spacing:** Standardized section margins (`margin-top: 35px`), heading padding, and paragraph block margins (`margin-bottom: 50px`) for proper visual rhythm.
* **Custom Card & Box Styling:** Styled event articles (`.event-article`) using generous padding, distinct asymmetric `border-radius` corners (`25px` / `5px`), background overlays, and interactive hover transformations.
* **Borders & Radius:** Added custom borders and rounded corners (`border-radius: 10px` to `25px`) across navigation links, form inputs, textareas, fieldsets, and primary buttons.
* **Max-Width & Flexible Sizing:** Avoided problematic rigid pixel widths on structural elements, utilizing percentages (`width: 50%` on form container), flexible flexbox items, and `width: 100%` image scaling for flexible viewport adaptation.
* **Preserved HTML Structure:** Kept existing semantic markup intact while enhancing visual appeal strictly through pure CSS.