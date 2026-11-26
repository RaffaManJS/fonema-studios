🇬🇧 English | 🇮🇹 [Italiano](README.it.md)

## Build the CSS

Install the dependencies once, then compile `input.css` into the minified `output.css`:

```bash
npm install
npm run build
```


# Fonema Studios

A demo website for a fictional recording studio, built with HTML and Tailwind CSS as a portfolio project.

> **Note:** Fonema Studios is not a real business. The address, phone number and other contact details are placeholders, and the photos come from [Unsplash](https://unsplash.com).

## Pages

- **Home**: studio name in the hero, a slowly rotating vinyl record (SVG), an audio player with tracks, and a closing call to action before the footer
- **Services**: recording, rehearsal room, mixing and mastering, production (rock and rap beats) and a full package available on quote
- **Gallery**: 12 photos grouped in 4 categories
- **Contacts**: how to reach the studio (placeholder details) and FAQ section.

## Technologies

- HTML5
- Tailwind CSS (installed with npm, compiled and minified)
- CSS variables for the colour palette
- Self-hosted fonts: Shrikhand (titles and logo) and DM Sans
- Inline SVG graphics

## Features

- **Vintage light palette** defined with CSS variables (cream `#F3EAD8`, brown `#4A2E1B`, terracotta `#A3472A`), so colours can be changed from a single place
- **Responsive images**: the gallery photos are served with `srcset` in four sizes (1200, 800, 600 and 400 px), so each device downloads only what it needs
- **Self-hosted fonts**: the site makes no requests to external font servers
- **Performance**: Lighthouse score above 97 on every page

## Project structure

- `assets/`: images and other static files
- `input.css`: Tailwind source file
- `output.css`: compiled and minified CSS used by the pages
- `fonts.css`: declarations of the self-hosted fonts
- `package.json` and `package-lock.json`: npm configuration and exact dependency versions

`node_modules/` is not included in the repository; it can be recreated with `npm install`.

## Credits

Built by Raff as part of a junior web developer portfolio. Photos by Unsplash contributors, used under the [Unsplash License](https://unsplash.com/license).
