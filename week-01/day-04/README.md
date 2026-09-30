# Day 04 — HTML Forms & Accessibility Basics

**IEEE Open Source Cohort — Web Development Domain**  
**Student Name:** Muhammad Ali Ammad 
**Date:** September 25, 2026

---

## 📋 Task Statement
Today's task is to add a proper registration form to the HTML Page (IEEE Student Branch) created in the previous task (Day 03_Task 03).

---

## 🎯 Objective
The objective of today's task was to learn how users submit information through HTML forms, understand form controls, enforce input validation using semantic attributes and structure input elements clearly without external CSS or JavaScript.

---

## 🚀 The Journey Continues
This task marks another important milestone in my Full-Stack Web Development journey.

Following previous (Day-03_Task-03) structural layout and navigation validation, Day 04 introduces an interactive "Join the Cohort" HTML registration form integrated directly into the IEEE Student Branch page. By utilizing semantic form elements (`<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<select>`, `<option>`, `<textarea>` and `<button>`), enforcing specific input types (`email`, `tel`, `text`, `radio`) and applying `required` field validation, I am mastering client-side data intake and web accessibility fundamentals before transitioning to CSS styling, JavaScript DOM management and backend API handlers.

---

## ✅ Task Requirements & Completed Milestones
I have successfully implemented all requirement criteria specified in the briefing using clean, unstyled HTML5 syntax:

* **Dedicated Form Container:** Created a new section (`id="cohort"`) with a clear heading and registration deadline notification.
* **Full Name Field:** Integrated a dedicated input control with required text validation.
* **Email Field:** Configured using `type="email"` to enforce proper email format validation upon form submission.
* **Phone Field:** Implemented using `type="tel"` to capture contact phone numbers.
* **Department Field:** Added a text input field to accept academic department entries (e.g., BSIT, BSCS).
* **Semester Field:** Built using radio button inputs (`name="selectOne"`) allowing single-choice selection from 1st through 8th Semester.
* **Area of Interest Field:** Implemented a `<select>` dropdown menu containing domains such as Web Development, AI & Machine Learning, Cyber Security, Cloud & DevOps, Data Science, Game Development and UI/UX Design as options added through `<option>` tags.
* **Statement Textarea:** Added a `<textarea>` control titled "Why do you want to join" for candidates to express their expectations and motivations.
* **Semantic Submit Button:** Used a real `<button type="submit">` element to trigger form submission behavior.
* **Accessibility & Form Grouping:** Applied `<label>` elements for every control and utilized `<fieldset>` and `<legend>` blocks for clean, accessible form field grouping.
* **Pure HTML Architecture:** Built completely with pure semantic HTML5 without relying on external CSS styles or inline scripts.