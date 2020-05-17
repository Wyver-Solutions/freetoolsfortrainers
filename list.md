---
layout: page
title: List of tools
permalink: /list/
---
<p class="center">Disclaimer: Inclusion in this list does not imply a recommendation.</p>

<p class="center">Each situation is different and so you may need to experiment or get personal advice.</p>

<table width="100%" id="toolslist">
    <thead>
        <th>Name</th>
        <th>Categories</th>
        <th>Notes</th>
    </thead>
{% for tool in site.data.tools %}
  <tr>
    <td><a href="{{ tool.url }}" target="_blank">{{ tool.name }}</a></td>
    <td>{{ tool.categories }}</td>
    <td>{{ tool.notes }}</td>
</tr>
{% endfor %}
</table>