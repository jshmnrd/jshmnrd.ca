---
title: "Other Stuff"
description: "Posts related to other/random topics"
summary: "Posts in this page don't fit in any of the above topics."
ShowBreadCrumbs: true
date: 2026-03-01
hidemeta: true
cover:
    image: "chill_of_the_wild.gif"
    alt: "“Window” by minimoss on 8bitdash"
    # src: https://www.8bitdash.com/gallery?artworkId=a09012ef-fb2e-4237-a936-3da7ed0a0479
    relative: true
---

<script>
document.addEventListener("DOMContentLoaded", function () {
  const emojis = [
    "🎲","🛩","🐂","🖍","🧠","🕯️","🧽","🐻","🌔","🧨"
  ];

  const randomEmoji = emojis[Math.floor(Math.random() * emojis.length)];

  const titleEmoji = document.querySelector(".title-emoji");

  if (titleEmoji) {
    titleEmoji.textContent = randomEmoji;
  }
});
</script>
<h1>
  <span class="title-emoji">🎲</span>
  Other Stuff
</h1>
Posts in this page don't fit in any of the above topics.