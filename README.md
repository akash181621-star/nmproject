# nmproject
# Theme-Customizer-in-wordpress
This project demonstrates how to create and implement a custom theme customizer in WordPress. It allows users to modify theme options (like colors, typography, and layout) directly from the WordPress Customizer panel, with real-time previews.

Technologies Used:
WordPress Customizer API
PHP, HTML5, CSS3, JavaScript 
Theme Development Standards

Challenges Faced:
Customizer API Learning Curve – Understanding the structure of add_setting(), add_section(), and add_control() took time.
Live Preview with JavaScript (postMessage) – Implementing instant updates without page refresh required careful setup.
Balancing Flexibility and Simplicity – Designing user-friendly controls while keeping the theme lightweight.
Dynamic CSS Rendering – Generating and applying custom CSS in real-time from Customizer inputs.
Theme Security & Sanitization – Ensuring input validation and sanitization for user-generated data.
Browser Compatibility – Making sure the preview and styles work consistently across all major browsers.

Features:
Live Preview Customization – Instantly preview theme changes such as colors, fonts, and layouts using the WordPress Customizer API.
Custom Sections & Controls – Add your own custom sections, settings, and controls in the Customizer panel.
Color & Typography Options – Let users modify site colors, font families, and font sizes dynamically.
Layout Customization – Provide options for sidebar positions, header styles, and footer layouts.
Custom Logo & Background Uploads – Support for uploading custom logos, headers, and background images.
Responsive Design Preview – Adjust and preview theme behavior on different devices (desktop, tablet, mobile).
Built Using WordPress Customizer API – Implements best practices with WP_Customize_Manager
