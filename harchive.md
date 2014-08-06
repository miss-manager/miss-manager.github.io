---
layout: page
title: Archive
description: An archive of the wisdom of Gertrude Belcher.
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}