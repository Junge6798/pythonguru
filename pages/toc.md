---
layout: page
title: Table Of Contents
permalink: /toc/
---

# Table Of Contents

Welcome to the {{ site.title }} learning platform! The whole syllabus is designed based on `Python 3`.
Here you can quickly jump to a particular section.

{% include util/note.html
    text="This syllabus is aimed at people with little programming experience and who want to start
    learning Python."
    icon_class="fa icon-note"
%}

{% include notice.html
    primary="The content of the syllabus is still in building stage."
    secondary="However, you can still begin your learning."
%}

<div class="section-index">
  <hr class="panel-line">
  {% for page in site.toc %}
    {% if page.type != "section" %}
      <div class="entry">
        <h5>
          <a href="{{ page.url | remove: 'index' | prepend: site.baseurl }}">{{ page.title }}</a>
        </h5>
        <p class="mb-0">{{ page.description }}</p>
      </div>
    {% endif %}
  {% endfor %}
</div>
