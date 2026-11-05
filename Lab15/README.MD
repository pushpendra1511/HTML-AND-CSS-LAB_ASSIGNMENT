# Lab 15: Responsive Pages with Media Queries

Name: Pushpendra Singh
Roll No: 2410303367
Student ID: BCS2024376
Section : D
Course: BCS554 - HTML & CSS Development Lab
University: Invertis University, Bareilly (B.Tech CSE)

_____________________________________________________________


Aim
Make pages adapt to phone and desktop widths.


Theory

- Responsive design makes one page look good on every screen size.
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> is required so phones use their real width.
- Mobile-first: write the simple phone layout first, then add @media (min-width: 600px) { ... } for bigger screens.
- A media query applies CSS only when its condition (like a minimum width) is true.
- Make images flexible with max-width: 100%; height: auto;.
- Relative units (rem, %, fr) scale better than fixed px.


Files in this folder

- mobile-first.html: Cards stacked on phones, side by side above 600px.
- responsive-image.html: Image that never overflows its container.
- responsive-text.html: Heading that grows above 600px.
- images/sample.jpg: Placeholder picture.
How to check
Open with Live Server, press F12 and use the device toolbar (phone icon) to test sizes. Screenshot both views.