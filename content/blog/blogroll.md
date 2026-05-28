---
title: "Blogroll" 
date: 2026-05-27
tags: ["posts","lists","websites"]
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
    URL: "https://pub.jshmnrd.ca/w/share/0001-blogroll.opml"
    Text: "OPML Download"
showToc: false
disableAnchoredHeadings: false
ShowWordCount: false
layout: dev
---

This is my [blogroll](https://indieweb.org/blogroll), a collection of the blogs I read regularly.

I recommend using [Mire](https://mire.meadow.cafe), as it's a nice minimal reader. You can check out my [blogroll there](https://mire.meadow.cafe/u/jshmnrd/blogroll) too.

<h2>Aditya Telange</h2>
<b>Website:</b> <a href="https://adityatelange.in" target="_blank">AdityaTelange.in</a><br>
&emsp;&emsp;&emsp;<a href="#!" data-copy="https://adityatelange.in/index.xml">AdityaTelange.in/index.xml</a>
&emsp;&emsp;<button class="copy-btn" data-copy="https://adityatelange.in/index.xml">copy</button>

<ul hidden>
  <li> <!-- Aditya Telange -->
    <a href="https://adityatelange.in/" target="_blank">Aditya Telange</a>
    &emsp;&emsp;
    <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">feed</button>
  </li>
  <li> <!-- Arduin Findeis -->
    <a href="https://arduin.io/" target="_blank">Arduin Findeis</a>
    &emsp;
    <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">feed</button>
  </li>
  <li> <!-- James -->
    <button class="copy-btn" data-copy="https://jamesg.blog/feeds/posts.xml">feed</button>
    &emsp;&emsp;
    <a href="https://jamesg.blog/" target="_blank">James' Coffee Blog</a>
  </li>
  <li> <!-- Meadow -->
    <button class="copy-btn" data-copy="https://meadow.cafe/feeds/main_rss.xml">feed</button>
    &emsp;&emsp;
    <a href="https://meadow.cafe/" target="_blank">Meadow</a>
  </li>
  <li> <!-- Robert Birming-->
    <button class="copy-btn" data-copy="https://robertbirming.com/feed/">feed</button>
    &emsp;&emsp;
    <a href="https://robertbirming.com/" target="_blank">Robert Birming</a>
  </li>
  <li> <!-- Toska -->
    <button class="copy-btn" data-copy="https://toska.bearblog.dev/feed/?type=rss">feed</button>
    &emsp;&emsp;
    <a href="https://toska.bearblog.dev/" target="_blank">Toska</a>
  </li>
  <li> <!-- Zakhary -->
    <button class="copy-btn" data-copy="https://zakhary.dev/feed.xml">feed</button>
    &emsp;&emsp;
    <a href="https://zakhary.dev/" target="_blank">Zakhary</a>
  </li>
</ul>

<ul hidden>
  <li> <!-- Aditya Telange -->
    <a href="https://adityatelange.in/" target="_blank">Aditya Telange</a>
    &emsp;&emsp;
    <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">feed</button>
  </li>
  <li> <!-- Arduin Findeis -->
    <a href="https://arduin.io/" target="_blank">Arduin Findeis</a>
    &emsp;
    <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">feed</button>
  </li>
  <li> <!-- James -->
    <button class="copy-btn" data-copy="https://jamesg.blog/feeds/posts.xml">feed</button>
    &emsp;&emsp;
    <a href="https://jamesg.blog/" target="_blank">James' Coffee Blog</a>
  </li>
  <li> <!-- Meadow -->
    <button class="copy-btn" data-copy="https://meadow.cafe/feeds/main_rss.xml">feed</button>
    &emsp;&emsp;
    <a href="https://meadow.cafe/" target="_blank">Meadow</a>
  </li>
  <li> <!-- Robert Birming-->
    <button class="copy-btn" data-copy="https://robertbirming.com/feed/">feed</button>
    &emsp;&emsp;
    <a href="https://robertbirming.com/" target="_blank">Robert Birming</a>
  </li>
  <li> <!-- Toska -->
    <button class="copy-btn" data-copy="https://toska.bearblog.dev/feed/?type=rss">feed</button>
    &emsp;&emsp;
    <a href="https://toska.bearblog.dev/" target="_blank">Toska</a>
  </li>
  <li> <!-- Zakhary -->
    <button class="copy-btn" data-copy="https://zakhary.dev/feed.xml">feed</button>
    &emsp;&emsp;
    <a href="https://zakhary.dev/" target="_blank">Zakhary</a>
  </li>
</ul>

<div hidden>
  <li> <!-- -->
    <button class="copy-btn" data-copy="#">feed</button>
    &emsp;&emsp;
    <a href="#" target="_blank"></a>
  </li>
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