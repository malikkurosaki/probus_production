---
title: home
layout: default
type: menu
description: ini keterangan home
permalink: /home/
---

```js
var home = "ini adalah home"
```

{% for post in site.posts %}
    {{ post.title }}
{% endfor %}