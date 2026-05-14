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
<b>Website:</b> <a href="https://adityatelange.in/" target="_blank">adityatelange.in</a>  
<b>RSS feed:</b> adityatelange.in/index.xml&nbsp;&nbsp;<button class="copy-btn" data-copy="https://adityatelange.in/index.xml">Copy</button>

<h2>Arduin</h2>
<b>Website:</b> <a href="https://arduin.io/" target="_blank">adityatelange.in</a>  
<b>RSS feed:</b> arduin.io/index.xml&nbsp;&nbsp;<button class="copy-btn" data-copy="https://arduin.io/index.xml">Copy</button>

## James' Coffee Blog
Website: [jamesg.blog](https://jamesg.blog/)  
RSS feed: [jamesg.blog/feed/](https://jamesg.blog/feed)

## Meadow
Website: [meadow.cafe](https://meadow.cafe/)  
RSS feeds: [meadow.cafe/feeds/](https://meadow.cafe/feeds/)

## Robert Birming
Main website [robertbirming.com](https://robertbirming.com/)  
Main RSS feed: <input hidden type="text" value="https://robertbirming.com/feed/" id="myInput"><span style="text-decoration:underline 2px solid var(--primary);" onmouseover="style='text-decoration:underline 2px solid var(--darkcolor);cursor:pointer;'" onmouseout="style='text-decoration:underline 2px solid var(--primary);'" onclick="myFunction()">robertbirming.com/feed/</span>
<div style="background:var(--lightcolor);border:2px solid var(--darkcolor);border-radius:10px;padding:10px;">
    <p><b>WARNING ⚠️</b><br>Only paste this into RSS feed viewer. Going to this link into the browser will download a document (not sure why, it's a <a href="https://bearblog.dev/" target="_blank">Bear Blog</a> thing).</p>
</div>


Alt website: [birming.com](https://birming.com/)  
Alt RSS feed: [birming.com/feed.xml](https://birming.com/feed.xml)

<script>
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