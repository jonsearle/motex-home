# MOTEX Landing Page

A single-page landing site for MOTEX, a service offering modern tools for garages.

## Project Structure

```
motex-home/
├── index.html          # Main HTML structure
├── design-theme.css    # Design system with CSS custom properties
├── styles.css          # Component styles using design theme
├── assets/             # Logo files and other assets
└── README.md           # This file
```

## Design System

The design uses a comprehensive theme system defined in `design-theme.css` with CSS custom properties for:

- **Colors**: Charcoal background (#111827), white text, orange CTA buttons (#F97316)
- **Typography**: Inter font family with specified sizes and weights
- **Spacing**: Consistent spacing system using CSS variables
- **Components**: Reusable component tokens for buttons, borders, etc.

## Features

- Fully responsive design (mobile-first approach)
- Clean, modern UI matching the MOTEX brand
- Accessible button states and touch-friendly targets
- Semantic HTML structure

## Setup

1. Place logo files in the `assets/` directory
2. Update logo references in `index.html` if using image files instead of text-based logo
3. Open `index.html` in a web browser

## CTA Buttons

The "Start Your 30-Day Free Trial" buttons are configured to open an email client with a pre-filled subject line to `jon.searle@gmail.com`.

## Browser Support

Modern browsers with CSS custom properties support (all current browsers).

## Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Customization

All design tokens can be modified in `design-theme.css` by updating the CSS custom properties. The responsive typography and spacing adjustments are also defined there.

