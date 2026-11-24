# Import report: The Arts of Becoming

Imported from page.zip on 2026-11-24 with `openspace import html`.
Sources: the page's HTML and CSS. 0 requests.

## Summary

- **7** pages, **0** collection items in 0 collection(s)
- **0** media files (0.0 MB) downloaded into `media/`
- **0** redirects so old addresses keep working
- **0** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | The Arts of Becoming | 1 | 1 |
| `/the-arts` | `/the-arts` | The Arts | 1 | 1 |
| `/the-thread` | `/the-thread` | The Thread | 1 | 1 |
| `/true-to-essence` | `/true-to-essence` | True To Essence | 1 | 1 |
| `/journal` | `/journal` | The Journal | 1 | 1 |
| `/about` | `/about` | Kathleen Marie Rose | 1 | 1 |
| `/inquire` | `/inquire` | What is calling you? | 1 | 1 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying the original site's CSS or code.

- Brand color #472d1e (the site's accent color).
- Fonts on the original site: Cormorant Garamond / Hanken Grotesk → pairing "Cormorant Garamond & Jost" (Cormorant Garamond / Jost), same family for Cormorant Garamond. Licensed fonts can be uploaded in Site Styles → Fonts.
- Type scale on the original site: Heading 1 is 2.4× body text. Density "comfortable" from the section heights.
- Page background #fefdf5 on the original site → #fcfaf8 (text contrast 15.6:1).

Design check: 0 error(s), 85 warning(s).

- warning (/): “The Arts of Becoming” has no clear call to action — nothing tells visitors what to do next.
- warning (/): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/the-arts): “The Arts” has no clear call to action — nothing tells visitors what to do next.
- warning (/the-arts): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/the-thread): “The Thread” has no clear call to action — nothing tells visitors what to do next.
- warning (/the-thread): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/true-to-essence): “True To Essence” has no clear call to action — nothing tells visitors what to do next.
- warning (/true-to-essence): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/journal): “The Journal” has no clear call to action — nothing tells visitors what to do next.
- warning (/about): “Kathleen Marie Rose” has no clear call to action — nothing tells visitors what to do next.
- warning (/inquire): “What is calling you?” has no clear call to action — nothing tells visitors what to do next.
- warning (site): The The Arts of Becoming section uses 8 fixed colours, so Site Styles can't restyle them.
- … and 73 more: run Design check in Studio or `design_check` with Claude.

## Needs attention

Nothing: every page, block and link was mapped.

## Not moved by the importer

- Scripts, animations and anything rendered only by JavaScript (try `--render` for script-built pages).
- Server-side features: shops, logins, search, comments.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://site.openspace.invalid` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the old hosting until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).


## Designed sections

37 sections keep their own design as a designer component. Every word, picture and link in them is a field you edit in Studio; the design itself changes only through Component code (designers) or Claude.

| Section | Page | Fields | CSS |
|---|---|---|---|
| The Arts of Becoming (`welcome`) | / | 8 | 2.0 KB |
| There is an art to becoming who you are. (`premise`) | / | 4 | 1.3 KB |
| See · Liberate · Create · Cultivate (`living-practice`) | / | 7 | 1.8 KB |
| The Arts (`the-arts`) | / | 3 | 1.5 KB |
| The Thread (`the-thread`) | / | 8 | 2.3 KB |
| Photography for the evolutionary being. (`true-to-essence`) | / | 5 | 1.7 KB |
| Field notes on being + becoming. (`journal`) | / | 5 | 1.9 KB |
| Hi, I'm Kathleen. (`kathleen`) | / | 7 | 1.7 KB |
| What is asking to become through you? (`begin`) | / | 3 | 1.8 KB |
| The Arts (`the-arts-arts-intro`) | /the-arts | 2 | 1.3 KB |
| Embodiment + Practice (`the-arts-embodiment`) | /the-arts | 5 | 1.4 KB |
| Courses + Circles (`the-arts-circles`) | /the-arts | 5 | 1.5 KB |
| Earth + Living Systems (`the-arts-earth`) | /the-arts | 4 | 1.4 KB |
| Creative Work (`the-arts-creative`) | /the-arts | 5 | 1.6 KB |
| Not sure where to begin? (`the-arts-dark`) | /the-arts | 4 | 1.9 KB |
| The Thread (`the-thread-thread-intro`) | /the-thread | 3 | 1.4 KB |
| Thresholds (`the-thread-thresholds`) | /the-thread | 1 | 1.0 KB |
| You are not a formula. (`the-thread-not-a-curriculum`) | /the-thread | 5 | 1.5 KB |
| The threads we may draw from (`the-thread-the-threads`) | /the-thread | 4 | 2.1 KB |
| What it may include (`the-thread-what-it-includes`) | /the-thread | 1 | 1.1 KB |
| The container (`the-thread-the-container`) | /the-thread | 4 | 1.5 KB |
| Begin with a conversation. (`the-thread-begin`) | /the-thread | 4 | 1.9 KB |
| True To Essence (`true-to-essence-tte-intro`) | /true-to-essence | 6 | 2.0 KB |
| A world of its own. (`true-to-essence-a-world-of-its-own`) | /true-to-essence | 1 | 1.2 KB |
| Soulcentric Photography (`true-to-essence-approach`) | /true-to-essence | 2 | 1.4 KB |
| What I photograph (`true-to-essence-what-i-photograph`) | /true-to-essence | 2 | 1.3 KB |
| Come as you are. (`true-to-essence-dark`) | /true-to-essence | 4 | 1.9 KB |
| The Journal (`journal-journal-intro`) | /journal | 2 | 1.3 KB |
| Territories (`journal-territories`) | /journal | 2 | 1.1 KB |
| Letters from the Arts of Becoming (`journal-letters`) | /journal | 3 | 1.4 KB |
| Kathleen Marie Rose (`about-about-intro`) | /about | 3 | 1.4 KB |
| A regenerative Renaissance woman. (`about-renaissance`) | /about | 7 | 1.3 KB |
| A path of devotion (`about-devotion`) | /about | 1 | 1.1 KB |
| The thread beneath everything. (`about-thread-beneath`) | /about | 4 | 1.6 KB |
| What is calling you? (`inquire-inquire-intro`) | /inquire | 2 | 1.3 KB |
| I want support in my becoming. (`inquire-doors`) | /inquire | 9 | 1.4 KB |
| Footer (`site-footer`) | footer | 3 | 1.1 KB |
