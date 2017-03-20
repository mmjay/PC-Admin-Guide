---
layout: post
href: "#introduction"
title: Getting Started
h2:
 - title: "Introduction"
   href: "#introduction"
 - title: "Version control"
   href: "#version-control"
---
## Introduction
This administrative guide documents standard operating procedures in External Affairs. If you have any ideas or comments on how to improve this guide, please send us feedback at [EA (Admin)@peacecorps.gov](mailto:EAAdmin@peacecorps.gov).

This guide is best viewed in Google Chrome.

## Version control
<table class="table table-hover table-responsive">
  <thead class="thead-default">
    <tr>
    {% for header in site.data.version.keys %}
      <th>{{header}}</th>
    {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.version.content %}
    <tr>
    {% for column in row %}
      <td>{{column}}</td>
    {% endfor %}
    </tr>
    {% endfor %}
  </tbody>
</table>
