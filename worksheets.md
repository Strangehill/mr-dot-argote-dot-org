---
layout: default
title: Worksheets
---

<style>
{% capture style %}
  .printouts a {
   // border: solid 1px black;
  }
{% endcapture %}
{{ style | scssify }}
</style>


<div class="printouts">

<ul>
{% for item in site.worksheets %}
  <li style="border-radius:1em;display:inline-block;padding: 0.5em 1em;list-style:none;background-image: linear-gradient(to right, #DCE,#EEF);">
  <a href="{{ item.url }}"> {{ item.title }} </a>
  </li>
{% endfor %}
</ul>
</div>

