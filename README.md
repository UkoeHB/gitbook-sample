# README

A simple gitbook based on [this tutorial](https://hackernoon.com/how-to-publish-a-book-with-gitbook-cli-and-github-pages-in-7-minutes-i61w3wjn). Find the generated book [here](https://ukoehb.github.io/gitbook-sample/).


## Adding Content

New Markdown files go in `src/` (note: it is fine to add subdirectories to `src/`), and you can edit `SUMMARY.md` to make them appear in the GitBook. See [the documentation](https://gitbookio.gitbooks.io/documentation/content/index.html) for details.

Assuming `gitbook-cli` is installed, run this to update the GitBook:

```
// at command line
gitbook build src docs
```


## GitHub Pages

In GitHub -> Settings -> GitHub Pages -> Source -> select folder `/docs` from the dropdown (and `Save`). Then the GitBook will appear at `https://USERNAME.github.io/gitbook-sample/` (once Pages gets its act together, which may take up to 20mins or so for each update).
