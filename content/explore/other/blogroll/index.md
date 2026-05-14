---
title: "Blogroll" 
date: 2026-05-13
tags: ["posts","lists","resources","websites"]
author: ["Joshua Maynard"]
description: "My blogroll: a list of the blogs I read."
summary: "My blogroll: a list of the blogs I read."
#cover:
    #image: "#"
    #alt: "“title” by artist on website"
    # src: #
    #relative: true
    #crop: "Center"
editPost:
    URL: "https://github.com/jshmnrd/hugo/tree/main/content/explore/other/blogroll"
    Text: "version 01"
showToc: false
disableAnchoredHeadings: false
ShowWordCount: false
---

These are my favourite blogs!  
The list is in alphabetical order and will be updated as often as I remember. For reading blogs, I use [Mire](https://mire.meadow.cafe), so the most up-to-date list is on there - [here's a link to my blogroll on Mire](https://mire.meadow.cafe/u/jshmnrd/blogroll).

<h2>Aditya Telange</h2>
<b>Website:</b> <a href="https://adityatelange.in/" target="_blank">adityatelange.in</a><br>
<b>RSS feed:</b> adityatelange.in/index.xml&emsp;&emsp;<button class="copy-btn" data-copy="https://adityatelange.in/index.xml">Copy</button>

<h2>Arduin</h2>
<b>Website:</b> <a href="https://arduin.io/" target="_blank">adityatelange.in</a><br>
<b>RSS feed:</b> arduin.io/index.xml&emsp;&emsp;<button class="copy-btn" data-copy="https://arduin.io/index.xml">Copy</button>

<h2>James' Coffee Blog</h2>
<b>Website:</b> <a href="https://jamesg.blog/" target="_blank">jamesg.blog</a><br>
<b>RSS feed:</b> jamesg.blog/feed/&emsp;&emsp;<button class="copy-btn" data-copy="https://jamesg.blog/feed">Copy</button>

<h2>Meadow</h2>
<b>Website:</b> <a href="https://meadow.cafe/" target="_blank">meadow.cafe</a><br>
<b>RSS feeds:</b> meadow.cafe/feeds/&emsp;&emsp;<button class="copy-btn" data-copy="https://meadow.cafe/feeds/">Copy</button>

<h2>Robert Birming</h2>
<b>Websites:</b> <a href="https://robertbirming.com" target="_blank">robertbirming.com</a>&emsp;&emsp;&emsp;<a href="https://birming.com" target="_blank">birming.com</a><br>
<b>RSS feeds:</b> robertbirming.com/feed/&emsp;&emsp;<button class="copy-btn" data-copy="https://robertbirming.com/feed/">Copy</button>&emsp;&emsp;&emsp;birming.com/feed.xml<button class="copy-btn" data-copy="https://birming.com/feed.xml/">Copy</button>

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