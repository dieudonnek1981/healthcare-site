# WeHelp Home Health Care Services Website

This is the codebase for the WeHelp Home Care Services website, a static site designed to provide information about the business and generate leads through local search engine optimization (SEO).

## Project Purpose

The primary goal of this website is to establish an online presence for WeHelp Home Health Care Services, inform potential clients about the available in-home care services, and improve visibility in local search results to generate business leads.

## Technology Stack

- **HTML5:** Provides the structure and content of the web pages.
- **CSS3 (with Tailwind CSS):** Handles the styling and layout using the utility-first framework Tailwind CSS.
- **JavaScript:** Used for basic client-side interactivity (e.g., mobile menu toggle, scroll animations).
- **Cloudflare Pages:** Used for hosting and automatic deployment directly from the GitHub repository.

## Features and Optimizations

- **Static Site:** Simple, fast, and secure hosting.
- **Responsive Design:** Adapts to various screen sizes (desktop, tablet, mobile).
- **Clear Service Listing:** Dedicated sections for available home care services.
- **Local SEO Focus:** Implemented Schema.org (`HealthcareService`) markup on the homepage to provide structured business information to search engines.
- **Enhanced Social Sharing:** Utilized Open Graph meta tags for improved previews when links are shared on social media.
- **SEO Best Practices:** Included canonical tags to prevent duplicate content issues and ensure proper indexation by search engines.
- **Configured for Deployment:** Setup for automatic builds and deployments via Cloudflare Pages (compiles Tailwind CSS).
- **Sitemap and Robots.txt:** Configured for search engine crawling and indexing.

## Development and Deployment

This site is automatically built and deployed by Cloudflare Pages on pushes to the main branch. The Cloudflare Pages build command runs `npm run build:css` to compile the Tailwind styles. The built site is served from the root directory.

To work on the project locally:

1.  Clone the repository.
2.  Ensure Node.js and npm are installed.
3.  Run `npm install` to install dependencies (primarily Tailwind CSS).
4.  You may need to run a local development command provided by Tailwind (e.g., `npm run watch`) to compile CSS changes while developing.

## Project Structure

```
healthcare-site
├─ about.html
├─ contact.html
├─ css
│  ├─ input.css
│  └─ styles.css
├─ fonts
├─ images
│  ├─ favicon
│  │  ├─ android-chrome-192x192.png
│  │  ├─ android-chrome-512x512.png
│  │  ├─ apple-touch-icon.png
│  │  ├─ favicon-16x16.png
│  │  ├─ favicon-32x32.png
│  │  └─ favicon.ico
│  ├─ hero-background.jpeg
│  ├─ logo-clear.png
│  ├─ logo.png
│  ├─ service-alzheimers.jpg
│  ├─ service-checkins.jpg
│  ├─ service-companion.jpg
│  ├─ service-parkinsons.jpg
│  ├─ service-personal.jpg
│  └─ service-respite.jpg
├─ index.html
├─ js
│  └─ main.js
├─ package.json
├─ robots.txt
├─ services.html
├─ site.webmanifest
├─ sitemap.xml
└─ tailwind.config.js

```

