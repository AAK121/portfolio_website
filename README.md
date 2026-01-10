# Portfolio Website

A clean, professional portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases projects, interests, courses, and an about section.

## Features

- 📱 Fully responsive design
- 🎨 Clean, minimalist white background design
- 🚀 Smooth scrolling navigation
- 💼 Project showcase section
- 📚 Courses (current and completed)
- 🎯 Interests section
- 📧 Contact information
- ⚡ Fast and lightweight

## Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── css/
│   ├── styles.css      # Main stylesheet
│   └── responsive.css  # Responsive design styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Images folder (add your images here)
├── assets/             # Additional assets
└── README.md           # Project documentation
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `portfolio` or `username.github.io` for a user site)
4. Make the repository public
5. Don't initialize with README (we already have one)

### Step 2: Push Your Code to GitHub

Open your terminal/PowerShell in the Portfolio directory and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your GitHub username and repository name.

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Customization Guide

### Update Personal Information

1. **index.html**:
   - Replace `[Your Name]` with your actual name
   - Update the hero section with your introduction
   - Edit the About Me section
   - Add your actual projects with descriptions
   - Update interests to match yours
   - Fill in your courses (current and completed)
   - Replace placeholder links with your actual social media/GitHub links

### Add Your Projects

In the Projects section, update each project card:
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <span class="project-status">Completed</span>
    </div>
    <p class="project-description">
        Your project description here
    </p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="your-demo-link" class="project-link">View Project</a>
        <a href="your-github-link" class="project-link">GitHub</a>
    </div>
</div>
```

### Add Images

Place your images in the `images/` folder and reference them in your HTML:
```html
<img src="images/your-image.jpg" alt="Description">
```

### Customize Colors (Optional)

If you want to adjust colors while keeping it minimal, edit `css/styles.css`:
```css
:root {
    --primary-color: #000000;    /* Main black color */
    --secondary-color: #333333;  /* Dark gray */
    --text-color: #222222;       /* Text color */
    --text-light: #666666;       /* Light text */
}
```

## Local Development

To view your website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- No external dependencies or frameworks

## License

Feel free to use this template for your own portfolio. No attribution required.

## Tips for Success

1. **Keep Content Updated**: Regularly update your projects and courses
2. **Add Real Content**: Replace all placeholder text with your actual information
3. **Optimize Images**: Compress images before adding them to reduce load time
4. **Test Responsiveness**: Check your site on different devices
5. **Add Analytics**: Consider adding Google Analytics to track visitors
6. **SEO**: Update meta tags in the HTML head section

## Need Help?

- Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
- Review [MDN Web Docs](https://developer.mozilla.org/) for HTML/CSS/JS reference

---

**Good luck with your portfolio! 🚀**
