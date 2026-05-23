---
title: "Blog"
description: "My Blog"
ShowBreadCrumbs: false
---

<h1>🖊 Blog</h1>
<p>
    This page is just for quick updates. For now I will show it in RSS but I may remove it later.<br>
    <button title="Copy RSS feed URL" class="copy-btn" data-copy="https://jshmnrd.ca/index.xml">Subscribe to my RSS!</button>
</p>

<script> /* Copy to clipboard script */
document.querySelectorAll(".copy-btn").forEach(button => {
  button.addEventListener("click", () => {
    const textToCopy = button.dataset.copy;
    const originalText = button.textContent;

    navigator.clipboard.writeText(textToCopy).then(() => {
      button.textContent = "RSS Feed URL Copied!";

      setTimeout(() => {
        button.textContent = originalText;
      }, 1500);
    });
  });
});
</script>