# Knox-Box
Denton Fire Department - Knox Box Guidelines
This project is a standalone, single-page HTML landing page designed to provide public information regarding the Knox Rapid Access System requirements for the City of Denton, Texas.
🚀 Quick Start
Download the knox_guidelines.html file. Open the file in any modern web browser (Chrome, Edge, Firefox, Safari). No installation required: The project uses a Content Delivery Network (CDN) for styling, so you do not need to install Node.js or run build commands.Note: An active internet connection is required to load the fonts, icons, and Tailwind CSS styles.
🛠️ Technology Stack
HTML5: Semantic markup for accessibility and structure.Tailwind CSS (CDN): Utility-first CSS framework for styling.Google Fonts: Uses the "Inter" font family.JavaScript: Minimal inline script for Tailwind configuration.
🎨 Customization
Branding Colors
The color palette is defined in the <script> tag within the <head> section. You can adjust the hex codes to match updated branding requirements:
tailwind.config = {
    theme: {
        extend: {
            colors: {
                navy: '#152a40',  // DFD Navy
                red: '#bf2726',   // DFD Red
                yellow: '#f9c031',// DFD Yellow
            }
        }
    }
}
Images
Currently, images are hosted on external servers (Constant Contact and Transparent Textures).Recommendation: For a production deployment, download the images and save them to a local images/ folder relative to the HTML file.Update Paths: Change src="https://..." to src="images/filename.png".
📱 Features
Responsive Design: Adapts to mobile, tablet, and desktop screens.Sticky Navigation: The top menu remains visible while scrolling.Smooth Scrolling: Clicking navigation links smoothly animates to the section. Print Friendly: The layout is simple enough to print reasonably well for handouts.
📦 Deployment
Since this is a static HTML file, it can be deployed to:
Any standard web server (Apache, Nginx, IIS).GitHub Pages.Netlify or Vercel (drag and drop).SharePoint or internal intranet file servers.
📝 License
This code is intended for use by the Denton Fire Department or authorized entities.
