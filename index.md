---
layout: page
title: Leonwiki
head: 一个新的开始
---

“你可以像疯狗那样对周围的一切愤愤不平，你可以诅咒命运，但是等到最后一刻，你还是得平静的放手而去。”
可以肯定的是，在一个不是很好的环境里，时间总是被努力与竞争毫不费力的研碎。关系和利益，个性与顺从，真真AND假假，平凡的一切成为嫁衣和炮灰是如此正常和应该。
我要在这里留下点什么，哪怕是打针吃药的碎碎念。因为这样，有时候，我感觉和前一天不一样了。

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


