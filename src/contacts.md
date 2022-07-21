---
layout: page
title: Contact Information
---

<ul>
  {% for contact in collections.contacts.resources %}
    <li>
      <a href="{{ contact.relative_url }}">{{ contact.data.title }}</a>
    </li>
  {% endfor %}
</ul>
