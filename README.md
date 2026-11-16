# Sled Dog Games

The studio page for Sled Dog Games. Plain HTML and CSS, no build step.

- `index.html` is the whole page.
- `assets/` holds the logo animation, the gameplay clips, the fonts and their licenses.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

## Publishing on GitHub Pages

1. Push this folder to a GitHub repository (the files go in the repository root).
2. In the repository, open Settings, then Pages.
3. Under "Build and deployment", pick "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. The page goes live a minute or two later at the address that Pages shows.

Once the address is known, change the `og:image` line near the top of `index.html` to the full address of `assets/sled-dog-games-card.png` so link previews show the logo card.
