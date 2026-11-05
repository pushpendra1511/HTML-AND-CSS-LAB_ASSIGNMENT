# Lab 14: CSS Grid Layouts

Name: Pushpendra Singh
Roll No: 2410303367
Student ID: BCS2024376
Section : D
Course: BCS554 - HTML & CSS Development Lab
University: Invertis University, Bareilly (B.Tech CSE)


_____________________________________________________________


Aim
Create grids with columns, auto-fill galleries and named areas.


Theory
- CSS Grid is a two-dimensional layout system (rows and columns together). Enable it with display: grid.
- grid-template-columns: 1fr 1fr 1fr makes three equal columns. fr means a share of the free space.
- repeat(auto-fill, minmax(150px, 1fr)) makes as many columns of at least 150px as fit, so a gallery adjusts to the screen width.
- grid-template-areas names regions of the layout, and grid-area places an element into a named region.
- Use Flexbox for one-dimensional layouts and Grid for full page or two-dimensional layouts.


Files in this folder
- grid-first.html: Six boxes in three columns.
- gallery.html: Responsive photo gallery.
- dashboard-areas.html: Header, sidebar, main and footer with grid areas.


How to check
Open with Live Server, resize the window and screenshot