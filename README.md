# Portfolio

My professional portfolio website - Project Coordinator & Creative Developer showcasing projects, skills, and social links.

## Features

✨ **Modern Design**
- Beautiful purple gradient background
- Responsive grid layout with 6 interactive link cards
- Smooth animations and hover effects
- Fully mobile-responsive design
- Professional typography and spacing

🎯 **Interactive Elements**
- GitHub profile link
- Twitter/X profile link
- LinkedIn profile link
- CV download
- Source code link
- Contact/Email link

🎬 **Animations**
- Fade-in animations on page load
- Hover effects with scale and lift animations
- Color gradient transitions on hover
- Icon scaling effects

## Quick Start

### 1. Customize Content
Edit `index.html` and replace:
- `YOUR NAME` with your actual name
- `yourusername` with your GitHub username
- `your.email@example.com` with your email
- Update all social media links with your profiles

### 2. View Locally
Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server
```

Then visit `http://localhost:8000`

### 3. Deploy to GitHub Pages

If this is your user portfolio:
- Ensure repository is named `yourusername.github.io`
- Push to `main` branch
- Your site will be live at `https://yourusername.github.io`

For a project portfolio:
- Go to Settings → Pages
- Select `main` branch as source
- Your site will be live at `https://yourusername.github.io/portfolio`

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── style.css       # Styling and animations
└── README.md       # This file
```

## Customization

### Change Colors
Edit the gradient in `style.css` line 12:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add More Links
Add new link items in `index.html` within `.links-grid`:
```html
<a href="your-link" target="_blank" class="link-item">
    <div class="icon">🎯</div>
    <span>Your Label</span>
</a>
```

### Adjust Layout
Modify grid columns in `style.css` line 68:
```css
grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Responsive Design

## License

Free to use and modify for personal portfolio purposes.

## Created with ❤️

Inspired by modern portfolio design. Built with passion for clean, responsive web design.
