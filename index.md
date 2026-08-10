\---

layout: default

title: Home

\---



\# Abhiram's Embedded Systems Journey



Documenting what I learn as I rebuild my embedded fundamentals — from C pointers to RTOS to Linux drivers.



\## Latest posts

{% for post in site.posts %}

\- \[{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}

{% endfor %}

