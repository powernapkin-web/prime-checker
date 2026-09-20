# Prime Checker

A dark-themed prime number checker web app — single HTML file, no dependencies.

## What it does

Enter any whole number and get an instant answer:

- **Prime** — confirms primality, shows the previous and next prime numbers
- **Composite** — lists all factors
- **0 or 1** — correctly identifies them as neither prime nor composite
- Rejects negatives and numbers that are too large

## How it works

Pure client-side JavaScript with a trial-division primality test (6k ± 1 optimization). No server, no build step, no dependencies. Just open the HTML file in any browser.

## Running locally dis

```bash
# Any static server works
python3 -m http.server 8080
# then open http://localhost:8080
```

Or just double-click `index.html` — it runs entirely from disk.

## Deploy

Hosted on GitHub Pages: https://powernapkin-web.github.io/prime-checker/
