===============================================
FLUENTBIT WEBSITE - README
===============================================

Welcome to the FluentBit Website!
This is a professional, modern, responsive multi-page website built with HTML, CSS, and JavaScript.

===============================================
FILE STRUCTURE
===============================================

FluentBit/
│
├── index.html          # Home page with hero section and keywords
├── about.html          # About page with mission and vision
├── contact.html        # Contact page with Google Form
├── download.html       # Download page with installation guides
├── style.css           # All styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.txt          # This file

===============================================
HOW TO RUN THE WEBSITE LOCALLY
===============================================

OPTION 1: Open Directly in Browser
1. Navigate to the project folder
2. Double-click on "index.html"
3. The website will open in your default browser

OPTION 2: Using Live Server (Recommended)
1. Install a local web server (e.g., VS Code Live Server extension)
2. Open the project folder in your code editor
3. Right-click on index.html and select "Open with Live Server"
4. The website will open at http://localhost:5500 (or similar)

OPTION 3: Using Python Simple Server
1. Open terminal/command prompt in the project folder
2. Run: python -m http.server 8000
   (Or: python3 -m http.server 8000)
3. Open browser and go to: http://localhost:8000

===============================================
HOW TO CUSTOMIZE
===============================================

1. COLORS
   Open "style.css" and modify the CSS variables at the top:
   
   :root {
       --primary-color: #3D6FF4;      /* Main blue color */
       --secondary-color: #FFFFFF;     /* White */
       --accent-color: #C4D6EE;       /* Light blue accent */
       --text-color: #000000;         /* Black text */
   }
   
   Change these hex values to your preferred colors.

2. KEYWORDS & LINKS
   Open "index.html" and find the content sections.
   Look for <a href="..."> tags with the focus keywords:
   - fluentbit
   - best fluentbit operations
   - promtail vs fluentbit
   
   Replace URLs in the href="" attributes with your desired links.

3. GOOGLE FORM LINK
   Open "contact.html" and find this line:
   
   <a href="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform"
   
   Replace the URL with your own Google Form link.

4. GITHUB REPOSITORY LINK
   In all HTML files, find:
   
   https://github.com/kinseydarow/FluentBit
   
   Replace with your own GitHub repository URL.

5. DOWNLOAD LINK
   Open "download.html" and find:
   
   <a href="https://fluentbit.net/download/" target="_blank"
   
   Replace with your actual download page URL.

6. FOOTER TEXT
   In all HTML files, find the footer section:
   
   <p>Designed & Developed by <span class="highlight">Kinsey Darow</span></p>
   
   Replace "Kinsey Darow" with your name or brand.

7. SOCIAL MEDIA LINKS
   In the footer of all pages, find:
   
   <div class="social-links">
       <a href="https://github.com/..."><i class="fab fa-github"></i></a>
       <a href="#"><i class="fab fa-twitter"></i></a>
       ...
   </div>
   
   Replace "#" with your actual social media URLs.

8. WEBSITE CONTENT
   - Open any HTML file
   - Find the text content within <p>, <h1>, <h2>, etc. tags
   - Modify the text as needed
   - Keep the HTML structure intact

9. IMAGES (Optional)
   Currently, the website uses CSS-based designs and Font Awesome icons.
   To add your own images:
   
   - Create an "images" folder in the project directory
   - Add your images to this folder
   - In HTML, add: <img src="images/your-image.jpg" alt="Description">
   - Style images in style.css as needed

10. FONTS
    The website uses Google Fonts (Inter and Poppins).
    To change fonts:
    
    - Open any HTML file
    - Find the <link> tag for Google Fonts
    - Replace with your preferred fonts from https://fonts.google.com
    - Update font-family in style.css

===============================================
FEATURES INCLUDED
===============================================

✓ Fully responsive design (mobile, tablet, desktop)
✓ Modern navigation with mobile hamburger menu
✓ Smooth scrolling and animations
✓ Interactive tab system on download page
✓ Copy-to-clipboard functionality for code blocks
✓ Back-to-top button
✓ SEO-friendly semantic HTML
✓ Cross-browser compatible
✓ Fast loading and optimized
✓ Professional color scheme
✓ Font Awesome icons integration
✓ Fade-in animations on scroll

