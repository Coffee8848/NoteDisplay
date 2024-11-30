# 欢迎来到我的笔记库！

这里是我整理的离散数学笔记。你可以在下面找到不同章节的链接。

## 笔记章节

{% for note in site.posts %}

- [{{ note.title }}]({{ note.url }})
  {% endfor %}
