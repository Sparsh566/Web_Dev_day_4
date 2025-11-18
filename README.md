Task 4 — Making a Website Mobile-Friendly Using CSS Media Queries

✅ Objective
Convert an existing desktop-only webpage into a fully mobile-friendly responsive layout using CSS media queries.


📂 Files Used
index.html — Existing webpage
style.css — Updated with responsive media queries


🧰 Tools Required
VS Code
Chrome/Brave DevTools (Device Toolbar)
Any existing HTML/CSS file


📝 What I Did
1. Opened the project in VS Code
Loaded the index.html and style.css files inside the project folder.


2. Identified non-responsive elements
Checked for:
Fixed widths
Large images
Horizontal layouts
Overflow issues
Desktop-only nav layout


3. Added Media Query for Mobile (max-width: 768px)
Inside style.css, added:
@media (max-width: 768px) {
  body {
    padding: 10px;
  }
  nav ul {
    flex-direction: column;
    text-align: center;
    gap: 10px;
  }
  img {
    width: 100%;
    height: auto;
  }
  .container {
    flex-direction: column;
    width: 100%;
  }
  h1 {
    font-size: 24px;
  }
  p {
    font-size: 16px;
  }
  button {
    width: 100%;
  }
}

4. Adjusted Layout for Mobile
Stacked columns vertically
Reduced text and button sizes
Made navigation menu vertical
Ensured no overflow on left/right
Added responsive images

5. Tested on Brave Browser
Used Brave DevTools → Device Toolbar
Checked on:
iPhone 12
Pixel 7
Samsung Galaxy S8

Ensured:
No horizontal scroll
Text readable
Nav menu stacked
Buttons centered
Images scaled inside container


6. Fixed Issues
Removed fixed widths
Added width: 100% for container blocks
Fixed padding and alignment
Ensured images don’t overflow


📸 Screenshots 
Desktop view screenshot
Mobile view screenshot using Brave DevTools
