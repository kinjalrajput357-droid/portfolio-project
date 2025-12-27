# Simple Portfolio Website

A clean, modern portfolio website built with pure HTML, CSS, and JavaScript. No frameworks or dependencies required.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme** - Modern dark color scheme with blue accents
- **Smooth Animations** - Fade-in effects and smooth scrolling between sections
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Interactive Projects** - Hover effects and project showcases
- **Contact Form** - Built-in contact form with validation
- **Skills Display** - Organized frontend and backend skill tags
- **Social Links** - Quick access to your social media profiles

## Sections

1. **Home/Hero** - Eye-catching introduction with call-to-action buttons
2. **About** - Personal background and experience
3. **Projects** - Showcase of your best work with descriptions and links
4. **Skills** - Frontend and backend technologies you work with
5. **Contact** - Contact form and social media links

## Getting Started

1. Download or clone this repository
2. Open `index.html` in your web browser
3. That's it! No build process or installation required

## Customization

### Personal Information

Edit the following sections in `index.html`:

- **Navigation Brand** (line ~15): Change "Your Name" to your actual name
- **Hero Section** (line ~30): Update your name and title
- **About Section** (line ~45): Add your bio and experience
- **Projects Section** (line ~60): Replace with your actual projects
- **Skills Section** (line ~95): Add/remove skills as needed
- **Contact Section** (line ~120): Update email and social links

### Colors

Customize the color scheme in the `:root` section of the `<style>` tag:

```css
:root {
  --bg-primary: #0a0e27;
  --bg-secondary: #151935;
  --accent: #3b82f6;
  --text-primary: #ffffff;
  --text-secondary: #94a3b8;
}
```

### Images

Replace placeholder images with your own:

- Project images: Update `src` attributes in project cards
- Add your profile picture in the About section if desired

### Form Handling

The contact form currently shows an alert on submission. To make it functional:

1. Set up a backend endpoint (e.g., using FormSpree, Netlify Forms, or your own server)
2. Update the form submission handler in the `<script>` section
3. Change the `fetch` URL to your endpoint

Example with FormSpree:

```javascript
fetch('https://formspree.io/f/YOUR_FORM_ID', {
  method: 'POST',
  body: formData,
  headers: {
    'Accept': 'application/json'
  }
})
```

## Deployment

### GitHub Pages

1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings → Pages
4. Select your branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a generated URL
3. Optional: Connect to GitHub for automatic deployments

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Free to use for personal and commercial projects.

## Credits

Created with HTML, CSS, and vanilla JavaScript. No frameworks required.
