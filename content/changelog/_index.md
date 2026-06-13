---
title: "Changelog"
description: "Track changes made to the website"
icon_svg: "keepachangelog"
layout: "page"
---

<style>
  .post-content h2 {
    font-size: 24px;
    margin: 0;
    color: var(--darkcolor);
  }
</style>

All notable changes to this project will be documented on this page.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- // CURRENT VERSION
‼️ REMEMBER TO CHANGE THE FOOTER ‼️
---------------------------->

## 1.0.5
**Date:** 2026-06-13

### Added

-   Made a [Slashes](/slashes) page.
    -   Added it to the menu as well.

### Removed

-   Removed the "Other" category from the [Explore](/explore) page.
-   Deleted the "Uses" page - by now it's baseically just a duplicate of [colophon](/colophon).

### Changed

-   Updated page titling and icons.
-   [88x31](/88x31) is now it's own page, no longer part of [Explore](/explore).
-   [Colophon](/colophon): Changed site info to colophon, inspired by [Aether Mug](https://aethermug.com/colophon).
-   Updated the [Sitemap](/sitemap)
-   Moved "Other" category pages to main content directory, listed them in [Slashes](/slashes).
-   Removed [Archive](/archive) & [Tags](/tags) from the menu.
    -   Added both to [Blog](/blog) and [Explore](/explore) pages as links above the list of posts.
-   Added [Slashes](/slashes) as a button on the home page.

---

<!-- // PREVIOUS VERSIONS
---------------------------->

## 1.0.4
**Date:** 2026-06-11

### Changed

-   [Blogroll](/blogroll): Moved [blogroll](/blogroll) to the main directory, instead of being a subpage of [blog](/blog).  
    From ```/blog/blogroll``` to just ```/blogroll```
    - Updated [blog](/blog) & [explore](/explore) links.

### Fixed

-   The Blogroll and RSS Feed boxes on [blog](/blog) & [explore](/explore) - now the entire box is hyperlinked, not just the text in the box.

## 1.0.3
**Date:** 2026-06-10

### Added

-   [Site Map](/sitemap): Added a sitemap for accessibility.

## 1.0.2
**Date:** 2026-06-09

### Changed

-   [Changelog](#): Small layout changes to Changelog page.
    -   Previous versions are now details toggles to save space and be more readable.
-   [Site Info](/siteinfo): Moved [siteinfo](/siteinfo) to the main directory, instead of being a subpage of [about](/about).  
    From ```/about/siteinfo``` to just ```/siteinfo```
    -   Updated footer link

## 1.0.1
**Date:** 2026-06-08

### Changed

-   Updated version
    -   Change version number in changelog (here)
    -   Change version number in footer
-   [Changelog](/changelog): Moved changelog to the main directory, instead of a subpage of [about](/about).  
    From ```/about/changelog``` to just ```/changelog```
    -   Updated footer link to the changelog.
-   [Blogroll](/blogroll): Moved the RSS feed link <button class="copy-btn">copy</button> button to the left of the link, for better formatting, especially on skinnier screens.

### Fixed

-   [Blog](/blog): Fixed missing image from blog post [002 - "Blog Links Update"](/blog/002-bloglinks).
-   [Site info](/about/siteinfo): Fixed the summary "Jump to section ↓" button.

## 1.0.0
**Date:** 2026-06-07

### Added

-   Initial commit.  
    Not the initial site commit, but the initial commit of this changelog.  
    To not bog myself down backlogging every change, I've decided to only start tracking now that I've decided to keep a changelog. 