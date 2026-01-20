# FinaMo — Financial Momentum for MSMEs

A modern, professional website for FinaMo, providing affordable, tech-enabled accounting and financial management services for Nigerian MSMEs.

## Features

- **Responsive Design** - Mobile-first approach with clean UI
- **Service Showcase** - Detailed pricing, services, and solutions
- **Contact Form** - Web3Forms integration for inquiries
- **FAQ Chatbot** - Interactive chatbot with common questions
- **Partner Logos** - Rotating marquee of consulting partners
- **Modern Styling** - Green and gold color scheme with smooth animations

## Project Structure

```
finamo/
├── index.html          # Main website file
├── script.js           # JavaScript for interactive features
├── assets/             # Images and logos
│   ├── Logo22.jfif
│   ├── FCMB.jfif
│   ├── NASSI.jfif
│   └── BMO.png
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── CNAME              # Custom domain for GitHub Pages
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/finamo.git
cd finamo
```

2. Open `index.html` in your browser or deploy using GitHub Pages

## Deployment

### GitHub Pages
1. Push the repository to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Custom domain: finamo.biz (if configured)

### Local Server
```bash
python -m http.server 8000
# Visit http://localhost:8000
```

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Web3Forms API
- Google Fonts (Inter)

## Features

### Contact Form
Uses Web3Forms for email delivery without server-side code.

### Interactive Chatbot
FAQ system with 4 pre-loaded questions and intelligent query matching.

### Mobile Responsive
Fully responsive design with hamburger navigation for mobile devices.

## Customization

- **Colors**: Edit CSS variables in `:root` section of `index.html`
- **Content**: Update text directly in HTML sections
- **Form Email**: Change `access_key` in the contact form for Web3Forms
- **Images**: Replace asset files in the `assets/` folder

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

All rights reserved © FinaMo 2024

## Contact

Visit [www.finamo.biz](https://www.finamo.biz) for more information.