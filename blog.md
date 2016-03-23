---
layout: page
title: Blog
order: 2
permalink: /blog/
---

{::options auto_ids="false" /}

{: .post-list}
{% for post in site.tags.blog %}
* {{ post.date | date: "%b %-d, %Y" }}
  {: .post-meta}

  ## [{{ post.title }}]({{ post.url | prepend: site.baseurl }} "{{ post.title }}"){: .post-link}
  
  {{ post.excerpt }}
{% endfor %}

subscribe to [Atom feed {% include icon-feed.svg %}]({{ "/atom.xml" | prepend: site.baserul }} "Subscribe")
{: .rss-subscribe}
