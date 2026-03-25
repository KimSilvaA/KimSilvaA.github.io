---
title: "Predictive Modeling of Alzheimer’s Outcomes"
excerpt: "My MS Capstone Project"

header:
  teaser: /assets/images/brain.png
---
## Overview


<style>
table { border-collapse: collapse; width: 50%; }
th, td { border: 1px solid #ccc; padding: 0.5rem; }
</style>

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Category</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    {% for feature in site.data.features %}
    <tr>
      <td>{{ feature.Feature }}</td>
      <td>{{ feature.Category }}</td>
      <td>{{ feature.Description }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
