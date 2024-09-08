---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
show_sidebar: true
var: 5 var value
title: polo

---



👋, I'm Philips Prince.

- You are probably here because I forced you to. Thanks for coming in.
- I spent my time reading, writing a little, surfing blogs.

{{ "hi" | capitalize }}

{% if page.show_sidebar %}
  <div class="sidebar">
    sidebar content is awesome
  </div>
{% endif %}

<h1>{{ "Hello World!" | downcase }}</h1>

{{page.var}}

{% if page %}
  Hello {{ page.title }}!
{% endif %}