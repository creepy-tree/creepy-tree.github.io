---
layout: page
title: About
order: 1
permalink: /about/
---

At Creepy Tree Productions, we make games that encourage empathy and
connection by giving the player agency over their actions, and giving
those actions lasting effects in the game world.

# Who Are We?

{: .people-list }
{% for person in site.people %}
* {% include about.html person=person %}
{% endfor %}
