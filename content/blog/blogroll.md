---
title: "Blogroll" 
date: 2026-05-27
tags: ["posts","lists","websites"]
author: ["Joshua Maynard"]
description: "My blogroll: a list of the blogs I read."
summary: "My blogroll: a list of the blogs I read."
editPost:
    URL: "https://pub.jshmnrd.ca/w/share/0001-blogroll.opml"
    Text: "OPML Download"
showToc: false
disableAnchoredHeadings: false
ShowWordCount: false
layout: dev
build:
  list: never
---
<sup><code>Updated: 2026-06-06</code></sup>

# Blogroll

<br>

<style>
  .post-content p.br-h2 {
    font-weight: 700;
    font-size: 24px;
    margin: 0;
  }
</style>

This is my [blogroll](https://indieweb.org/blogroll), a collection of the blogs I read regularly.

I recommend using [Mire](https://mire.meadow.cafe), as it's a nice minimal reader. You can check out my [blogroll there](https://mire.meadow.cafe/u/jshmnrd/blogroll) too. Here's an <a href="https://pub.jshmnrd.ca/w/share/0001-blogroll.opml" target="_blank">OPML download</a> as well.

<p class="br-h2">Aditya Telange</p>
<p>
  <b>Website:</b>
  <a href="https://adityatelange.in" target="_blank">AdityaTelange.in</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://adityatelange.in/index.xml" target="_blank">adityatelange.in/index.xml</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">Copy</button>
</p>

<p class="br-h2">James G</p>
<p>
  <b>Website:</b>
  <a href="https://jamesg.blog/" target="_blank">JamesG.blog</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://jamesg.blog/feeds/" target="_blank">jamesg.blog/feeds</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://jamesg.blog/feeds/posts.xml">Copy</button>
</p>

<p class="br-h2">Meadow</p>
<p>
  <b>Website:</b>
  <a href="https://meadow.cafe/" target="_blank">Meadow.cafe</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://meadow.cafe/feeds/" target="_blank">meadow.cafe/feed</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://meadow.cafe/feeds/main_rss.xml">Copy</button>
</p>

<p class="br-h2">Robert Birming</p>
<p>
  <b>Website:</b>
  <a href="https://robertbirming.com/" target="_blank">RobertBirming.com</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://robertbirming.com/feed/" target="_blank">robertbirming.com/feed</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://robertbirming.com/feed/">Copy</button>
</p>

<p class="br-h2">Toska</p>
<p>
  <b>Website:</b>
  <a href="https://toska.bearblog.dev/" target="_blank">Toska.bearblog.dev</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://toska.bearblog.dev/feed/" target="_blank">toska.bearblog.dev/feed</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://toska.bearblog.dev/feed/?type=rss">Copy</button>
</p>

<p class="br-h2">Zakhary</p>
<p>
  <b>Website:</b>
  <a href="https://zakhary.dev/" target="_blank">Zakhary.dev</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="https://zakhary.dev/feed.xml" target="_blank">zakhary.dev/feed</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="https://zakhary.dev/feed.xml">Copy</button>
</p>

<!--<p class="br-h2">_</p>
<p>
  <b>Website:</b>
  <a href="#" target="_blank">_</a>
  <br>&emsp;&emsp;&emsp;
  <b>Feed:</b>
  <a href="#" target="_blank">_</a>
  &emsp;&emsp;
  <button class="copy-btn" data-copy="#">Copy</button>
</p>-->

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