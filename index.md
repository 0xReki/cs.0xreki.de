---
title: Custom Schema
layout: 2021/schema-home
---
# Custom Schema

## Classes

{% assign pages = site.pages
  | where: "type", "Class" %}

<!-- markdownlint-disable MD033 -->
<ul>{% for page in pages %}
 {% unless page.subclass-of contains 'schema' %}{% continue %}{% endunless %}
  <li>
    <a href="{{ page.url }}" class="context-cs">{{ page.title }}</a>
    {% assign subpages = site.pages | where: 'subclass-of', page.url %}
    <ul>{% for subpage in subpages %}
      <li>
        <a href="{{ subpage.url }}" class="context-cs">{{ subpage.title }}</a>
      </li>{% endfor %}
    </ul>
  </li>{% endfor %}
</ul>

## Properties

{% assign pages = site.pages
  | where: "type", "Property" %}

<ul>{% for page in pages %}
  <li><a href="{{ page.url }}" class="context-cs">{{ page.title }}</a></li>{% endfor %}
</ul>
<!-- markdownlint-enable MD033 -->
