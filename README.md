# CODTECH-Task1
NAME:HARI NITHIN S
COMPANY:CODTECH IT SOLUTIONS
ID:CTO8FED
DOMAIN:FRONTEND WEB DEVELOPMENT
DURATION:DECEMBER 20TH TO JANUARY 20TH 2025

OVER VIEW OF THE PROJECT
1. Header Section
The document begins with the standard <!DOCTYPE html> declaration, setting the page to use the HTML5 standard.
It sets the language of the webpage to English (<html lang="en">).
The head section includes:
Meta tags for character encoding (UTF-8) and viewport settings to ensure responsiveness on mobile devices.
The title tag specifies the title of the webpage as "Hari Nithin's portfolio".
External stylesheets are linked:
Google Fonts (Noto Sans).
Bootstrap 5 for responsive design.
Internal <style> is used to import Google Fonts again (though it’s redundant) and styles for a dropdown menu.
2. Navbar
A navigation bar (<nav>) uses Bootstrap classes for styling.
Contains a brand name with "Hari Nithin S" and a dropdown menu with links to different sections of the portfolio (Home, About, Skills, Contact).
The dropdown menu (.dropdown) uses custom styles to display a list of links when hovered over.
3. Home Section
The "Home" section introduces the portfolio owner with a background image (using background-image).
Contains a heading ("hi i'am Hari Nithin S") and a subheading ("i am a college student").
There's a call-to-action button (connect with me), which links to a WhatsApp number.
4. About Section
The "About" section also uses a background image and contains an introduction to Hari Nithin S.
A short description of his academic background and interests is provided, including his passion for learning programming, data analysis, and sports like handball.
The section has a two-column layout, with text on the left and an image placeholder on the right (though no image source is specified).
5. Skills Section
The "Skills" section showcases two skills: HTML and CSS, each represented by a card with an image and a brief description of the proficiency level.
The section is styled with a background image and contains a heading.
6. Contact Section
The "Contact" section is designed to allow visitors to reach out via a form.
It includes input fields for the user’s name, email, mobile number, and a message textarea.
A "Submit" button at the bottom allows users to send their contact information (although no action is set for the form).
7. Footer
The footer at the bottom contains a copyright statement, noting that the portfolio is designed and developed by Hari Nithin S.
Notes and Potential Improvements:
Redundant @import statement: The Google Fonts @import in both the <head> and within the <style> tags is unnecessary. It can be removed from the <style> section.
Broken Image Sources: In the About section, the src attribute for the image tag is empty (src=""). You should provide an actual image URL to display the image.
Missing Form Action: The contact form doesn't specify an action attribute, meaning the form won't actually send data anywhere when submitted. It should be linked to a backend or API to handle form submissions.
Bootstrap Missing JS: To enable the dropdown functionality properly, Bootstrap's JavaScript files should be included, as they provide the interaction (for example, the collapsible menu). This is missing in the code, but it could be added at the end of the <body> section:
html

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

Mobile Compatibility: The website uses Bootstrap for responsiveness, which should work well on mobile devices, but it’s always good to test on different screen sizes.
