# Lab 11: Units and CSS Variables

Name: Pushpendra Singh
Roll No: 2410303367
Student ID: BCS2024376
Section: D
Course: B.Tech(CSE)
Course: BCS554 - HTML & CSS Development Lab
University: Invertis University, Bareilly 


____________________________________________________________


Aim
Use px, %, rem units and CSS custom properties (variables).


Theory
- px is a fixed pixel size. % is relative to the parent element. rem is relative to the root font size (16px by default), so 1.5rem = 24px.
- CSS variables (custom properties) are defined with --name: value;, usually inside :root so the whole page can use them.
- Use a variable with var(--name). Change it once and everything using it updates.
- Design tokens are the central values of a design (colours, spacing, font sizes) stored as variables in one file.

Files in this folder
- units.html: px, % and rem demo.
- variables.html: Variables defined in :root and used with var().
- tokens.css: Design tokens stylesheet.
- tokens-demo.html: Page that uses tokens.css.

How to check
Open with Live Server and screenshot each page.