# Musicon

**Description:**  
Musicon is an interactive, multi-page website for an online musical instruments store. This project demonstrates the integration of HTML, CSS, JavaScript, and Handlebars to create a stylish, functional, and responsive web application.

---
## Features

- Navigation Bar:  
  - A fully styled navigation bar using unordered lists and anchor tags.  
  - Easy access to the home, store, and contact pages.

- Stylish Design:  
  - Custom CSS styling for layout, positioning, color schemes, and typography.

- Dynamic Content Rendering:  
  - Handlebars.js used to create reusable templates for the store page.  
  - JavaScript objects and arrays dynamically populate the templates.

- Responsive Pages:  
  - Layout adapts seamlessly to different screen sizes and devices.

---

## Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Handlebars.js  

---

File Structure

musicon/
├── public/
│   ├── style.css          # Custom styles
│   ├── main.js            # JavaScript logic for dynamic rendering
│   └── handlebars.min.js  # Handlebars.js library
├── index.html             # Home page
├── store.html             # Store page
├── contact.html           # Contact page
└── README.md              # Project documentation



How It Works

Home Page: Provides a brief introduction to the store and its offerings.
Store Page:
Uses Handlebars.js templates to dynamically render a list of instruments.
Instruments are fetched from a JavaScript object array.
Contact Page: Contains a simple contact form for user inquiries.
Navigation:
A navigation bar allows seamless switching between pages.
The current class highlights the active page.
