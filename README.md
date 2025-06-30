# Multiple Websites on GitHub Pages

This repository contains multiple websites hosted on GitHub Pages. Each website is organized in its own folder within the `sites` directory, making it easy to maintain multiple websites in a single repository.

## Repository Structure
??? index.html (Main landing page)
??? README.md
??? sites/
?   ??? cnc-solutions/ (CNC Machining Services website)
?   ?   ??? index.html
?   ?   ??? css/
?   ?   ??? js/
?   ?   ??? images/
?   ?
?   ??? portfolio-site/ (Portfolio website template)
?   ?   ??? index.html
?   ?   ??? css/
?   ?   ??? js/
?   ?   ??? images/
?   ?
?   ??? [add more websites here]
## Websites Included

### 1. CNC Solutions Website
A professional website for a CNC machining services company showcasing their capabilities, services, and portfolio.

- **Path:** `/sites/cnc-solutions/`
- **Technologies:** HTML5, CSS3, JavaScript
- **Features:** Responsive design, service showcase, portfolio gallery, contact form

### 2. Portfolio Website Template
A personal portfolio website template for showcasing skills, projects, and professional experience.

- **Path:** `/sites/portfolio-site/`
- **Technologies:** HTML5, CSS3, JavaScript
- **Features:** Skills display, portfolio gallery, contact form

## How to Use This Repository

### Viewing the Websites
1. The main landing page at the root directory links to all websites
2. Each website can be accessed directly via its path: `yourusername.github.io/sites/website-name/`

### Adding a New Website
1. Create a new folder in the `sites` directory
2. Add your HTML, CSS, JS, and other assets to this folder
3. Update the main `index.html` file to add a link to your new website

### Local Development

To work on these websites locally:

1. Clone this repository to your local machinegit clone https://github.com/yourusername/yourusername.github.io.git
2. Navigate to the project foldercd yourusername.github.io
3. To work on a specific website, navigate to that website's foldercd sites/website-name
4. Open the site in your web browser by opening `index.html` or using a local server

## Deploying to GitHub Pages

To deploy this collection to GitHub Pages:

1. Push your changes to your GitHub repository
2. Go to your GitHub repository settings
3. Scroll down to the "GitHub Pages" section
4. Select your main branch as the source
5. The sites will be published at `https://yourusername.github.io/` and each website will be accessible at its respective path

## Customization

Each website can be customized independently without affecting others:

- Replace placeholder images in each website's `images` folder
- Update text content in each website's `index.html` file
- Modify styles in each website's CSS files
- Add functionality through each website's JavaScript files

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or support, please contact [your contact information].