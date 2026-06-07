---
title: "Explore"
description: "Explore the content of my website"
ShowBreadCrumbs: false
---

<h1>🔭 Explore</h1>
<p>The main content of my website. Pick a topic from the list and enjoy!</p>
<p class="callout rss" onmouseover="cursor:'pointer;'" onmouseout="cursor:'auto;'">
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