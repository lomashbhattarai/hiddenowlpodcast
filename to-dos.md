---
layout: page
title: 
permalink: /to-dos/
---

A list of to-dos.

*(as a rule, I can only add to-dos and never remove it)*

<ul>
{% for toDo in site.data.to-dos  %}
  <li> {{toDo}} </li>
{% endfor %}
</ul>

