# dc995.github.io

The home of things David Crawford

## Overview

This is a personal GitHub Pages website for David Crawford, hosted at [https://dc995.github.io](https://dc995.github.io). The site serves as a central hub for projects, portfolio work, and personal content.

## Project Structure

```
dc995.github.io/
├── index.html          # Main landing page with HTML structure and inline CSS
├── README.md           # Project documentation (this file)
└── LICENSE             # MIT License file
```

## Features

- **Responsive Design**: Mobile-first approach with viewport meta tags
- **Modern Styling**: Clean, minimalist design with card-based layout
- **SEO Optimized**: Includes meta tags for search engines and social sharing
- **Semantic HTML**: Uses proper HTML5 semantic elements for accessibility

## Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with flexbox for layout
- **GitHub Pages**: Static site hosting

## Development

### Local Development

To view the site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/dc995/dc995.github.io.git
   cd dc995.github.io
   ```

2. Open `index.html` in your web browser:
   ```bash
   open index.html  # macOS
   xdg-open index.html  # Linux
   start index.html  # Windows
   ```

Alternatively, use a local web server:
```bash
python -m http.server 8000
# Visit http://localhost:8000
```

### Making Changes

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes to the HTML/CSS files

3. Test your changes locally in multiple browsers

4. Commit and push:
   ```bash
   git add .
   git commit -m "Description of your changes"
   git push origin feature/your-feature-name
   ```

5. Create a pull request or merge to main branch

### Deployment

GitHub Pages automatically deploys the site when changes are pushed to the main branch. Changes typically appear within a few minutes.

## Code Documentation

### index.html Structure

The main HTML file includes:
- **DOCTYPE declaration**: HTML5 document type
- **Head section**: Contains meta tags, title, and inline CSS
- **Body section**: Main content container with semantic elements
- **Styling**: Inline CSS with comments explaining each rule

Key sections:
- **Meta tags** (lines 10-17): SEO and responsive design configuration
- **CSS Reset** (lines 24-29): Browser consistency
- **Layout Styles** (lines 31-52): Flexbox-based centering
- **Main Content** (lines 77-93): Semantic HTML structure

## Browser Support

This site supports all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2019-2025 David Crawford

## Contact

For questions or suggestions, please open an issue in the GitHub repository.

## Future Enhancements

Potential improvements for this site:
- [ ] Add portfolio section with project showcases
- [ ] Implement blog functionality
- [ ] Add contact form
- [ ] Include social media links
- [ ] Add dark mode toggle
- [ ] Implement custom domain
- [ ] Add Google Analytics or privacy-focused analytics

## Acknowledgments

Built with GitHub Pages and deployed automatically through GitHub Actions.
