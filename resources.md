---
layout: page
title: Resources
subtitle: Dont't know where to start? We got your back!
cover-img: /assets/img/banner6.jpg
---
<ul class="pagination blog-pager">
  {% for resource in site.resources limit:2 %}
  <li class="page-item">
    <a class="page-link" href="{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.title }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
<ul class="pagination blog-pager">
  {% for resource in site.resources limit:2 offset:2 %}
  <li class="page-item">
    <a class="page-link" href="{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.title }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
<ul class="pagination blog-pager">
  {% for resource in site.resources limit:2 offset:4 %}
  <li class="page-item">
    <a class="page-link" href="{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.title }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
<ul class="pagination blog-pager">
  {% for resource in site.resources limit:2 offset:6 %}
  <li class="page-item">
    <a class="page-link" href="{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.title }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>
<ul class="pagination blog-pager">
  {% for resource in site.resources limit:2 offset:8 %}
  <li class="page-item">
    <a class="page-link" href="{{ resource.link }}" data-toggle="tooltip" data-placement="top" >{{ resource.title }}</a>
  </li>
  <br>
  {% endfor %}  
</ul>