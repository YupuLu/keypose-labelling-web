# Keypose Exploration project page

This directory contains a static project page for **Keypose Exploration: Efficient Automatic Trajectory Labelling and Cross-Embodiment Policy Transfer**.

## Local preview

From `web/keypose-labelling/`, run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://localhost:8000/>. The page and its `figures/` directory must remain together.

## Release placeholders

The page links to the paper at <https://arxiv.org/abs/2606.29028> and the project repository at <https://github.com/YupuLu/keypose_labelling>. The BibTeX block uses the supplied arXiv citation.

The hero briefly introduces the two following projects. Their paper and project links, and a short explanation of how they connect, appear near the bottom.

The page uses only the three publication figures copied from `manip/policy/tase/doc/pic/`: the automatic labelling pipeline, the keypose example, and the rollout comparison. It contains no participant data or internal experiment files.

QR code assets for posters are stored separately in `../poster-qr/` and are not part of this webpage. That directory keeps the repository QR as `qr-keypose-labelling-project` and the webpage QR as `qr-keypose-labelling-web`.

## GitHub Pages

Copy the contents of this directory to the root of a public repository and enable GitHub Pages from the `main` branch. The site will then be available at `https://<username>.github.io/<repository>/`.
