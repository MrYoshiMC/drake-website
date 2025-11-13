# Drake Website

A modern, responsive website dedicated to Drake's music and discography.

## About

This website showcases Drake's albums, biography, and music career. Built with vanilla HTML, CSS, and a clean, minimalist design philosophy.

## Features

- Interactive album grid showcasing Drake's complete discography
- Individual album pages with cover art and details
- Integrated Spotify player for desktop users
- Fully responsive design optimized for mobile, tablet, and desktop
- Custom typography with web fonts
- Smooth hover animations and transitions

## Technologies

- HTML5
- CSS3 (Flexbox & Grid)
- Custom Web Fonts
- Spotify Embed API

## Project Structure

```
drake-website/
├── index.html          # Homepage
├── albums.html         # Album grid page
├── about.html          # About Drake
├── styles.css          # Global styles
├── albums/             # Individual album pages
│   ├── sofargone.html
│   ├── takecare.html
│   └── ...
├── pictures/
│   ├── albums/         # Album cover images
│   └── textures/       # Background textures
└── fonts/              # Custom web fonts
```

## Live Demo

Visit the live site: [https://mryoshimc.github.io/drake-website/](https://mryoshimc.github.io/drake-website/)

## Local Development

### Prerequisites

- A modern web browser
- A local web server (optional but recommended)

### Setup

1. Clone the repository

```bash
git clone https://github.com/MrYoshiMC/drake-website.git
cd drake-website
```

2. Start a local server

Using Python:
```bash
python -m http.server 8000
```

Using Node.js:
```bash
npx serve
```

3. Open your browser and navigate to `http://localhost:8000`

## Design Specifications

### Responsive Breakpoints

- **Desktop**: > 1024px (includes Spotify sidebar)
- **Tablet**: 481px - 1024px
- **Mobile**: ≤ 480px

### Color Palette

| Element | Color Code |
|---------|-----------|
| Background | `#ede6d6` |
| Text | `#484848` |
| Cards | `#ffffff` |
| Header/Footer | `#333333` |

