---
title: "Explore"
description: "Explore the content of my website"
ShowBreadCrumbs: false
---

<h1>🔭 Explore</h1>
<p>
    The main content of my website. Pick a topic from the list and enjoy!<br>
    Subscribe to my RSS!&nbsp;<button class="copy-btn" data-copy="https://jshmnrd.ca/index.xml" onClick="alert('Link copied to clipboard!')">Copy RSS feed URL</button>
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