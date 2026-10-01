# kmfbrightpages.com

Static site for KMF Bright Pages, served by GitHub Pages at https://kmfbrightpages.com.

The pages are **generated** by the book factory (`kmf site build` in `kmf-bright-pages-book-factory`); edit the
factory's `books/<key>/listing/review_link.json` and rebuild rather than editing HTML here.

- `/r/<slug>/` — the page each printed book's QR code points to. "Coming soon" until the book's ASIN is recorded
  (`kmf site asin <book> <ASIN>`), then links to the Amazon review form. Printed codes never change.
- No scripts, cookies or analytics.
