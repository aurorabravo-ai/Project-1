# Personal Website

A modern, responsive personal portfolio website that you can customize to showcase your work, skills, and experience.

## Features

✨ **Modern Design**
- Clean, professional aesthetic with gradient accents
- Fully responsive layout (mobile, tablet, desktop)
- Smooth animations and transitions
- Dark and light mode compatible

📱 **Sections**
- **Home/Hero** - Eye-catching introduction with your name and title
- **About** - Personal bio and key statistics
- **Skills** - Organized by categories (Frontend, Backend, Tools)
- **Portfolio** - Showcase your projects with images and descriptions
- **Contact** - Contact form and social media links
- **Navigation** - Sticky navbar with smooth scrolling

⚡ **Interactive Features**
- Smooth scroll navigation
- Form validation and submission
- Scroll animations for elements
- Active navigation highlighting
- Success notifications

## File Structure

```
Project-1/
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── script.js       # JavaScript interactivity
└── README.md       # This file
```

## How to Customize

### 1. **Personal Information**
Edit `index.html` and replace:
- `Your Name` - Change in navbar logo and hero section
- `Full Stack Developer | Designer | Creative Thinker` - Update your title
- About section text with your own bio
- Stats (Years Experience, Projects, etc.) with your numbers

### 2. **Add Your Projects**
In the Portfolio section, update:
- Project titles
- Project descriptions
- Replace placeholder images with real project screenshots
- Update project links

### 3. **Update Skills**
Modify the skill cards to match your expertise:
- Change skill names
- Reorganize categories as needed
- Add/remove skills to fit your profile

### 4. **Social Links**
In the Contact section, add your:
- GitHub profile URL
- LinkedIn profile URL
- Twitter/X profile URL
- Email address

### 5. **Color Scheme**
Customize colors in `styles.css` by modifying the CSS variables at the top:

```css
:root {
    --primary-color: #6366f1;      /* Purple/Indigo */
    --secondary-color: #ec4899;    /* Pink */
    --text-dark: #1f2937;          /* Dark gray */
    --text-light: #6b7280;         /* Light gray */
    --bg-light: #f9fafb;           /* Light background */
    --bg-white: #ffffff;           /* White */
}
```

## Getting Started

1. **Open the website:**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```

2. **Start customizing:**
   - Edit the text, images, and links
   - Update colors and styling in `styles.css`
   - Add more interactivity with `script.js`

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

You can deploy this website to:
- **GitHub Pages** - Free hosting
- **Netlify** - Drag and drop deployment
- **Vercel** - Optimized for static sites
- **Traditional hosting** - Any web host

Simply upload all files to your hosting provider!

## Tips for Best Results

1. **Replace placeholder images** with real project screenshots
2. **Keep content concise** - visitors scan rather than read
3. **Update regularly** - keep portfolio current with new projects
4. **Add real links** - make sure social and project links work
5. **Test on mobile** - ensure everything looks good on phones/tablets
6. **Optimize images** - compress images for faster loading

## Customization Examples

### Change Hero Section Color
Edit in `styles.css`:
```css
.hero {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
}
```

### Add More Portfolio Projects
Copy a `portfolio-card` div in `index.html` and update the content.

### Modify Animations
Adjust animation timing and effects in `styles.css` by changing the `--transition` variable and keyframe animations.

## License

This template is free to use and modify for your personal portfolio.

---

**Ready to share your portfolio?** Customize it, deploy it, and start showcasing your work! 🚀
