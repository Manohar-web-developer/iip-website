# iip-website
IIP ACADEMY
Website Development Project
Addition Note / Project Documentation

1. Project Overview
Field	Details
Project Name	IIP Academy Website
Type	Static Website (Multi-Page)
Technology Used	HTML5, CSS3
Total Pages	6 Pages
CSS Architecture	Common CSS + Page-Specific CSS
Purpose	Informational website for IIP Academy — an IT training institute in Jodhpur


2. Project Folder Structure
The project is organized in a clean, structured format as follows:

IIP Website/
├── Html/                  ← All HTML page files
├── index.html
├── about-us.html
├── courses.html
├── gallary.html
├── enquiry.html
└── contact-us.html
├── css/                   ← All CSS style files
├── common.css             (Shared styles — header, menu, footer)
├── index.css              (Home page styles)
├── about-us.css           (About Us page styles)
├── courses.css            (Courses page styles)
├── gallary.css            (Gallery page styles)
├── enquiry.css            (Enquiry form styles)
└── contact-us.css         (Contact page styles)
└── Images/                ← All images and icons

3. Pages & Their Description
3.1  index.html — Home Page
•	Top header bar with website URL and email ID
•	Navigation menu with links to all pages
•	Left sidebar with quick navigation links and News section
•	Banner image in the main content area
•	Course listing section showing 8 courses with colorful icons
•	'How We Work' section with 4 colorful step cards
•	Footer with Quick Links, Training list, address, and social media icons

3.2  about-us.html — About Us Page
•	Page heading with breadcrumb navigation (Home / About Us)
•	Detailed content about IIP Academy — training, projects, hosting
•	Highlights Engineering / MCA student project opportunities
•	'Why IIP Academy' section with ordered list of 5 key benefits

3.3  courses.html — Courses Page
•	3-column grid layout displaying 9 courses
•	Each course card has a colored image header and course name below
•	Courses: PHP, Python, Advance PHP, SEO, Android, Graphic Design, Digital Marketing, WordPress, Java

3.4  gallary.html — Gallery Page
•	3x3 image grid layout with 9 gallery cards
•	Each card has an image on top and a dark title bar at the bottom
•	Hover effect: card scales up and image zooms in slightly
•	Images sourced from Images/gallery_img/ folder (1.jpg to 9.jpg)

3.5  enquiry.html — Enquiry Page
•	Complete enquiry form with the following fields:
•	Gender (Radio buttons: Male / Female)
•	Name, Contact No, Email (Text inputs)
•	Country, State, City (Dropdown selects)
•	Address and Enquiry (Textarea fields)
•	Send button styled in IIP Academy blue (#00A8EC)

3.6  contact-us.html — Contact Us Page
•	Two-column contact info section with Phone icon and Location pin icon
•	Phone: 0291-2468122, +91-9269698122
•	Email: info@iipacademy.com  |  Website: www.iipacademy.com
•	Address: Ground Floor, Laxmi Tower, Bhaskar Circle, Ratanada, Jodhpur (Raj.)
•	'Find Us On Map' section with embedded map image


4. CSS Architecture (Modular Design)
A key feature of this project is its modular CSS structure. Instead of writing all CSS in one single file, the styles are divided into:

CSS File	Used In	Contains
common.css	All 6 pages	Header, Top Menu, Sidebar, Footer
index.css	index.html only	Course list colors, How We Work section
about-us.css	about-us.html only	Page status bar, content paragraphs, imp list
courses.css	courses.html only	Course cards, image headers, color themes per course
gallary.css	gallary.html only	3x3 grid, card layout, hover animations
enquiry.css	enquiry.html only	Form layout, input fields, radio buttons, Send button
contact-us.css	contact-us.html only	Contact info boxes, map section


5. Key HTML Concepts Used
•	Semantic tags: <div>, <ul>, <li>, <a>, <img>, <h1>–<h5>, <p>
•	Navigation using <ul> and <li> with anchor tags
•	Images linked using <img src='...' alt='...'>
•	Forms with <input>, <select>, <textarea>, <button>, <label>
•	Radio buttons grouped using name='gender'
•	Dropdown selects using <select> and <option>
•	Linking CSS using <link rel='stylesheet' href='...'>
•	Comments used throughout: <!-- Section Start --> / <!-- Section End -->


6. Key CSS Concepts Used
•	CSS Flexbox: Used for header, menu bar, footer layout
•	CSS Grid: Used for Courses page (3-column), Gallery page (3x3), How We Work (4-column)
•	Box Model: margin, padding, border, box-sizing: border-box
•	Border Radius: Rounded corners on cards, buttons, news box
•	CSS Transitions: Hover effects on gallery cards (scale + zoom)
•	Background Images: 'How We Work' section uses background-image with background-position
•	Color Theming: Each course has its own brand color applied consistently
•	object-fit: cover: Used in gallery images to maintain aspect ratio
•	CSS Variables approach: .active class applies color #00A8EC across all pages


7. Color Scheme
Color	Hex Code	Used For
IIP Blue	#00A8EC	Active links, sidebar buttons, headings
Dark Grey	#343130	Top header bar, footer background
Orange	#F09C01	News box header
Light Grey	#F1F0EF	Page background
White	#FFFFFF	Menu bar, content areas
Dark Copyright	#302D2C	Copyright bar


8. Features Summary
•	Fully multi-page website with 6 pages
•	Consistent header, navigation, sidebar and footer across all pages
•	Active link highlighting using .active CSS class
•	Responsive-ready layout using Flexbox and Grid
•	Modular CSS: common.css + page-specific CSS (easy to maintain)
•	Gallery with hover animation effects
•	Enquiry form with all standard form elements
•	Contact page with phone, email, address and map
•	Social media links in footer (Instagram, LinkedIn, Facebook, Twitter)
•	Copyright bar at the bottom of every page


9. Student Declaration
I hereby declare that this project — IIP Academy Website — has been developed by me as part of my web development training. All HTML and CSS code has been written manually using concepts learned during the course. The project demonstrates practical application of HTML5 and CSS3 including Flexbox, Grid, Forms, Modular CSS, and multi-page navigation.

Student Name:  Manohar Choudhary
Date:  30 March 2026
Signature: Manohar Choudhary
Trainer / Institute: Ssandeep bhati / WS Cube Tech

