---
layout: page
show_meta: false
title: "Τεκμηρίωση των Web APIs της GUNet"
subheadline: "Ενημερωθείτε και κάντε χρήση των APIs"
header:
   image_fullwidth: "unsplash_windows_maselskis.jpg"
permalink: "/apis/"
---
<ul>
    {% for api in site.apis %}
    <li><a href="{{ site.url }}{{ api.url }}">{{ api.title }}</a></li>
    {% endfor %}
</ul>
