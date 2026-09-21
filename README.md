# AJCAI 2026 Workshop on AI for Science

Website for the **Workshop on AI for Science — Advanced AI and Data Analytics for Scientific Research**, co-located with [AJCAI 2026](https://ajcai2026.org/), Auckland, New Zealand, 27 November 2026.

## Contents

```
index.html      # the whole site (single, self-contained page)
photos/         # speaker and organiser photos
.nojekyll       # tells GitHub Pages to serve files as-is
```

No build step, no dependencies. Open `index.html` locally, or serve the folder:

```bash
python3 -m http.server 8000
```

## Publishing with GitHub Pages

1. Push this folder to a repository.
2. In the repository, go to **Settings → Pages**.
3. Under *Build and deployment*, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. The site appears at `https://<username>.github.io/<repo>/` within a minute or two.

## Editing

All content and styles live in `index.html`. To add a speaker, copy an existing card block in the speakers section and drop the photo into `photos/`.

## Contact

- Tianyi Zhang — tianyi.zhang2@sydney.edu.au
- Yihao Ding — yihao.ding@uwa.edu.au
