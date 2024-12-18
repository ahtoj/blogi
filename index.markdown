---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div id="archives">
    Categories:
    {% for category in site.categories %}
    <ul style="display: inline; margin-left:0;">
        {% capture category_name %}{{ category | first }}{% endcapture %}
        <li style="display: inline;">{{ category_name }}</li>
    </ul>
    {% endfor %}
</div>
