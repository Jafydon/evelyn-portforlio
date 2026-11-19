# Barrister Evelyn Olotu Portfolio

## Run locally
Open `index.html` in a browser, or use a local development server (for example VS Code Live Server).

## Offline support
The service worker (`sw.js`) caches the homepage and the two main portrait images. Service workers require HTTPS hosting or localhost; they do not activate when opening the HTML file directly with `file://`.
After the first successful visit while online, the cached page can load when the network is unavailable.

## GitHub Pages
Commit and push `index.html`, `sw.js`, and the `images` folder together. Enable GitHub Pages for the repository. Use the published HTTPS address for offline caching.

## Contact form
The contact form opens the visitor's email application using `evelynlinks2008@gmail.com`. It does not send mail directly from the website. A hosted form service or backend is needed for direct submission.

## Motion
Animations use CSS and the browser's IntersectionObserver API. No external animation library is required. Reduced-motion preferences are respected.
