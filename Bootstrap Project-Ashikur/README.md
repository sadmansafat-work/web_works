# Ashikur Portfolio

Static portfolio website: HTML and CSS only, no JavaScript.

## Structure
```
index.html      Home
about.html      About
projects.html   Projects (CSS-only category filter)
blog.html       Blog
contact.html    Contact
css/style.css   The single stylesheet (tokens, base, components, pages, responsive)
images/         icons/ (SVG), decor/, photos/, projects/, blog/
```

## Notes
- Fonts: Poppins and PT Sans via Google Fonts (needs an internet connection).
- Icons, logos and decorations are vector SVGs exported from the Figma/PDF design; photos are WebP.
- Interactive parts are pure CSS: the Skills/Education tabs (radio inputs + `:checked`),
  the project filter (radio inputs + sibling selectors) and the mobile menu (checkbox).
- Forms open the visitor's mail client (`mailto:`) because there is no back end.
- Colours, spacing and breakpoints are defined as CSS variables at the top of `style.css`.
