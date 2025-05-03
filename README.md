Salmin Habibu Personal Portfolio
A clean, modern, and responsive personal portfolio website built with HTML, CSS, and JavaScript.

Portfolio Preview

Overview
This portfolio website showcases Salmin Habibu's professional skills, experience, and projects in a visually appealing interface. The website is designed to be responsive, ensuring a seamless user experience across all device sizes.

Features
Responsive Design: Looks great on all devices (desktop, tablet, and mobile)
Interactive UI: Smooth animations and transitions
Dynamic Project Filtering: Filter projects by category
Contact Form: Functional contact form with client-side validation
Smooth Scrolling: Enhanced user experience with smooth navigation
Back to Top Button: Easy navigation back to the top of the page
Skills Visualization: Visual representation of skills with animated progress bars
Timeline Layout: Clean timeline representation for resume and experience
Structure
text

portfolio/
├── css/
│   └── styles.css
├── images/
│   └── profile.jpg
├── js/
│   └── script.js
├── index.html
└── README.md
Installation
Download the portfolio-website.zip file
Extract the contents to your desired location
Open index.html in your web browser to view the website locally
Alternatively, clone the repository:

bash

git clone <repository-url>
cd portfolio
Usage
This portfolio is ready to use out of the box. Simply open the index.html file in a web browser to view it locally.

Customization
General Information
Open index.html and update the personal information:
Name
Profile image
Contact details
Social media links
About section text
Projects
To add or modify projects:
Find the projects-grid section in index.html
Add or modify the project items following the existing structure
Update the data-category attribute to categorize your projects correctly
Example project item:

html

<div class="project-item" data-category="web">
    <div class="project-img">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Technologies Used</p>
        <div class="project-links">
            <a href="#" class="btn-view-project">View Project</a>
        </div>
    </div>
</div>
Resume/Experience
To update your experience and education:
Locate the resume section in index.html
Modify the timeline items with your information
Skills
To update your skills:
Find the skills section in index.html
Modify the skill items and progress percentages
Styling
To customize colors and styles:
Open css/styles.css
The color scheme and key styles are defined as CSS variables at the top of the file
css

:root {
    --primary-color: #5c62ec;
    --primary-dark: #4549a9;
    /* other variables */
}
Deployment
GitHub Pages
Push your portfolio to a GitHub repository
Go to repository Settings > Pages
Select the branch to deploy (usually main or master)
Your site will be available at https://yourusername.github.io/repository-name/
Netlify
Create an account on Netlify
Drag and drop the portfolio folder to the Netlify dashboard
Your site will be deployed with a Netlify subdomain
Other Hosting Options
Vercel
Firebase Hosting
Amazon S3
Any traditional web hosting service
Server-Side Integration
The contact form currently uses client-side validation and simulates submission. To make it fully functional:

Create a server-side script (PHP, Node.js, etc.) to process form submissions
Update the form action in index.html to point to your server script
Modify the JavaScript in script.js to handle actual form submission
Credits
Font Awesome for icons
Google Fonts for typography
Placeholder images from Placeholder.com
License
This project is open source and available under the MIT License.
