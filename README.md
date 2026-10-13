# GitHub Workshop

A beginner-friendly introduction to Git and GitHub using **GitHub Desktop**, from the [Reality Bending Lab](https://realitybendinglab.com/) at the University of Sussex. No prior experience needed.

There are two versions of the workshop:

| Workshop | For | Slides |
|---|---|---|
| **Internal** | Members of the Reality Bending Lab | 👉 **[View the internal slides](https://anafneves.github.io/GitHubWorkshop/internal/workshop_internal.html)** |
| **External** | Members of Liat's Lab| 👉 **[View the external slides](https://anafneves.github.io/GitHubWorkshop/external/workshop_external.html)** |

## What it covers

Both workshops cover:

- Why use Git and GitHub
- Key ideas: repository, fork, clone, commit, push, pull, pull request
- Setting up GitHub Desktop
- The workflow: fork ➜ clone ➜ commit ➜ push ➜ pull request ➜ keep your fork up to date
- Extras: creating your own repository, going back in time, when things go wrong, branches

The two versions differ in:

| | Internal | External |
|---|---|---|
| **PI's view** (one repo per project, how our repos are organised) | – | ✓ |
| **Hands-on exercise** | Add a memory to the REBEL website | Fork the [Biosignals-2](https://github.com/cmdaoust/Biosignals-2) repo and open a pull request |

## Repository structure

```
README.md
workshop.scss                     # Shared slide theme (colours, cards, boxes)
internal/
  workshop_internal.qmd           # Internal slides (edit this)
  images/                         # Screenshots used in the internal slides
external/
  workshop_external.qmd           # External slides (edit this)
  images/                         # Screenshots used in the external slides
```

## Editing the slides

The slides are written in [Quarto](https://quarto.org). Edit the `.qmd` file, then render it to HTML:

```bash
quarto render internal/workshop_internal.qmd
quarto render external/workshop_external.qmd
```

## Contact

Ana Neves: a.neves@sussex.ac.uk
