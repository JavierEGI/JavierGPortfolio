# Javier G. Issa Data Portfolio

## Overview
This is a personal data portfolio website for showcasing your analytics and business intelligence projects. Built with static HTML and CSS.

## File Structure
- index.html → Homepage with introduction and featured projects.
- projects.html → Gallery with all projects.
- project-template.html → Template to duplicate for new projects.
- style.css → Main stylesheet.
- images/ → Folder for your project images.

## How to Add a New Project
1. Copy 'project-template.html' and rename it, e.g., 'project-new.html'.
2. Edit the contents (title, description, image, tools, etc.).
3. Save an image in the 'images' folder and update its path.
4. Go to 'projects.html' and add a new block inside the `.project-gallery` section:
   ```html
   <div class="project-card">
     <img src="images/your-image.jpg" alt="Project Name" />
     <h4>Project Name</h4>
     <p>Short description of the project.</p>
     <a href="project-new.html" class="btn">View Details</a>
   </div>
   ```
5. Save and upload all files to your hosting platform (GitHub Pages, Netlify, etc.).

Enjoy your portfolio!
