📱 Responsive Web Design with CSS Media Queries

📌 Overview
This task focuses on converting a desktop-only webpage into a mobile-friendly responsive layout using CSS media queries.
The design automatically adjusts layouts, font sizes, and elements for better usability on smaller screens.

🎯 Objective
Apply CSS media queries to make a static webpage responsive.
Optimize for mobile view (max-width: 768px).
Ensure layouts, text, and images adjust properly across devices.

🛠️ Tools Used
VS Code (for editing HTML/CSS)
Chrome DevTools (for mobile testing)

🧠 Key Concepts
CSS Media Queries
Flexible Layouts (stack columns, reduce font size)
Responsive Images (max-width: 100%; height: auto;)
Navigation menu adjustment for small screens

⚙️ Implementation Steps
Open you HTML file in VS Code.
Identify non-responsive elements (fixed widths, large text, oversized images).
Add a media query targeting smaller screens:
@media (max-width: 768px) {
  body {
    font-size: 14px;
    padding: 10px;
  }

  .container {
    flex-direction: column;
    text-align: center;
  }

  img {
    max-width: 100%;
    height: auto;
  }

  nav ul {
    flex-direction: column;
    gap: 10px;
  }
}

Test the layout using Chrome DevTools → Toggle Device Toolbar.
Fix overflow and spacing issues for smaller viewports.

📂 Deliverables
Updated style.css file with responsive media queries.
A webpage that resizes smoothly on mobile and tablet screens.

🧩 Outcome
✔ Understand how to use media queries for responsive design.
✔ Practice layout adjustments, font resizing, and image scaling for different devices.
