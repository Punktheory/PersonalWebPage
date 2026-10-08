# Tsz-Yui Qin — Personal Website

A simple, responsive academic homepage based on the supplied CV, with a layout inspired by [Yangqiu Song's homepage](https://www.cse.ust.hk/~yqsong/).

**Website:** [Tsz-Yui Qin (秦子睿) — HKUST Computer Science](https://punktheory.github.io/PersonalWebPage/)

## Editing

- `index.html` contains the biography, research, manuscripts, education, and experience.
- `styles.css` controls the appearance and mobile layout.
- `sitemap.xml` lists the canonical homepage for submission to search engines. Update its `lastmod` when the homepage content meaningfully changes.
- `assets/tsz-yui-qin.jpg` is the supplied portrait, preserved without alteration.
- `assets/QINTszYui_CV_20260907.pdf` is the original supplied CV.

No dependencies or build step are required. Open `index.html` in a browser to preview the site.

## Publishing

GitHub Pages publishes the root directory of the `main` branch. Updates pushed to `main` are deployed automatically. The `.nojekyll` file keeps the site as plain static files.

## Search discovery

The homepage includes English and Chinese names, the alternative spelling Qin Tsz Yui, a canonical URL, and `ProfilePage` / `Person` structured data linking to the existing GitHub, LinkedIn, and HKUST profiles. These help describe the person and page; they do not guarantee indexing or a particular ranking. The site's URL and existing typography are preserved.

To connect Google Search Console:

1. Add a **URL-prefix** property for `https://punktheory.github.io/PersonalWebPage/`.
2. Select **HTML tag** verification. Add the exact `google-site-verification` meta tag issued to the owner's Google account inside the homepage's `<head>`, publish it, then click **Verify**. Keep the tag after verification. No verification token is included until the owner supplies it.
3. Submit `https://punktheory.github.io/PersonalWebPage/sitemap.xml` in **Sitemaps**.
4. Inspect the canonical homepage URL and choose **Request indexing** if needed.
5. Use the indexing report to confirm Google's status and the performance report to monitor searches such as Tsz-Yui Qin, Qin Tsz Yui, 秦子睿, and HKUST Tsz-Yui Qin.

`robots.txt` rules apply at `https://punktheory.github.io/robots.txt`, not inside `/PersonalWebPage/`. A missing root robots.txt currently does not prohibit crawling, so no ineffective project-directory robots.txt is added. Submit this sitemap through Search Console. If the site is moved later, update the canonical URL and sitemap together and redirect the old page.

Keep links to this homepage on public profiles and project pages. Relevant official guidance: [SEO basics](https://developers.google.com/search/docs/fundamentals/seo-starter-guide), [verification](https://support.google.com/webmasters/answer/9008080?hl=en), and [requesting a crawl](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl).

## Content notes

The initial content is based on the CV dated 7 September 2026. Manuscripts are explicitly labeled as under review. SafetyDPO appears as research-assistant experience and is not listed as an authored publication. Update these statuses when appropriate.

The supplied CV's displayed leaderboard address returns 404; the site uses the working link embedded in that PDF: https://punktheory.github.io/Traderbenchmark/leaderboard/.

The downloadable CV is the original file, including its phone number and existing PDF hyperlinks. The homepage email link uses the visible, correct address `tyqin@connect.ust.hk`.

## Visitor map

The footer area displays a responsive MapMyVisitors map using the embed code supplied by the site owner. The widget loads asynchronously over HTTPS and uses its own external service to record visits and approximate visitor locations. Manage statistics in the MapMyVisitors account that generated this code. The public widget identifier is not an account password or API secret.

The map is limited to 200 pixels wide, fits smaller screens, and is hidden when printing. If JavaScript is disabled, a text alternative is shown. Browser tracking protection or an unavailable provider may prevent the map from loading.
