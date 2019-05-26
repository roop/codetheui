---
layout: default
---

<em><a href="/">Code the UI: UIKit</a></em>

<div style="margin: 1em 0 1em 0">
<div align="left" style="float: left; font-size: 0.9em;">
    {%- if page.prev -%}
    <a href="{{ page.prevurl }}">« {{ page.prev }}</a>
    {%- endif -%}
</div>
<div align="right" style="font-size: 0.9em;">
    {%- if page.next -%}
    <a href="{{ page.nexturl }}">{{ page.next }} »</a>
    {%- endif -%}
</div>
</div>

<article class="post">
  <div class="post-content">
    {{ content }}
  </div>
</article>

<div style="margin-bottom: 1em">
<div align="left" style="float: left; font-size: 0.9em;">
    {%- if page.prev -%}
    <a href="{{ page.prevurl }}">« {{ page.prev }}</a>
    {%- endif -%}
</div>
<div align="right" style="font-size: 0.9em;">
    {%- if page.next -%}
    <a href="{{ page.nexturl }}">{{ page.next }} »</a>
    {%- endif -%}
</div>
</div>


