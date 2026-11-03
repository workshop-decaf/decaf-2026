# decaf-2026
Initial code for DeCaF 2026

Presentation PDFs are stored in `assets/slides/` and linked from the workshop
program in `index.html`. GitHub Pages serves them directly with the rest of the
static site. PDF links open in the browser. File sizes in the agenda use decimal MB.

To add a presentation, copy the supplied PDF into `assets/slides/` with a
descriptive filename and link it from the matching program entry. Keep local
source copies in the ignored `slide-source/` directory. Publish only PDFs,
preserve the supplied PDF contents, and update the displayed size when replacing
a deck. Do not commit PowerPoint source files.

Each file must stay below GitHub's [100 MiB repository file limit](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github),
and the published site must stay below the [1 GB GitHub Pages limit](https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits).
These presentation files are committed directly to Git; no Git LFS or external
file host is needed.
