# Changelog

## Version 1.5.0 (2020-11-01)

- Change from lernblog.ch to lernblog.org.
- No emojis and other non-Latin characters in slug.
- Style: small color and size adjustments.
- Use some nice mountains as default images.
- FEED: Improve Atom XML feed (paging, full content, featured image)
- Update to Hugo v0.88.1

## Version 1.4.4 (2020-09-26)

- Update Hugo to v0.75.1
- Remove `disableFastRender` in the Hugo config.

## Version 1.4.3 (2020-08-05)

- Fix image urls in RSS and JSON Feeds.

## Version 1.4.2 (2020-08-25)

- CMS: Make E-Mail optional for author settings.

## Version 1.4.1 (2020-08-12)

- Change preview path to home URL. The slug does not work correctly with the new folder structure.
- Use last italic <em> element in blockquotes for blockquote footer.

## Version 1.4.0 (2020-08-11)

- BREAKING: Organize content in subfolders (keeps images together with content).
- BREAKING: Rename `content/img` to `content/media` (may contain other assets than images like pdf files).
- Update to Hugo v0.74.3.
- Update to Bootstrap v4.5.2 
- Update to medium-zoom v1.0.6
- Update to jQuery v3.5.1
- Improve styling of blockquote. Now supports adding of a footer for source or author.
- CMS: Re-add warning message to tags that `#` are not allowed.
- CMS: Content footnotes as slimmed down markdown editor.
- CMS: Allow the use of Netlify identity login (redirect from home to /admin/ for initial password setup).
- CMS: Add image upload size limit.
- Deploy to Netlify button (see README).

## Version 1.3.7 (2020-02-15)

- Hugo's new Markdown library (Goldmark) does not allow inline HTML by default. We turn this on with `unsafe = true`.

## Version 1.3.6 (2020-02-15)

- Update to Hugo v0.64.1.
- Use `.Site.Pages` instead of `.Pages` to find pages in specific sections.
- Fix image links (public folder). It must start with a slash to be absolute in new NetlifyCMS version.
- Link from taxonomy terms page to home.

## Version 1.3.5 (2019-09-13)

- Design: Add `margin-bottom` to div elements in article content (used for [Video embeds](https://getbootstrap.com/docs/4.1/utilities/embed/)).

## Version 1.3.4 (2019-09-04)

- CMS: Add warning message to tags that `#` are not allowed (had to be removed again).

## Version 1.3.3 (2019-08-29)

- Design: Same bottom margin on lists as on paragraphs.

## Version 1.3.2 (2019-08-03)

- General Settings: Remove Facebook/Twitter from footer, change default subtitle.

## Version 1.3.1 (2019-07-04)

- CMS: Set tags to optional to make it clear for the user that it is not necessary.
- CMS: Remove previews and preview styles.
- CMS: Add a preview path and display url.
- CMS: Remove Netlify identity widget from home page.
- BUG: Deactivate tags validation because of a NetlifyCMS bug (also see #4).

## Version 1.3.0 (2019-06-23)

- BREAKING CHANGE: Remove image from automatically being added to the top of each post. Now the post image is only used in the blog overview and for SEO. This allows more flexibility about images in the post content.
- CMS: Make design color optional.
- Remove prefilled design color.
- LICENSE: More explicit explanation of license.
- Styling: Better handling of image caption margins.

## Version 1.2.0 (2019-06-17)

- Make post summary optional and fall back to first words of content if no summary is available (see #6).
- Footnotes on custom pages.
- Add next and prev meta tags for paginated overview page.
- Rename "Unterseiten" to "Eigene Seiten".
- Switch CDN for NetlifyCMS because of slow loading times (from jsdelivr to unpkg).
- Use CSS custom properties to simplify the user defined color.
- Styling: make some gray texts slightly darker.

## Version 1.1.0 (2019-06-14)

- Use `/tags/...` as path to the tag overview and also every single tag page.
- Remove `enableGitInfo` from config and use the command line flag in netlify instead. This makes it easier for users to download the repo and run Hugo locally without using git (see https://github.com/gohugoio/hugo/issues/6035).

## Version 1.0.5 (2019-06-08)

- Make tags clickable on frontpage cards.
- Improve tag and tag overview pages.
- Remove Font Awesome icon font. Instead use HTML arrows and Emojis.
- Add custom svg pin icon.

## Version 1.0.4 (2019-06-05)

- Footnote: Use text field widget instead of markdown/rich-text area. Also improve footnote styling to support markdown footnotes.

## Version 1.0.3 (2019-06-03)

- CMS: Make profile image, icon, and logo to optional.
- Use relative url for images in blog overview. This is more stable during DNS and URL changes.

## Version 1.0.2 (2019-06-03)

- CMS: Make blog image optional.
- Compress the standard images.
- JSON Feed: Use "jsonify" instead of "HTML escape".
- ATOM Feed: Use "HTML escape".
- Add LICENSE und info about licens in README.
- Add CHANGELOG.

## Version 1.0.1 (2019-05-28)

- Make Footer optional.
- Change the date format of posts from date-time to date only.

## Version 1.0.0 (2019-05-28)

- Initial version.
