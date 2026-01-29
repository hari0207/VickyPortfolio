# Gym Trainer Portfolio Website

A modern, responsive portfolio website for a gym trainer showcasing services, client transformations, and training programs.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Three Main Pages**: Home, About, and Training Programmes
- **Smooth Scrolling**: Enhanced user experience with smooth scroll animations
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Google Form Integration**: All "Enquire Now" buttons link to your Google Form
- **Client Showcase**: Display transformation photos and client testimonials
- **Modern UI**: Professional design with clean aesthetics

## File Structure

```
portfolio/
├── index.html              # Home page with all sections
├── about.html              # About page
├── training.html           # Training Programmes page
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── main.js            # JavaScript for interactivity
├── images/                 # Image assets
│   ├── logo.png
│   ├── training.jpg
│   ├── trainer-photo.jpg
│   └── transformations/   # Client transformation photos
└── README.md              # This file
```

## Setup Instructions

1. **Add Your Images**
   - Add your logo to `images/logo.png`
   - Add training image to `images/training.jpg`
   - Add your photo to `images/trainer-photo.jpg`
   - Add client transformation photos to `images/transformations/`
   - See `images/README.md` for detailed image requirements

2. **Update Google Form Links**
   - Open all HTML files (`index.html`, `about.html`, `training.html`)
   - Find all instances of `https://forms.google.com/YOUR_FORM_LINK`
   - Replace `YOUR_FORM_LINK` with your actual Google Form URL

3. **Customize Content**
   - Edit the text content in each HTML file to match your information
   - Update trainer name, experience, certifications, etc.
   - Modify program descriptions to match your services
   - Add/remove client testimonials as needed

4. **Test the Website**
   - Open `index.html` in a web browser
   - Test all navigation links
   - Verify all "Enquire Now" buttons link to your Google Form
   - Test on mobile devices or use browser dev tools

## Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #ff6b35;    /* Main accent color */
    --secondary-color: #1a1a1a;   /* Dark background */
    --accent-color: #4ecdc4;      /* Secondary accent */
}
```

### Adding More Sections
To add more transformation cards or program cards, copy the existing HTML structure and modify the content.

### Adding More Pages
1. Create a new HTML file
2. Copy the navigation structure from existing pages
3. Update the active link in the navigation
4. Add your content

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All images should be optimized for web to ensure fast loading
- Replace placeholder text with your actual content
- Test all Google Form links before going live
- Consider adding analytics tracking if needed

## Support

For questions or customization help, refer to the code comments in the HTML, CSS, and JavaScript files.
