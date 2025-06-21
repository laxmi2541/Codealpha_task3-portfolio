# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This template provides a clean and professional way to showcase your work, skills, and contact information.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive layout
- ⚡ Smooth scrolling and animations
- 🍔 Mobile-friendly navigation
- 📝 Contact form
- 🎯 Project showcase section
- 💪 Skills display
- 📊 About section with statistics
- 🔗 Social media links

## Getting Started

1. Clone this repository or download the files
2. Open `index.html` in your code editor
3. Customize the content to match your information
4. Replace placeholder images with your own
5. Update the contact form to handle submissions (you'll need a backend service)

## Customization

### Personal Information

Edit the following sections in `index.html`:
- Your name and title in the hero section
- About section content
- Project details and images
- Skills and technologies
- Contact information
- Social media links

### Styling

The website uses CSS variables for easy customization. In `styles.css`, you can modify:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### Adding Projects

To add a new project, copy the project card structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path-to-your-image" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn small">View Demo</a>
            <a href="#" class="btn small secondary">Source Code</a>
        </div>
    </div>
</div>
```

### Adding Skills

To add new skills, use the following structure:

```html
<div class="skill-item">
    <i class="fab fa-icon-name"></i>
    <span>Skill Name</span>
</div>
```

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as source
5. Your site will be published at `https://yourusername.github.io/repository-name`

### Netlify

1. Create a Netlify account
2. Click "New site from Git"
3. Choose your repository
4. Deploy settings will be automatically configured
5. Your site will be published at a Netlify subdomain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images 