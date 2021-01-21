---
title: Památky Náchoda
order: 40
---
<div markdown="1" style="text-align: center">

## Památky hradu, města a panství Náchoda, i vlastníkův jeho.

Sepsal

## Josef Myslimír Ludvík,

někdy farář na Bohušíně, posléz na odpočinutí co oltářník ve Skalici nad Úpou.


## DÍL 1.

(s vyobrazením Náchoda) \\
 V Hradci Králové, 1857. \\
 Tiskem Lad. Pospíšila.
</div>

{% assign pages_list = site.pamatky-nachoda | sort:"order" %}

{% for node in pages_list %}
<a href="{{ node.url }}">{{ node.title }}</a>
{% endfor %}