===============================================
BROWSER COMPATIBILITY
===============================================

✓ Chrome (latest)
✓ Firefox (latest)
✓ Safari (latest)
✓ Edge (latest)
✓ Mobile browsers (iOS Safari, Chrome Mobile)

===============================================
RESPONSIVE BREAKPOINTS
===============================================

- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: ≤ 480px

===============================================
EXTERNAL DEPENDENCIES
===============================================

1. Google Fonts (Inter & Poppins)
   https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Poppins:wght@400;500;600;700&display=swap

2. Font Awesome Icons (v6.4.0)
   https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css

Note: These are loaded via CDN and require internet connection.
For offline use, download and include them locally.

===============================================
SEO OPTIMIZATION
===============================================

Each page includes:
- Meta description tags
- Semantic HTML5 elements (header, nav, section, footer)
- Descriptive alt attributes (for images, if added)
- Clean URL structure
- Proper heading hierarchy (h1, h2, h3)
- Internal linking for better navigation

To improve SEO further:
1. Add sitemap.xml
2. Add robots.txt
3. Implement Open Graph tags
4. Add structured data (JSON-LD)

===============================================
PERFORMANCE TIPS
===============================================

1. Optimize images before uploading (compress, resize)
2. Minify CSS and JavaScript for production
3. Use a CDN for faster loading
4. Enable caching on your web server
5. Consider using lazy loading for images

===============================================
DEPLOYMENT OPTIONS
===============================================

OPTION 1: GitHub Pages
1. Create a GitHub repository
2. Push all files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at: https://username.github.io/repo-name

OPTION 2: Netlify
1. Sign up at netlify.com
2. Drag and drop the project folder
3. Your site will be live instantly
4. Netlify provides free SSL and custom domain support

OPTION 3: Vercel
1. Sign up at vercel.com
2. Import your GitHub repository
3. Vercel will automatically deploy
4. Get instant previews for every change

OPTION 4: Traditional Web Hosting
1. Get hosting from providers like Bluehost, HostGator, etc.
2. Upload files via FTP/SFTP
3. Point your domain to the hosting
4. Website will be live

===============================================
TROUBLESHOOTING
===============================================

ISSUE: Navigation menu not working on mobile
SOLUTION: Make sure script.js is properly linked and loaded

ISSUE: Styles not applying
SOLUTION: Clear browser cache, check if style.css is properly linked

ISSUE: Icons not showing
SOLUTION: Check internet connection (Font Awesome loads via CDN)

ISSUE: Links not working
SOLUTION: Ensure all href attributes have correct URLs

ISSUE: Google Form button not opening
SOLUTION: Verify the Google Form link is correct and publicly accessible

===============================================
SUPPORT & CONTACT
===============================================

For questions, issues, or customization help:
- GitHub: https://github.com/kinseydarow/FluentBit
- Contact Form: Use the contact page on the website

===============================================
LICENSE
===============================================

This website template is free to use and modify.
Font Awesome icons are licensed under CC BY 4.0
Google Fonts are licensed under Open Font License

===============================================
CREDITS
===============================================

Design Inspiration: fluentbit.net
Built with: HTML5, CSS3, JavaScript
Fonts: Inter & Poppins (Google Fonts)
Icons: Font Awesome 6.4.0
Developed by: Kinsey Darow

===============================================
VERSION HISTORY
===============================================

Version 1.0 (2024)
- Initial release
- 4 pages (Home, About, Contact, Download)
- Fully responsive design
- Modern animations and interactions

===============================================
NEXT STEPS
===============================================

1. Replace placeholder links with actual URLs
2. Customize colors to match your brand
3. Add your own content and images
4. Test on multiple devices
5. Deploy to your hosting platform
6. Set up custom domain (optional)
7. Monitor performance and user feedback

Thank you for using this template!
Happy customizing! 🚀

===============================================
