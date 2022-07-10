---
layout: page
title: Contact
permalink: /contact/
---


<table>
  {%- for contact in site.data.contacts %}
  <tr>
    <td>{{ contact.type }}</td>
    <td>{{ contact.value }}</td>
  </tr>
  {%- endfor %}
</table>