# Content and link comparison report

Source of truth: `https://ksenia-alekseeva.vercel.app/`

Comparison date: 14 November 2026

## Summary

The local replica was created from the current production HTML and original production assets. It now includes the original two requested changes plus the eight follow-up revisions requested on 14 November 2026. All other production content, styling and functionality remain unchanged.

## Intended differences

1. The original portrait asset is replaced by the supplied `my photo_new.png`. The existing circular placement, responsive dimensions, object-fit crop, glow, alt text and eager loading behaviour are preserved. Image metadata and structured-data dimensions now reference the new 1122 × 1402 source file.
2. A seven-image, heading-free photography carousel uses the supplied numbered photographs in the original order. It now appears inside `Awards and recognition`, before the awards list. The excluded `1766058853602.jpeg` Augustus Media/LG collage is not present.
3. The Yango logo card now uses the horizontal black Yango Yasmina SVG supplied in the shared Drive folder, with the subtitle “UAE market launch, from day one”.
4. The second About paragraph, result metric labels, result source-link placement and three career titles were updated to the supplied wording.
5. The Kazan Digital Forum Instagram link was removed.
6. Sorbonne University Abu Dhabi was added under Teaching as “Guest lecturer on advertising and marketing”, linked to the supplied LinkedIn post.
7. The supplied Instagram profile was added to the contact buttons and JSON-LD `sameAs` list.

The carousel adds only its own CSS, markup and interaction script. It uses native horizontal overflow, touch and trackpad scrolling, scroll snapping, left/right buttons, keyboard arrow controls, reduced-motion support, lazy image decoding and responsive card widths of approximately three items on desktop and 1.2 items on mobile.

## Content preservation

- Navigation: unchanged, including all five production anchor links.
- Hero, facts and CTA copy: unchanged word for word.
- Brands and logos: order is unchanged; the Yango card alone is replaced by the requested Yango Yasmina logo and subtitle.
- About: first and third paragraphs are unchanged; the second uses the supplied replacement text.
- Selected results: all five entries and descriptions remain; short metric labels were added and the dynamic-feed source link was moved to the Sephora and Samsung entry.
- Career: dates and bullets are unchanged; all three role headings use the supplied expanded titles and locations.
- Expertise: all four areas and descriptions unchanged.
- Awards and recognition: all nine items, descriptions and links remain, preceded by the relocated carousel.
- Speaking and stage: all eight items remain; only the Kazan Instagram link was removed.
- Podcast and writing are unchanged; Teaching adds the Sorbonne University Abu Dhabi guest lecture.
- Quick answers: all six visible FAQ entries and answers unchanged; the existing five FAQ structured-data entries are also unchanged.
- Contact adds the requested Instagram profile; footer text is unchanged.

## Link comparison

- Existing links in production: 49 total anchor elements.
- Current links locally: 50 total anchor elements.
- Added carousel links: 0.
- Added links: Sorbonne LinkedIn post and Instagram profile.
- Removed link: Kazan Digital Forum Instagram post.
- Moved link: “Boosting sales with dynamic feed” now appears under Sephora and Samsung at Publicis.

All internal anchors and every production external URL were copied directly from the live DOM. No URL was invented or substituted.

## Asset comparison

- Original production brand logos retained: Yango Play, Publicis Groupe, Samsung, TikTok Ad Awards, Sephora, Visa and NEOM.
- The Yango logo was replaced by the horizontal black Yango Yasmina SVG from the supplied Drive folder.
- Original favicon retained.
- Original font import retained: Bricolage Grotesque and IBM Plex Sans.
- Replacement portrait used directly from the supplied PNG without regeneration or appearance editing.
- Carousel files used directly from the supplied JPEGs without regeneration or stretching.

## SEO and structured content

The production title, description, author, robots directives, canonical URL, Open Graph copy, Twitter copy, JSON-LD graph, `robots.txt`, `llms.txt` and sitemap structure are preserved. Only portrait image URLs and their actual dimensions were updated to the supplied portrait. The sitemap image entry was updated to the same portrait file.

## Remaining review step

Before any production deployment, review the local preview at desktop and mobile sizes. No production deployment has been performed.
