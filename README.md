# Xiang Li

Personal academic website: **https://lix0120.github.io/**

Xiang Li is a fourth-year PhD student in mathematics at UCLA, supervised by Itay Neeman. Research interests: forcing, large cardinals, and partition relations.

## Editing

The homepage is in `index.html`. Edit the biography and research interests near the end of the file. Colors, spacing, and typography are defined in its `<style>` block. The site uses no JavaScript, third-party font requests, tracking, or build dependencies. Computer Modern Unicode Serif fonts are served locally from `fonts/`; their license and source information are included there.

Update the year of study in both the visible biography and the description metadata when needed.

## Deployment

The publishing source for this public repository is **main → /(root)**. Changes pushed to `main` are published automatically once Pages is enabled. The empty `.nojekyll` file disables Jekyll processing.

To configure Pages, open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, and save.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8765` in this directory and visit `http://localhost:8765`.
