---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome to my Personal Website!

I am Dan and this is my website. I hope you enjoy poking around.

{% assign image_files = site.static_files | where: "image", true %}
{% for im in image_files %}
    {{ im.path }}
{% endfor %}