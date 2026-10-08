# Tsz-Yui Qin — Personal Website

A simple, responsive academic homepage based on the supplied CV, with a layout inspired by [Yangqiu Song's homepage](https://www.cse.ust.hk/~yqsong/).

**Website:** https://punktheory.github.io/PersonalWebPage/

## Editing

- `index.html` contains the biography, research, manuscripts, education, and experience.
- `styles.css` controls the appearance and mobile layout.
- `assets/tsz-yui-qin.jpg` is the supplied portrait, preserved without alteration.
- `assets/QINTszYui_CV_20260907.pdf` is the reserved CV download path; the PDF is temporarily not published.

No dependencies or build step are required. Open `index.html` in a browser to preview the site.

## Publishing

GitHub Pages publishes the root directory of the `main` branch. Updates pushed to `main` are deployed automatically. The `.nojekyll` file keeps the site as plain static files.

## Content notes

The initial content is based on the CV dated 7 September 2026. Manuscripts are explicitly labeled as under review. SafetyDPO appears as research-assistant experience and is not listed as an authored publication. Update these statuses when appropriate.

The supplied CV's displayed leaderboard address returns 404; the site uses the working link embedded in that PDF: https://punktheory.github.io/Traderbenchmark/leaderboard/.

The CV link remains in the navigation, but its PDF is temporarily withheld and the URL intentionally returns 404. A local backup is kept outside the website repositories. To re-enable downloads when authorized, restore the desired PDF at the reserved path and remove its `.gitignore` entry before publishing. This withdrawal does not remove copies from existing Git history. The homepage email link uses `tyqin@connect.ust.hk`.

## Visitor map

The footer area displays a responsive MapMyVisitors map using the embed code supplied by the site owner. The widget loads asynchronously over HTTPS and uses its own external service to record visits and approximate visitor locations. Manage statistics in the MapMyVisitors account that generated this code. The public widget identifier is not an account password or API secret.

The map is limited to 200 pixels wide, fits smaller screens, and is hidden when printing. If JavaScript is disabled, a text alternative is shown. Browser tracking protection or an unavailable provider may prevent the map from loading.
