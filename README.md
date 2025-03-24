# Personal Portfolio Website

A modern, responsive portfolio website showcasing professional experience, projects, and skills. Built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all devices
- Clean and modern UI
- Dynamic content loading from JSON
- Progressive Web App (PWA) support
- SEO optimized
- Social media integration
- Project showcase
- Resume download option
- Automated HTML generation from JSON

## Project Structure

```
.
├── index.html              # Main portfolio page (generated)
├── resume.html            # Resume page (generated)
├── portfolio.json         # Content configuration
├── generate_portfolio.py  # HTML generation script
├── css/                   # Stylesheets
├── js/                    # JavaScript files
├── img/                   # Images and icons
├── portfolio_media/       # Project media files
└── site.webmanifest      # PWA configuration
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/sanketchavan08/sanketchavan08.github.io.git
```

2. Navigate to the project directory:
```bash
cd sanketchavan08.github.io
```

3. Install Python dependencies:
```bash
pip install -r requirements.txt
```

4. Generate HTML files:
```bash
python generate_portfolio.py
```

5. Open `index.html` in your browser or use a local server.

## Customization

### Profile Information
Edit `portfolio.json` to update:
- Personal information
- Work experience
- Projects
- Skills
- Education
- Social links

After making changes to `portfolio.json`, you must regenerate the HTML files:
```bash
python generate_portfolio.py
```

### Styling
- Main styles are in `css/main.css`
- Modern normalize styles in `css/modern_normalize.css`
- HTML5 boilerplate styles in `css/html5bp.css`

### Images
- Profile picture: Replace `img/1742631126842.jpeg`
- Favicon: Replace `1742631126842.ico`
- Project images: Add to `portfolio_media/` directory

## Development

### Local Development
1. Install Python (if not already installed)
2. Run a local server:
```bash
python -m http.server 8000
```
3. Open `http://localhost:8000` in your browser

### Workflow
1. Make changes to `portfolio.json`
2. Run `python generate_portfolio.py` to update HTML files
3. Test changes locally
4. Commit and push changes

### Adding New Projects
1. Add project images to `portfolio_media/`
2. Update project information in `portfolio.json`
3. Run `python generate_portfolio.py` to update HTML files
4. Follow the existing JSON structure for consistency

## Deployment

This project is configured for GitHub Pages deployment. Simply push to the main branch to update the live site.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Sanket Chavan
- LinkedIn: [sanketchavan08](https://www.linkedin.com/in/sanketchavan08/)
- GitHub: [sanketchavan08](https://github.com/sanketchavan08)
- Email: chavansanket193@gmail.com 