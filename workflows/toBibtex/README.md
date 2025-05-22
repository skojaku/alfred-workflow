This workflow streamlines the generation of clean BibTeX entries from either a DOI or a paper title.

# Prerequisites

Ensure the following are installed:

* `curl`
* `jq`
* `python3`
* `bibtex-tidy`
* `pbcopy` (macOS)

# Usage

In Alfred, type:

```
bib Unsupervised embedding of trajectories captures the latent structure of scientific migration
```

or

```
bib 10.1145/3511808.3557220
```

The BibTeX will be copied to clipboard.