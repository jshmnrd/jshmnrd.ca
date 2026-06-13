---
title: "Blogroll"
emoji: "🗞"
layout: "page"
description: "My blogroll: a list of the blogs I read."
ShowBreadCrumbs: false
---

<style>
  .post-content p.br-h2 {
    font-weight: 700;
    font-size: 21px;
    margin: 0;
  }
</style>

This is my [blogroll](https://indieweb.org/blogroll), a collection of the blogs I read regularly.

I recommend using [Mire](https://mire.meadow.cafe), as it's a nice minimal reader. You can check out my [blogroll there](https://mire.meadow.cafe/u/jshmnrd/blogroll) too. Here's an <a href="https://pub.jshmnrd.ca/w/share/0001-blogroll.opml" target="_blank">OPML download</a> as well.

---

<p class="br-h2">Aditya Telange</p>
<p>
  <b>Website:</b>
  <a href="https://adityatelange.in" target="_blank">AdityaTelange.in</a>
  <br>
  <button class="copy-btn" data-copy="https://adityatelange.in/index.xml">Copy RSS</button>
  &emsp13;
  <a href="https://adityatelange.in/index.xml" target="_blank">adityatelange.in/index.xml</a>
</p>

<p class="br-h2">Among Cats and Books</p>
<p>
  <b>Website:</b>
  <a href="https://elmc.at/" target="_blank">elmc.at</a>
  <br>
  <button class="copy-btn" data-copy="https://elmc.at/feed/">Copy RSS</button>
  &emsp13;
  <a href="https://elmc.at/feed/" target="_blank">elmc.at/feed</a>
</p>

<p class="br-h2">Brentter</p>
<p>
  <b>Website:</b>
  <a href="https://brentter.com/" target="_blank">brentter.com</a>
  <br>
  <button class="copy-btn" data-copy="https://brentter.com/index.xml">Copy RSS</button>
  &emsp13;
  <a href="https://brentter.com/index.xml" target="_blank">brentter.com/index.xml</a>
</p>

<p class="br-h2">Heather Buchel</p>
<p>
  <b>Website:</b>
  <a href="https://heather-buchel.com/" target="_blank">heather-buchel.com</a>
  <br>
  <button class="copy-btn" data-copy="https://heather-buchel.com/feed/feed.xml">Copy RSS</button>
  &emsp13;
  <a href="https://heather-buchel.com/feed/feed.xml" target="_blank">heather-buchel.com/feed/feed.xml</a>
</p>

<p class="br-h2">James G</p>
<p>
  <b>Website:</b>
  <a href="https://jamesg.blog/" target="_blank">JamesG.blog</a>
  <br>
  <button class="copy-btn" data-copy="https://jamesg.blog/feeds/posts.xml">Copy RSS</button>
  &emsp13;
  <a href="https://jamesg.blog/feeds/" target="_blank">jamesg.blog/feeds</a>
</p>

<p class="br-h2">Meadow</p>
<p>
  <b>Website:</b>
  <a href="https://meadow.cafe/" target="_blank">Meadow.cafe</a>
  <br>
  <button class="copy-btn" data-copy="https://meadow.cafe/feeds/main_rss.xml">Copy RSS</button>
  &emsp13;
  <a href="https://meadow.cafe/feeds/" target="_blank">meadow.cafe/feed</a>
</p>

<p class="br-h2">Nishiki</p>
<p>
  <b>Website:</b>
  <a href="https://nshki.com/" target="_blank">nshki.com</a>
  <br>
  <button class="copy-btn" data-copy="https://nshki.com/feed.xml">Copy RSS</button>
  &emsp13;
  <a href="https://nshki.com/feed.xml" target="_blank">nshki.com/feed.xml</a>
</p>

<p class="br-h2">Robert Birming</p>
<p>
  <b>Website:</b>
  <a href="https://robertbirming.com/" target="_blank">RobertBirming.com</a>
  <br>
  <button class="copy-btn" data-copy="https://robertbirming.com/feed/">Copy RSS</button>
  &emsp13;
  <a href="https://robertbirming.com/feed/" target="_blank">robertbirming.com/feed</a>
</p>

<p class="br-h2">Toska</p>
<p>
  <b>Website:</b>
  <a href="https://toska.bearblog.dev/" target="_blank">Toska.bearblog.dev</a>
  <br>
  <button class="copy-btn" data-copy="https://toska.bearblog.dev/feed/?type=rss">Copy RSS</button>
  &emsp13;
  <a href="https://toska.bearblog.dev/feed/" target="_blank">toska.bearblog.dev/feed</a>
</p>

<p class="br-h2">Zakhary</p>
<p>
  <b>Website:</b>
  <a href="https://zakhary.dev/" target="_blank">Zakhary.dev</a>
  <br>
  <button class="copy-btn" data-copy="https://zakhary.dev/feed.xml">Copy RSS</button>
  &emsp13;
  <a href="https://zakhary.dev/feed.xml" target="_blank">zakhary.dev/feed</a>
</p>

<!--
<p class="br-h2">_</p>
<p>
  <b>Website:</b>
  <a href="#" target="_blank">_</a>
  <br>
  <button class="copy-btn" data-copy="#">Copy RSS</button>
  &emsp13;
  <a href="#" target="_blank">_</a>
</p>
-->

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

*Updated: 2026-06-11*