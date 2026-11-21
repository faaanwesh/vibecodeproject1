# Protocol Explorer

An interactive, self-contained learning lab that visualizes how a web request travels through the internet.

## Features

- Seven guided stages: application, DNS, TCP, TLS, IP routing, link delivery, and physical transmission.
- Animated packet journey with step controls and autoplay.
- TCP/IP protocol stack reference.
- Knowledge-check quiz with explanations.
- HTTP/1.1 request builder playground.
- Responsive dark interface; no framework, build step, backend, or API keys required.
- All interactions run locally in the browser.

## Run locally

Open `index.html` in any modern browser.

## Deploy with GitHub Pages

A GitHub Actions workflow in `.github/workflows/deploy.yml` publishes the repository root whenever `main` is updated.

In the repository settings, open **Pages** and set **Build and deployment → Source** to **GitHub Actions** if it is not already selected. The first workflow run will publish the site.

## License

Educational project. Protocol names and standards belong to their respective owners.
