---
layout: page
title: Contact
order: 3
permalink: /contact/
---

{: .people-list}
* {: style="margin-bottom:2em;"} {% include contact.html person=site.contact profile-picture-size="large" icon-color=site.icon-color %}
{% for person in site.people %}
* {% include contact.html person=person profile-picture-size="large" icon-color=site.icon-color %}
{% endfor %}