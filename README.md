# ALX Intermediate Frontend

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/reuben-idan/alx-intermediate-frontend)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

## Overview

This repository contains the ALX Intermediate Frontend curriculum projects, focusing on modern web development practices, semantic HTML, accessibility, responsive design principles, and Tailwind CSS implementation.

## Project Structure

```
alx-intermediate-frontend/
├── 0x00-semantic_html/
│   ├── 0-index.html          # Basic semantic HTML structure
│   ├── 1-index.html          # Enhanced with SEO meta tags
│   ├── 2-index.html          # Blog post layout with semantic elements
│   └── 3-index.html          # Accessible form with ARIA attributes
├── 0x02-tailwind-css/
│   ├── src/
│   │   ├── input.css         # Tailwind directives and custom styles
│   │   ├── output.css        # Generated Tailwind CSS
│   │   └── test.html         # Test file for Tailwind setup
│   ├── tailwind.config.js    # Tailwind configuration
│   ├── package.json          # Node.js dependencies
│   ├── 1-index.html          # Responsive CSS Grid layout
│   ├── 2-index.html          # Complex nested CSS Grid layout
│   ├── 3-nav_index.html      # Flexbox navigation bar
│   ├── 4-flexbox_index.html  # Responsive Flexbox layout with CDN
│   ├── 5-gridflex_index.html # Combined Grid and Flexbox layout
│   └── 6-imageGallery.html   # Responsive image gallery with CSS Grid
└── README.md
```

## Learning Objectives

### 0x00 - Semantic HTML

**Objective**: Master semantic HTML elements and accessibility best practices

#### Exercise 0: Creating a Structured HTML Document

- **File**: `0-index.html`
- **Focus**: Basic semantic structure with header, nav, main, article, section, and footer
- **Key Concepts**: DOCTYPE declaration, semantic elements, proper HTML structure

#### Exercise 1: Enhancing HTML with Meta Tags

- **File**: `1-index.html`
- **Focus**: SEO optimization and accessibility improvements
- **Key Concepts**: Meta tags, character encoding, viewport settings, SEO best practices

#### Exercise 2: Blog Post Layout

- **File**: `2-index.html`
- **Focus**: Complete blog post structure with semantic elements
- **Key Concepts**: Article structure, heading hierarchy, time elements, figure and figcaption

#### Exercise 3: Form Accessibility

- **File**: `3-index.html`
- **Focus**: ARIA roles and attributes for enhanced accessibility
- **Key Concepts**: Form accessibility, ARIA labels, required fields, screen reader support

### 0x02 - Tailwind CSS

**Objective**: Master Tailwind CSS utility-first framework and responsive design

#### Exercise 1: Responsive CSS Grid Layout

- **File**: `1-index.html`
- **Focus**: 3-column grid layout with responsive breakpoints
- **Key Concepts**: CSS Grid, responsive design, Tailwind utility classes

#### Exercise 2: Complex Nested CSS Grid Layout

- **File**: `2-index.html`
- **Focus**: Multi-section layout with nested grids and color gradients
- **Key Concepts**: Nested grids, color utilities, layout composition

#### Exercise 3: Flexbox Navigation Bar

- **File**: `3-nav_index.html`
- **Focus**: Responsive horizontal navigation with hover effects
- **Key Concepts**: Flexbox, responsive navigation, hover states

#### Exercise 4: Responsive Flexbox Layout

- **File**: `4-flexbox_index.html`
- **Focus**: Sidebar and content layout using Flexbox and Tailwind CDN
- **Key Concepts**: Flexbox, Tailwind CDN, responsive breakpoints

#### Exercise 5: Combined Grid and Flexbox Layout

- **File**: `5-gridflex_index.html`
- **Focus**: Multi-section layout combining CSS Grid and Flexbox
- **Key Concepts**: Grid + Flexbox integration, responsive design, layout composition

#### Exercise 6: Responsive Image Gallery

