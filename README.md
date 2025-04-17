Cheesecake Wonders Website
A responsive, modern website for a cheesecake business, showcasing products, blog posts, and a contact form. Built with HTML, CSS, and JavaScript, the site features a mobile-first design, smooth animations, and Feather Icons for a polished user experience.
Features

Responsive Design: Fully optimized for mobile (360px+), tablet (768px+), and desktop (1024px+) with fluid layouts and scalable typography.
Hamburger Menu: Collapsible navigation for mobile devices, expanding to a full menu on larger screens.
Animations: Subtle hover effects on buttons, cards, and images, plus fade-in animations for sections on scroll.
Feather Icons: Lightweight icons for star ratings, social media links, and navigation.
Contact Form: Professional, accessible form with validation-ready inputs.
Sections:
Hero: Engaging introduction with a call-to-action.
About: Story of the cheesecake business.
Menu: Showcase of cheesecake products with ratings and prices.
Blog: Recent posts with images and summaries.
Contact: Contact information, social links, and form.



Technologies

HTML5: Semantic markup for accessibility and structure.
CSS3: Mobile-first styling with Flexbox, media queries, and clamp() for responsive typography.
JavaScript: Handles hamburger menu toggle, section fade-in animations, and Feather Icons initialization.
Feather Icons: CDN-hosted icon library for social media and ratings.
Google Fonts: Poppins font for consistent typography.

Setup Instructions
Prerequisites

A modern web browser (Chrome, Firefox, Safari, etc.).
A code editor (e.g., VS Code) for modifications.
Basic knowledge of HTML, CSS, and JavaScript.

Installation

Clone or Download the Repository:
git clone <repository-url>

Or download the ZIP file and extract it.

Navigate to the Project Directory:
cd cheesecake-website


Ensure File Structure:Verify the following structure:
cheesecake-website/
├── img/
│   ├── logo.png
│   ├── 1.png
│   ├── 2x.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── 48104.jpg
│   ├── 502.jpg
│   └── spoon.jpg
├── index.html
├── style.css
├── script.js
└── README.md


Open the Website:

Double-click index.html to open in a browser, or
Use a local development server (recommended for testing):npx http-server

Then navigate to http://localhost:8080 in your browser.



Dependencies

Feather Icons: Loaded via CDN (<script src="https://unpkg.com/feather-icons"></script>).
Google Fonts: Poppins font loaded via CSS import.
No additional installations are required.

Usage

Navigation: Use the hamburger menu on mobile or the top navigation bar on desktop to explore sections.
Contact Form: Fill out the form to send inquiries (requires backend setup for functionality; see "Future Improvements").
Blog and Menu: Browse cheesecake products and blog posts, with hover effects for interactivity.
Social Links: Update <a href="#"> in the contact section with actual social media URLs.

File Structure

index.html: Main HTML file containing the website structure.
style.css: CSS file with mobile-first styles, media queries, and animations.
script.js: JavaScript for hamburger menu toggle, section animations, and Feather Icons.
img/: Folder containing all images (logo, hero, menu items, blog posts, contact).

Customization

Colors: Modify the color scheme in style.css (e.g., #78523b for primary, #fdae37 for accents, #fef8e0 for backgrounds).
Images: Replace images in the img/ folder, ensuring they are optimized (e.g., WebP format, <500KB).
Content: Update text in index.html (e.g., hero description, blog posts, contact info).
Social Links: Edit <a> tags in the contact section with your social media URLs.
Fonts: Change the Google Fonts import in style.css for a different typography style.

Future Improvements

Form Functionality: Integrate a backend (e.g., Node.js, PHP) or a service like Formspree for contact form submissions.
Image Optimization: Convert images to WebP and add loading="lazy" for faster loading.
Accessibility: Add ARIA landmarks and keyboard navigation for enhanced accessibility.
Analytics: Integrate Google Analytics to track user interactions.
SEO: Add meta tags (e.g., description, keywords) and structured data for better search engine visibility.

Testing

Responsiveness: Test across devices using browser dev tools (360px, 480px, 768px, 1024px, 1280px).
Browsers: Verify compatibility in Chrome, Firefox, Safari, and Edge.
Performance: Use tools like Lighthouse to check load times and optimize images.
Accessibility: Run an accessibility audit (e.g., WAVE) to ensure compliance.

Troubleshooting

Images Not Loading: Verify image paths in img/ folder and file names match index.html.
Hamburger Menu Not Working: Ensure script.js is linked and Feather Icons CDN is accessible.
Layout Issues: Check for CSS conflicts or missing media queries; test at various screen sizes.
Animations Lag: Reduce transition durations in style.css for mobile devices.

Credits

Feather Icons: feathericons.com
Google Fonts: fonts.google.com
Design Inspiration: Modern e-commerce and food websites.

License
This project is for personal or educational use. All rights reserved for images and content unless otherwise specified.
Contact
For questions or contributions, contact [Your Name] at [Your Email] or open an issue on the repository.

Last Updated: April 17, 2025
