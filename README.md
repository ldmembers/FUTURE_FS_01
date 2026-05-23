Sakthi Kandhavel — Tech-Driven Marketer & Developer Portfolio
📋 Overview
This is a modern, responsive portfolio website for Sakthi Kandhavel — a Third-year B.Tech AI & ML student at SNS College of Technology who combines technical development skills with marketing expertise and community leadership.

The portfolio showcases Sakthi's professional journey as a Forum Leader, Chief Finance Officer, and Full Stack Web Development Intern, along with technical skills, projects, and contact information.

🎨 Features
Visual & Interactive Elements
Dynamic particle background with warm orange-red gradient orbs and connecting lines

Typewriter animation cycling through professional roles

Scroll-triggered reveal animations (fade, slide-left, slide-right)

Glassmorphism UI with backdrop blur effects

Fully responsive design — mobile, tablet, and desktop optimized

Custom scrollbar with brand accent color

Back-to-top button that appears on scroll

Sections Included
Section	Content
Hero	Animated tagline, call-to-action buttons, identity card with contact info
About	Bio, contact chips, stats cards with animated fill bars
Skills	Technical, soft skills, and AI tools with level badges
Experience	Work history cards (Forum Leader, CFO, Full Stack Intern)
Education	Timeline-style academic background
Projects	Featured projects with thumbnails, tags, and demo links
Contact	Form + direct contact chips
Footer	Social links and copyright
Interactive Components
Sticky navigation with active section highlighting

Mobile hamburger menu

Hover effects on cards, buttons, and skill items

Working contact form (front-end validation with success message)

Stat card fill bars animate on scroll

🛠️ Technologies Used
Technology	Purpose
HTML5	Semantic structure
CSS3	Custom styling, animations, glassmorphism, responsive grid/flex layouts
JavaScript (Vanilla)	Canvas particle system, typewriter effect, scroll reveal, intersection observer, mobile menu, form handling
Canvas API	Dynamic animated background
Google Fonts	Syne (headings) + DM Sans (body)
CSS Grid & Flexbox	Responsive layouts
📁 Project Structure
text
sakthi-portfolio/
├── index.html              # Complete single-file portfolio
├── README.md               # Project documentation
└── (no external assets)    # All CSS/JS inline, no external images
Note: This is a single-file HTML document — no external dependencies, images, or build steps required.

🚀 Getting Started
Prerequisites
Any modern web browser (Chrome, Firefox, Safari, Edge)

No server required — works as a static HTML file

Installation
Download the file — save sakthi-portfolio.html to your local machine

Open in browser — double-click the file or drag into your browser window

Deploy online (optional):

Upload to any static hosting service (Netlify, Vercel, GitHub Pages)

Or copy the code into a web server's public directory

Local Development
bash
# No build steps needed — just edit the HTML file
# To preview changes, reload your browser after saving edits
📱 Responsive Breakpoints
Breakpoint	Adjustments
< 960px	Hero column reverses order, grid layouts switch to single column
< 700px	Hamburger menu appears, smaller padding, ID card resized, single-column contact form
🔧 Customization Guide
Update Personal Information
Edit the following sections in the HTML:

html
<!-- Hero name & tagline -->
<h1 class="hero-name">Sakthi<br/><span class="accent">Kandhavel</span></h1>

<!-- Contact details in ID card -->
<div class="id-detail-val">sakthiakandhavel.s@gmail.com</div>

<!-- Typewriter words array -->
const words=['Tech-Driven Marketer','Full Stack Developer','Forum Leader',...];
Modify Color Theme
Change CSS root variables (find :root in <style>):

css
:root {
  --bg:        #0c0a08;      /* Dark background */
  --orange:    #e8531a;      /* Primary accent */
  --gold:      #f5a623;      /* Secondary accent */
  --text:      #ede8e1;      /* Light text */
}
Add/Remove Projects
Copy the project card template:

html
<div class="proj-card reveal">
  <div class="proj-thumb pt1"><!-- thumbnail content --></div>
  <div class="proj-body">
    <div class="proj-title">Your Project Title</div>
    <p class="proj-desc">Description here...</p>
    <div class="proj-tags"><span class="ptag">Tech</span></div>
    <div class="proj-btns"><!-- buttons --></div>
  </div>
</div>
🌐 Live Demo Links
Update these placeholder URLs in the code:

Section	Current Link	Replace With
GitHub button	https://github.com	Your GitHub profile
Project "Live Site"	#	Actual deployment URL
Project GitHub	https://github.com	Your repo URL
LinkedIn	https://linkedin.com	Your LinkedIn profile
Twitter	https://twitter.com	Your Twitter handle
📧 Contact Form Behavior
The contact form currently uses client-side validation only:

Validates name, email, and message are not empty

Displays a success message without sending data to a server

To make it functional:
Add a backend endpoint (Node.js, PHP, or form service like Formspree)

Update the sendMsg() function with fetch() POST request

Example using Formspree (no backend required):

javascript
async function sendMsg() {
  const response = await fetch('https://formspree.io/f/your-endpoint', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ name, email, message })
  });
}
🎯 SEO Considerations
The page includes:

Meta description tag

Semantic HTML5 structure (<header>, <section>, <footer>)

Responsive viewport settings

Proper heading hierarchy (h1 → h2 → ...)

📄 License
This project is for personal portfolio use. You may:

Use this template for your own portfolio

Modify colors, content, and layout freely

Credit: Please retain the footer credit linking back to the original design.

👨‍💻 Author
Sakthi Kandhavel

Email: sakthiakandhavel.s@gmail.com

Location: Mettupalayam, Tamil Nadu

Degree: B.Tech AI & ML (2024–2028), SNS College of Technology

🙏 Acknowledgments
Fonts: Google Fonts (Syne, DM Sans)

Icons: Emoji-based for cross-platform compatibility

Design inspiration: Modern glassmorphism + dark theme portfolios

📞 Support
For questions or suggestions regarding this portfolio template, reach out to Sakthi directly via email or the contact form included in the page.

Built with ❤️ by Sakthi Kandhavel · © 2026

 