- **File**: `6-imageGallery.html`
- **Focus**: Image gallery with CSS Grid and responsive images
- **Key Concepts**: Image galleries, responsive images, CSS Grid, object-fit

## Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Styling and responsive design
- **Tailwind CSS**: Utility-first CSS framework
- **CSS Grid**: Modern layout system
- **Flexbox**: Flexible box layout model
- **JavaScript**: Interactive functionality (upcoming)
- **ARIA**: Web accessibility standards
- **Git**: Version control and collaboration

## Key Features

### Semantic HTML & Accessibility

- Semantic HTML structure for screen readers
- ARIA roles and attributes for enhanced accessibility
- Proper heading hierarchy (H1 → H2 → H3)
- Form labels and required field indicators
- Alt text for images and descriptive captions
- Keyboard navigation support

### Responsive Design

- Mobile-first responsive layouts
- CSS Grid and Flexbox integration
- Responsive image galleries
- Adaptive navigation systems
- Breakpoint-based design systems

### Tailwind CSS Implementation

- Utility-first CSS approach
- Responsive utility classes
- Custom configuration setup
- CDN and build process integration
- Component-based styling

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, Atom)
- Node.js and npm (for Tailwind CSS projects)
- Git for version control

### Installation

```bash
# Clone the repository
git clone https://github.com/reuben-idan/alx-intermediate-frontend.git

# Navigate to the project directory
cd alx-intermediate-frontend

# For Tailwind CSS projects
cd 0x02-tailwind-css
npm install

# Open files in your preferred editor
code .
```

### Running the Projects

#### Semantic HTML Projects

1. Open any HTML file in `0x00-semantic_html/` in your web browser
2. Use browser developer tools to inspect the semantic structure
3. Test accessibility with screen reader software
4. Validate HTML using W3C Validator

#### Tailwind CSS Projects

1. Open any HTML file in `0x02-tailwind-css/` in your web browser
2. For local Tailwind builds, run: `npx tailwindcss -i ./src/input.css -o ./src/output.css --watch`
3. Test responsive design across different screen sizes
4. Inspect utility classes in browser developer tools

## Development Guidelines

### Code Standards

- Use semantic HTML elements appropriately
- Ensure proper indentation and formatting
- Include meaningful alt text for images
- Implement ARIA attributes where necessary
- Follow accessibility guidelines (WCAG 2.1)
- Use Tailwind utility classes consistently
- Maintain responsive design principles

### Best Practices

- Validate HTML markup regularly
- Test with multiple browsers and devices
- Use semantic elements for structure
- Implement responsive design principles
- Prioritize accessibility in all implementations
- Optimize Tailwind CSS builds for production
- Follow mobile-first design approach

## Project Status

| Exercise                 | Status    | Completion Date |
| ------------------------ | --------- | --------------- |
| **0x00 - Semantic HTML** |           |                 |
| 0-index.html             | Completed | 2024            |
| 1-index.html             | Completed | 2024            |
| 2-index.html             | Completed | 2024            |
| 3-index.html             | Completed | 2024            |
| **0x02 - Tailwind CSS**  |           |                 |
| 1-index.html             | Completed | 2024            |
| 2-index.html             | Completed | 2024            |
| 3-nav_index.html         | Completed | 2024            |
| 4-flexbox_index.html     | Completed | 2024            |
| 5-gridflex_index.html    | Completed | 2024            |
| 6-imageGallery.html      | Completed | 2024            |

## Contributing

This is a learning project for ALX Software Engineering program. Contributions are welcome for educational purposes and improvements.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## Resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/)
- [W3C HTML Specification](https://www.w3.org/TR/html52/)
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [CSS Grid Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [Flexbox Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Reuben Idan**

- GitHub: [@reuben-idan](https://github.com/reuben-idan)
- ALX Software Engineering Student

---

_This project is part of the ALX Software Engineering curriculum, focusing on intermediate frontend development concepts and best practices including semantic HTML, accessibility, responsive design, and modern CSS frameworks._
