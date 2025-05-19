# DevOps Engineer Portfolio

This is my personal portfolio website showcasing my skills and experience as a DevOps Engineer. The site is built with HTML, CSS, and JavaScript, and is hosted using GitHub Pages.

## Features

- Responsive design that works on all devices
- Modern and clean UI with smooth animations
- Sections for About, Skills, Projects, and Contact information
- Interactive project cards with technology stack tags
- Smooth scrolling navigation
- Intersection Observer API for scroll animations

## Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- GitHub Pages for hosting

## Setup and Deployment

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   ```

2. Navigate to the repository folder:
   ```bash
   cd yourusername.github.io
   ```

3. Customize the content:
   - Update the information in `index.html` with your personal details
   - Modify the styling in `styles.css` if desired
   - Add your own projects and skills

4. Deploy to GitHub Pages:
   - Push your changes to the main branch
   - Go to repository Settings > Pages
   - Select the main branch as the source
   - Your site will be published at `https://yourusername.github.io`

## Customization

### Adding Projects

To add a new project, copy and modify the project card template in the Projects section of `index.html`:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description goes here.</p>
    <div class="tech-stack">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
    <a href="https://github.com/yourusername/project" class="project-link" target="_blank">
        <i class="fab fa-github"></i> View Project
    </a>
</div>
```

### Updating Skills

To update the skills section, modify the skill categories in the Skills section of `index.html`. Each category follows this structure:

```html
<div class="skill-category">
    <h3><i class="fas fa-icon-name"></i> Category Name</h3>
    <ul>
        <li>Skill 1</li>
        <li>Skill 2</li>
    </ul>
</div>
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Feel free to reach out to me at [your-email@example.com](mailto:your-email@example.com) or connect with me on [LinkedIn](https://linkedin.com/in/yourprofile).
