---
title: "Explore"
description: "Explore the content of my website"
ShowBreadCrumbs: false
---

<h1>🔭 Explore</h1>
<p>The main content of my website. Pick a topic from the list and enjoy!</p>
<div class="callout-row">
  <p class="callout rss">
    <a style="font-size:20px;font-weight:700;text-decoration:none;" href="/feeds">RSS Feeds</a>
  </p>

  <p class="callout rss">
    <a style="font-size:20px;font-weight:700;text-decoration:none;" href="/blog/blogroll">Blogroll</a>
  </p>
</div>

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