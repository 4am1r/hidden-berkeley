# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is made for incoming students at UC Berkeley, helping them lovate necessary reosurces around campus and the larger community. The first eight resources were supplied by COMPSS 211A; I added the Undergraduate Academic Building (information from https://www.berkeley.edu/map/undergraduate-academic-building/).

## Website checks

The website link is https://4am1r.github.io/hidden-berkeley/. I verified that the Undergraduate Academic Building's access is not limited to undergraduate students; anyone can euse the collaborative spaces. I improved the Morrison Library resource, adding the specific operating hours. FInally, the displayed values on the website match my CSV, and the links all work properly.
