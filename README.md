# Transmodal Sensing workshop websites

Static sites for the Transmodal Sensing workshop series, served with GitHub Pages
at <https://transmodality.github.io/>. The root page redirects to the latest workshop.

- `icra27/` — ICRA 2027 workshop **"Transmodal Sensing: Beyond Vision for Robotic Manipulation"**
  at <https://transmodality.github.io/icra27/>
  - `index.html` — the whole site (Tailwind CSS via CDN, Inter font). No build step.
  - `assets/people/` — square, web-sized headshots used on the page.
  - `assets/figures/` — the "Transmodal Robot Tasks" sketch from the proposal.
  - `media/` — original photos, including images used for Chan Lee and Jeremy Fishel.
  - The source proposal PDF is kept locally and is not committed (see `.gitignore`).

## Publish on GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**,
branch `main`, folder `/ (root)`. Every push to `main` redeploys.

## Preview locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000/icra27/
```

## Things to fill in later

Search `icra27/index.html` for `TBA` and `TBD`: workshop day and room, submission deadlines,
the submission portal link, and award winners.
