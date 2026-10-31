# Transmodal Sensing — ICRA 2027 Workshop website

Static single-page site for the ICRA 2027 workshop
**"Transmodal Sensing: Beyond Vision for Robotic Manipulation"**.

- `index.html` — the whole site (Tailwind CSS via CDN, Inter font). No build step.
- `assets/people/` — square, web-sized headshots (400 px) used on the page.
- `assets/figures/` — the "Transmodal Robot Tasks" sketch from the proposal.
- `media/` — original full-resolution photos (not referenced by the page).
- The source proposal PDF is kept locally and is not committed (see `.gitignore`).

## Publish on GitHub Pages

1. Push this repository to `github.com/transmodality/transmodality.github.io` (branch `main`).
2. In the repository settings, open **Pages** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site appears at <https://transmodality.github.io/> within a minute or two.

## Preview locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Things to fill in later

Search `index.html` for `TBA` and `TBD`: workshop day and room, submission deadlines,
the submission portal link (the disabled "Submission portal — coming soon" button in the
Call for Papers section), panelists, and award winners.
