---
title: Blog
nav:
  order: 4
  tooltip: Musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Blog

<!-- Twitter embeds from https://publish.twitter.com/ -->

<a class="twitter-timeline" data-width="400" data-height="400" href="https://twitter.com/IC_ArmenianMyco?lang=en">Tweets by ICArmenian-Mycologists</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}

<a href="https://twitter.com/IC_ArmenianMyco?lang=en" class="twitter-follow-button" data-show-count="false">Follow @IC_ArmenianMyco</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<a href="https://twitter.com/intent/tweet?screen_name=IC_ArmenianMyco" class="twitter-mention-button" data-show-count="false">Tweet to @IC_ArmenianMyco</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}

{% include centerer.html html=html %}

## <i class="fas fa-newspaper"></i>Blog

{% include blog-list.html %}

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
