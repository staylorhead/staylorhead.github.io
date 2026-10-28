# staylorhead.github.io

Personal research site for S. Taylor Head, PhD. Plain HTML and CSS, no build step: GitHub Pages serves the files as they are.

## Editing

| To change | Edit |
| --- | --- |
| Bio, news, contact | `index.html` |
| Research themes | `research.html` |
| Papers | `publications.html` (copy an existing `<li>` block) |
| Colors and fonts | `assets/site.css` (variables at the top) |
| Photo | replace `assets/img/taylor-head.jpg` |

## Adding a CV

Put the PDF at `assets/Head_CV.pdf`, then uncomment the CV line in the navigation of each page (search for `Head_CV.pdf`).

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publishing

Push to `main`. In the repository's **Settings → Pages**, set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
