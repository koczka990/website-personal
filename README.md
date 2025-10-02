# Vencel Dávid Koczka - Personal Portfolio Website

A modern, minimalistic personal portfolio website for a Data Scientist and Software Engineer specializing in LLM applications and RAG pipelines.

## Features

- ✨ **Modern Design**: Clean, minimalistic interface with subtle animations
- 🌓 **Dark/Light Mode**: Toggle between themes with persistence
- 📱 **Responsive**: Mobile-first design that works on all devices
- ⚡ **Fast Loading**: Optimized for performance and GitHub Pages
- 🎨 **Smooth Animations**: Scroll-triggered fade and slide animations
- 📧 **Contact Form**: Static-friendly contact form using mailto
- 🔍 **SEO Optimized**: Meta tags, Open Graph, and schema.org markup
- ♿ **Accessible**: WCAG compliant with proper focus states and ARIA labels

## Sections

1. **Hero**: Name, title, location, and call-to-action buttons
2. **About**: Professional summary and background
3. **Featured Work**: Highlighted thesis and recent work at Hypertype
4. **Experience**: Timeline of professional experience
5. **Education**: Academic background and achievements
6. **Skills**: Technical and soft skills organized by category
7. **Projects**: Portfolio of key projects and contributions
8. **Awards**: Recognition and achievements
9. **Contact**: Contact information and form

## Technology Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **Vanilla JavaScript**: No frameworks - pure ES6+ for better performance
- **Font Awesome**: Icons for visual enhancement
- **Google Fonts**: Inter font family for modern typography

## Setup and Deployment

### GitHub Pages Deployment

1. **Fork or Clone** this repository
2. **Replace Content**: Update the content in `index.html` with your information
3. **Add Resume**: Replace `resume.pdf` with your actual resume
4. **Commit Changes**: Push your changes to the main branch
5. **Enable GitHub Pages**: Go to repository Settings > Pages > Deploy from main branch
6. **Access Your Site**: Visit `https://yourusername.github.io/repository-name`

### Local Development

```bash
# Clone the repository
git clone https://github.com/koczka990/website-personal.git

# Navigate to the project directory
cd website-personal

# Open with a local server (recommended)
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Or simply open index.html in your browser
```

### Customization

#### Content Updates
- Edit `index.html` to update personal information, experience, and projects
- All content is easily editable in the HTML file

#### Styling Changes
- Modify `styles.css` to adjust colors, fonts, or layout
- CSS custom properties (variables) make theming easy
- Responsive breakpoints can be adjusted for different devices

#### Color Scheme
The website uses CSS custom properties for easy color customization:

```css
:root {
    --accent-primary: #3b82f6;     /* Primary blue */
    --accent-secondary: #10b981;   /* Secondary green */
    --bg-primary: #ffffff;         /* Main background */
    --text-primary: #1a1a1a;       /* Main text */
    /* ... more variables */
}
```

#### Resume Replacement
1. Create a PDF version of your resume
2. Name it `resume.pdf`
3. Replace the placeholder file
4. Ensure the file size is reasonable for web download

## Performance Optimization

- **Minification**: Consider minifying CSS and JS for production
- **Image Optimization**: Compress any images you add
- **CDN**: Font Awesome and Google Fonts are loaded from CDN
- **Lazy Loading**: Built-in support for lazy loading images
- **Efficient Animations**: Hardware-accelerated animations using transform and opacity

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Features

- Meta description and keywords
- Open Graph tags for social media sharing
- Schema.org structured data for search engines
- Semantic HTML for better search indexing
- Fast loading for improved search rankings

## Accessibility Features

- Semantic HTML structure
- ARIA labels and descriptions
- Keyboard navigation support
- High contrast ratios
- Focus indicators
- Screen reader compatible

## Contact Form

The contact form uses a static-friendly approach:
- Submits via `mailto:` link
- No server-side processing required
- Perfect for GitHub Pages hosting
- Pre-fills email client with form data

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: koczka990@gmail.com
- **GitHub**: [github.com/koczka990](https://github.com/koczka990)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/vencel-d%C3%A1vid-koczka-2aab8425a)

---

Built with ❤️ using modern web technologies and best practices.