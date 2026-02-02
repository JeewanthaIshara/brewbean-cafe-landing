# Brew Haven - Coffee Shop Landing Page

A modern, responsive landing page for Brew Haven coffee shop built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Dynamic Navigation**: Smooth navigation with mobile menu toggle functionality
- **Modern UI**: Clean and elegant design with a coffee shop aesthetic
- **Sections Included**:
  - Hero section with call-to-action
  - About Us section
  - Menu showcase
  - Operating Hours
  - Location information
  - Contact section
  - Footer with quick links

## Project Structure

```
cafe-landing/
├── index.html      # Main HTML file
├── script.js       # JavaScript functionality
├── style.css       # Styling and theme
footer.html         # Footer component
nav.html            # Navigation component
README.md           # This file
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/brew-haven-landing.git
   cd brew-haven-landing
   ```

2. Open the project in your browser:
   - Simply open `cafe-landing/index.html` in your web browser
   - Or use a local server like Live Server extension in VS Code

## Usage

The landing page includes:

- **Navigation Bar**: Easy navigation between different sections
- **Mobile Menu**: Toggle button for mobile navigation
- **Smooth Scrolling**: Click on navigation links to smoothly scroll to sections
- **Responsive Images**: Coffee shop imagery and branding

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS variables for theming
- **JavaScript**: Dynamic component loading and interactivity
- **Font Awesome**: Icons for navigation and branding
- **Responsive Design**: Mobile-first approach with media queries

## Features Highlighted

### Modular Components
Navigation and footer are loaded dynamically to maintain clean code structure:
```javascript
fetch('nav.html')
    .then(response => response.text())
    .then(data => {
        document.getElementById('nav-placeholder').innerHTML = data;
    });
```

### CSS Variables
Consistent theming using CSS custom properties:
```css
:root {
    --primary-color: #6f4e37;
    --secondary-color: #d4a574;
}
```

## Customization

To customize the landing page:

1. **Update Colors**: Modify CSS variables in `style.css`
2. **Change Content**: Edit text and sections in `index.html`
3. **Add Images**: Replace image paths with your own coffee shop photos
4. **Modify Navigation**: Update links in `nav.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- [ ] Add menu item database with filtering
- [ ] Implement online ordering system
- [ ] Add email notification system
- [ ] Create admin dashboard for content management
- [ ] Add animations and transitions
- [ ] Implement SEO optimization

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created for Brew Haven Coffee Shop

## Contact

For questions or feedback, please open an issue or contact us through the website.

---

**Happy brewing!** ☕
