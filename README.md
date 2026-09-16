# Xiang Li

Personal academic website: **https://lix0120.github.io/**

Xiang Li is a fourth-year PhD student in mathematics at UCLA, supervised by Itay Neeman. Research interests: forcing, large cardinals, and partition relations.

## Editing

The homepage is in `index.html`. Edit the biography and research interests near the end of the file. Colors, spacing, and typography are defined in its `<style>` block. The site uses no JavaScript, third-party font requests, tracking, or build dependencies. Text uses the system Courier New font, with Courier and monospace fallbacks. All headings use regular weight. The page is left-aligned and fills the available width; the horizontal rule follows the window width.

Update the year of study in both the visible biography and the description metadata when needed.

The email address in the header is a high-resolution transparent image at
`assets/contact-courier-new.png`. Use a new image filename when changing its font
so browsers request the new version. Keep it as an image rather than adding a plain-text address
or a `mailto:` link. Its alternative text spells out “at” and “dot” for screen
readers. Email and office occupy two rows on the right side of the header.

## Deployment

The publishing source for this public repository is **main → /(root)**. Changes pushed to `main` are published automatically once Pages is enabled. The empty `.nojekyll` file disables Jekyll processing.

To configure Pages, open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, and save.

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8765` in this directory and visit `http://localhost:8765`.
