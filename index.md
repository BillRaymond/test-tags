---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
hello
{% for post in site.posts %}
    {% for tag in post.tags %}
        Tag: {{tag}}
    {% endfor %}
{% endfor %}

