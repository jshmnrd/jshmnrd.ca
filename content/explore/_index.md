---
title: "Explore"
description: "Explore the content of my website"
ShowBreadCrumbs: false
---

<h1>🔭 Explore</h1>
<p>
    The main content of my website. Pick a topic from the list and enjoy!<br>
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