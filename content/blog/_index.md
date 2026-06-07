---
title: "Blog"
description: "My Blog"
ShowBreadCrumbs: false
disableAnchoredHeadings: true
---

<h1>🖊 Blog</h1>
<p>Welcome to my blog! I hope you enjoy :)<br>Check out my <a href="blogroll">blogroll</a>!</p>
<p class="callout rss">
    <span style="font-size:20px;font-weight:700;">Subscribe to my RSS feed!</span>&emsp;&emsp;&emsp;<button title="Copy RSS feed URL" class="copy-btn" data-copy="https://jshmnrd.ca/index.xml">Copy RSS Link</button>
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