# Personal Website

A clean, modern, and responsive personal website built from scratch without any CMS. Features three main sections: Personal Information, Professional Experience, and Blog.

## Features

- **Personal Information Section**: Introduction, bio, and contact information
- **Professional Experience Section**: Work experience, skills, and education
- **Blog Section**: Blog posts with a clean card layout
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Sticky header with smooth scrolling to sections
- **Mobile Menu**: Hamburger menu for mobile devices
- **Modern Styling**: Clean and professional design with CSS animations
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks or libraries needed

## Getting Started

### View Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/slashome/website.git
   cd website
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

### Customization

#### Personal Information
Edit `index.html` to update:
- Your name (line 33)
- Introduction text (lines 34-40)
- Contact information (lines 44-47)
- Email, location, social links

#### Professional Experience
Update in `index.html`:
- Work experience entries (lines 60-82)
- Skills (lines 86-109)
- Education (lines 113-123)

#### Blog Posts
Add or modify blog posts in the blog section (lines 134-179):
- Date
- Title
- Excerpt
- Link to full post

#### Styling
Customize colors and styling in `styles.css`:
- Color scheme (CSS variables in `:root`, lines 8-15)
- Fonts (line 18)
- Layout and spacing

#### Logo and Branding
- Update the logo text in `index.html` (line 15)
- Customize colors in `styles.css` (`:root` section)

## File Structure

```
website/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Navigation and interactive features
├── .gitignore      # Git ignore file
├── LICENSE         # GPL-3.0 License
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork this repository and customize it for your own use!
