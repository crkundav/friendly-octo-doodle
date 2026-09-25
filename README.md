# Math Fun 🎈

A tap-to-play math game for young kids, made for iPad.

- **Pick the math:** Adding (+), Take away (−), Groups of (×), or any mix
- **Pick the size:** numbers up to 5, 10, or 20
- Pictures for every problem; tap them to count out loud
- Questions are read aloud, with friendly hints after a wrong answer
- 10 questions per round, a star for each one

It's a single `index.html` with no build step and no dependencies.

## Play locally

```bash
python3 -m http.server 8010
```

Open http://localhost:8010. An iPad on the same Wi‑Fi can open `http://<your-mac's-ip>:8010`.

## Play anywhere (GitHub Pages)

In the repo on GitHub, go to **Settings → Pages**, set **Source** to "Deploy from a branch", pick `main` / `(root)`, and save.
The game goes live at `https://<username>.github.io/<repo>/`. On the iPad, open it in Safari, then tap **Share → Add to Home Screen** to give it an app icon.
