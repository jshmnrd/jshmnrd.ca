---
title: "Feeds"
emoji: "📰"
#icon_url: "https://pub.jshmnrd.ca/w/svg/0002-RSS.svg" 
#icon_svg: "rss"
ShowPostNavLinks: false
ShowBreadCrumbs: false
disableShare: true
build:
  list: never
hidemeta: true
---

<style>
    .post-content p.br-h2 {
        font-weight: 700;
        font-size: 24px;
        margin: 0;
    }
</style>

Welcome to my /feeds page, a concept created by [Marcus](https://marcus.io/blog/making-rss-more-visible-again-with-slash-feeds). Use these links to subscribe to feeds of my content.

---

<p class="callout">RSS is an acronym for a set of XML feed file format variants used for syndicating time-stamped content from web sites like blogs and podcasts, and sometimes a shorthand for feed file formats as a whole including Atom, or even more broadly for the concept of feeds or syndication in general.
<br><br>
RSS as an acronym has been used to mean: RDF or Rich Site Summary, or Really Simple Syndication.<br>
<small>[<a href="https://indieweb.org/RSS" target="_blank">source</a>]</small>
</p>

<p class="br-h2">All Content</p>
<p><b>Link:</b>&emsp;<a href="https://jshmnrd.ca/index.xml" target="_blank">https://jshmnrd.ca/index.xml</a><span class="tab"></span><button class="copy-btn" data-copy="https://jshmnrd.ca/index.xml">Copy</button>
</p>

<p class="br-h2">Blog Only</p>
<p><b>Link:</b>&emsp;<a href="https://jshmnrd.ca/blog/index.xml" target="_blank">https://jshmnrd.ca/blog/index.xml</a><span class="tab"></span><button class="copy-btn" data-copy="https://jshmnrd.ca/blog/index.xml">Copy</button>
</p>

<script> /* Copy to clipboard script */
document.querySelectorAll(".copy-btn").forEach(button => {
  button.addEventListener("click", () => {
    const textToCopy = button.dataset.copy;
    const originalText = button.textContent;

    navigator.clipboard.writeText(textToCopy).then(() => {
      button.textContent = "Copied!";

      setTimeout(() => {
        button.textContent = originalText;
      }, 1500);
    });
  });
});
</script>