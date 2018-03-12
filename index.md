---

layout: default
title: 随身笔记

---

#### [个人简介]({{site.baseurl}}/info)

#### 最新文章

{% for post in site.posts %}

+ {{ post.date | date_to_xmlschema | slice: 0, 10 }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})

{% endfor %}


