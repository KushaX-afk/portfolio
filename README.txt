KUSHAGRA RAJ - STATIC HTML/CSS PORTFOLIO
========================================

This project has been converted into a plain HTML and CSS portfolio.
The usable site now lives in the root folder:

- index.html       -> Home
- about.html       -> About
- projects.html    -> Project showcase
- customers.html   -> Customers
- youtube.html     -> YouTube videos
- contact.html     -> Contact form and email link
- styles.css       -> All styling, layout, animation, and responsive rules

How to open the site
--------------------

Open index.html in a browser. All navigation links point to the other
HTML pages in this same folder.

The pages use these image folders:

- assets/
- thumbnails/

No JavaScript is required for the converted static site. The mobile menu,
about-page tabs, hover effects, animations, responsive grids, and buttons
are handled with HTML and CSS only.

Editing quick guide
-------------------

Change site colors:
Edit the variables at the top of styles.css, especially:

- --bg
- --purple
- --pink
- --orange
- --cyan

Change navigation links:
Edit the header block in each HTML file.

Add a project:
Open projects.html, copy one .project-card block, update the title,
tool label, image path, and live project link.

Add a YouTube video:
Open youtube.html, copy one .video-card block, update the YouTube URL,
thumbnail path, title, views, and time badge.

Change contact email:
Open contact.html and replace rajkushagra194@gmail.com in both the
email link and the form action.

Important note
--------------

The old React source and dependency files were left untouched so the
original version is not destroyed. The converted HTML/CSS version is the
root-level static site listed above.
