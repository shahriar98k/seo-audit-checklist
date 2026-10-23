# SEO Audit Checklist for Online Stores

A plain checklist I use to audit e-commerce sites. Work from top to bottom. Tick each box as you go.

## 1. Crawling and indexing
- [ ] `robots.txt` does not block important pages
- [ ] XML sitemap exists, is in Search Console and lists only indexable URLs
- [ ] Important pages return status 200
- [ ] No long redirect chains
- [ ] Broken links (404) are fixed or redirected
- [ ] Filter and sort URLs have canonical tags or are blocked from crawling
- [ ] Search Console shows no big jump in "Excluded" pages

## 2. Site speed and mobile
- [ ] Pages pass Core Web Vitals in Search Console
- [ ] Images are compressed and use modern formats
- [ ] Mobile pages show the same content as desktop
- [ ] Buttons and text are easy to tap and read on a phone

## 3. On-page basics
- [ ] One unique title per page, about 30 to 60 characters
- [ ] One unique meta description per page, about 70 to 160 characters
- [ ] One H1 per page with the main keyword
- [ ] Clear H2 and H3 structure
- [ ] Image alt text describes the image
- [ ] URLs are short and readable

## 4. Product and category pages
- [ ] Every product has its own text, not the supplier copy
- [ ] Category pages have a short intro and a helpful guide below the products
- [ ] Out-of-stock products are kept, redirected or marked clearly
- [ ] Reviews are shown on the page
- [ ] Product schema is added and passes the Rich Results Test (see [schema-markup-templates](https://github.com/shahriar98k/schema-markup-templates))

## 5. Content and keywords
- [ ] Each page targets one main search intent
- [ ] No two pages fight for the same keyword
- [ ] Thin pages are improved, merged or removed
- [ ] Blog posts answer real buying questions and link to products

## 6. Internal links
- [ ] Important pages are within three clicks of the home page
- [ ] Categories link to top products and the other way round
- [ ] Anchor text says what the page is about
- [ ] No orphan pages (pages with no links to them)

## 7. Off-page and trust
- [ ] Backlinks come from real, relevant sites
- [ ] Toxic or spammy links are reviewed
- [ ] Google Business Profile is complete (for shops with a local presence)
- [ ] Contact, About, Returns and Privacy pages are easy to find

## 8. International and language (if used)
- [ ] `hreflang` tags are correct and point both ways
- [ ] Each language has its own URL and its own native copy, not machine translation
- [ ] Currency and shipping details match each market

## 9. Tracking
- [ ] Google Analytics and Search Console are set up and working
- [ ] Sales and form goals are tracked
- [ ] You have a baseline: clicks, impressions, sales, top pages

## After the audit
1. Sort the fixes by effect and effort.
2. Do quick wins first: titles, descriptions, broken links.
3. Check results in Search Console after 4 to 8 weeks.

Useful tools: [meta-tag-checker](https://github.com/shahriar98k/meta-tag-checker) and [gsc-report-tools](https://github.com/shahriar98k/gsc-report-tools).

Built by [Shahriar Kamal](https://shahriar98k.github.io/), SEO specialist. MIT license.
