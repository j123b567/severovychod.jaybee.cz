---
title: Památky Náchoda
order: 40
---
<style>
.center, .center p{
 text-align: center;
}
</style>
<div markdown="1" class="center">

# Památky hradu, města a panství Náchoda, i vlastníkův jeho.

Sepsal

## Josef Myslimír Ludvík,

někdy farář na Bohušíně, posléz na odpočinutí co oltářník ve Skalici nad Úpou.


## DÍL 1.

(s vyobrazením Náchoda) \\
 V Hradci Králové, 1857. \\
 Tiskem Lad. Pospíšila.
</div>

| Příloha | Velikost |
|---------|----------|
| [Památky Náchoda Ludvík.pdf]({{ site.baseurl }}/files/Pamatky Nachoda Ludvik.pdf)       | 2.0 MiB         |

{% assign pages_list = site.pamatky-nachoda | sort:"order" %}

{% for node in pages_list %}
<a href="{{ node.url }}">{{ node.title }}</a>
{% endfor %}
