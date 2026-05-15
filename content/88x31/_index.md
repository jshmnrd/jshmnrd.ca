---
title: "88x31 Collection"
description: "My 88x31 collection"
ShowBreadCrumbs: false
---

<h1>88x31 Collection</h1>
<p>This is my <a href="https://indieweb.org/88x31" target="_blank">88x31</a> collection, because I can't help but collect things. It's not like many collections, I've curated it very specifically and each one means something special. Click one to visit its original site.</p>
<hr>
<p style="text-align:center;">Link me on your site!&emsp;&emsp;&emsp;<button class="copy-btn" data-copy='<a href="https://jshmnrd.ca" target="_blank"><img alt="jshmnrd.ca" src="https://jshmnrd.ca/88x31.gif"></a>'>Copy Embed Code!</button></p>
<a class="badge" href="https://jshmnrd.ca" target="_blank"><img class="badge" alt="jshmnrd.ca" src="https://jshmnrd.ca/88x31.gif"></a>

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

<hr>

<!-- 88x31 TEMPLATE
<a class="badge" href="#" target="_blank"><img class="badge" alt="#" title="# dd/mm/yyyy" src="#"></a>
-->

<table class="badgegrid">
    <tr>
        <!-- jshmnrd 14/05/2026-->
        <td width="120px"><a class="badge" href="https://jshmnrd.ca" target="_blank"><img class="badge" alt="jshmnrd.ca" title="MY BANNER! (added 14/05/2026)" src="jshmnrd.gif"></a></td>
        <!-- NotByAI 14/05/2026 -->
        <td width="120px"><a class="badge" href="https://notbyai.fyi/" target="_blank"><img class="badge" alt="notbyai.fyi" title="My site is NOT created with any AI! (added 14/05/2026)" src="notbyai.png"></a></td>
        <!-- IndieWeb 14/05/2026 -->
        <td width="120px"><a class="badge" href="https://indieweb.org/" target="_blank"><img class="badge" alt="indieweb.org" title="Support the Indie Web! (added 14/05/2026)" src="indieweb.gif"></a></td>
        <!-- James' Coffee Blog -->
        <td width="120px"><a class="badge" href="https://jamesg.blog/" target="_blank"><img class="badge" alt="jamesg.blog" title="Significant inspiration to me! (added 14/05/2026)" src="james-coffee-blog.png"></a></td>
        <td width="120px"></td>
        <td width="120px"></td>
    </tr>
    <tr>
        <td width="120px"></td>
        <td width="120px"></td>
        <td width="120px"></td>
        <td width="120px"></td>
        <td width="120px"></td>
        <td width="120px"></td>
    </tr>
</table>