# Xiang Li

Personal academic website: **https://lix0120.github.io/**

Xiang Li is a fourth-year PhD student in mathematics at UCLA, supervised by Itay Neeman. Research interests: forcing, large cardinals, and partition relations.

## Editing

The homepage is in `index.html`. Edit the biography and research interests near the end of the file. Colors, spacing, and typography are defined in its `<style>` block. The site uses no JavaScript, third-party font requests, tracking, or build dependencies. Courier Prime fonts are served locally from `fonts/`; their license and source information are in `courier-prime-OFL.txt` and `courier-prime-PROVENANCE.md`.

Update the year of study in both the visible biography and the description metadata when needed.

The email address in the header is a high-resolution transparent image at
`assets/contact.png`. Keep it as an image rather than adding a plain-text address
or a `mailto:` link. Its alternative text spells out “at” and “dot” for screen
readers. The office appears beside it as ordinary text.

## Deployment

The publishing source for this public repository is **main → /(root)**. Changes pushed to `main` are published automatically once Pages is enabled. The empty `.nojekyll` file disables Jekyll processing.

To configure Pages, open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, and save.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8765` in this directory and visit `http://localhost:8765`.
