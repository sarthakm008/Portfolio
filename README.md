# Sarthak Madaan Comics

A playful comic-book styled personal portfolio site for Sarthak Madaan. The page introduces the creator, highlights featured project slots, and includes a contact call-to-action that opens Gmail compose in a new tab.

## Overview

This is a lightweight static website built with plain HTML and CSS. It does not require a build step, package manager, or backend server.

## Files

- `index.html` - Main page structure and content.
- `styles.css` - Visual styling, responsive layout, colors, typography, and hover states.

## Features

- Comic-inspired cover panel layout
- Responsive grid for mobile and desktop screens
- Google Fonts integration
- Featured work section with project cards
- Contact section with Gmail compose call-to-action
- Reduced-motion media query for accessibility

## Customization

Update the placeholder project names and descriptions in `index.html`:

- `Project Aurora`
- `Project Nova`

Replace the contact email in the Gmail compose link with your real email address:

```html
<a href="https://mail.google.com/mail/?view=cm&fs=1&to=you@example.com" class="cta-button" target="_blank" rel="noopener noreferrer">SAY HI</a>
```

Most of the theme can be adjusted from the CSS variables at the top of `styles.css`.

## Notes

The site currently uses external Google Fonts, so an internet connection is needed for the intended typography to load.
