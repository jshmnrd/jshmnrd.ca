---
title: "Blog Links Update"
description: "I've updated the links on my blog"
summary: "I've updated the links on my blog"
tags: ["posts","blog","update","hugo","site admin"]
date: 2026-06-06
postID: "002"
---

So I've been inspired to update the way my blog (this blog) page works.

I was inspired to do this by [Meadow](https://meadow.cafe/), who have given their posts an ID. For example, as of writing this, their most recent post is "0074 - the world is not made up of words" with an ID of 74.

![Screenshot of Meadow's blog list](https://pub.jshmnrd.ca/w/img/6001-MeadowBlogList.png#center)

I really like this concept of giving your posts an ID, but don't want it in the title.  
**So, I did it the *me* way**....which is just the Hugo way since I build this site with Hugo.

It was pretty easy actually. I just edited my ```post_meta.html``` partial:

```html
{{- if not .Date.IsZero -}}
{{- $scratch.Add "meta" (slice (printf "<span title='%s'>%s</span>" (.Date) (.Date | time.Format (default "January 2, 2006" site.Params.DateFormat)))) }}
{{- end }}

{{- if (.Param "ShowReadingTime") -}}
{{- $scratch.Add "meta" (slice (i18n "read_time" .ReadingTime | default (printf "%d min" .ReadingTime))) }}
{{- end }}
```
...and added this snippet between these two parameters:

```html
{{- with .Params.postID -}}
{{- $scratch.Add "meta" (slice (printf "ID %s" .)) }}
{{- end }}
```

...so the final snippet looks like this:

```html
{{- if not .Date.IsZero -}}
{{- $scratch.Add "meta" (slice (printf "<span title='%s'>%s</span>" (.Date) (.Date | time.Format (default "January 2, 2006" site.Params.DateFormat)))) }}
{{- end }}

{{- with .Params.postID -}}
{{- $scratch.Add "meta" (slice (printf "ID %s" .)) }}
{{- end }}

{{- if (.Param "ShowReadingTime") -}}
{{- $scratch.Add "meta" (slice (i18n "read_time" .ReadingTime | default (printf "%d min" .ReadingTime))) }}
{{- end }}
```

Then in the front matter, I can add whatever ```postID``` I want.

```yaml
---
postID: "002"
---
```

This change of URL format also required me to update the URL of my first post, which was pretty easy - I just changed the file name and added the previous URL as an alias (a default feature in Hugo, as I understand). looks like this:

```yaml
---
aliases:
  - /blog/2026-05-22-powrss/
---
```

These changes have motivated me to write more which is nice. I'm also quite proud of myself for figuring it out. That said, I'm not a pro so if there was a better way to do this, I'd love to [know](https://jshmnrd.ca/contact/)!

Anyways that's all. Thanks for reading! :)