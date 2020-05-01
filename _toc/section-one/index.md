---
title: Section One
date: 15th April, 2020 1:00:00
type: section
description: Section One - getting familiar with language
permalink: /toc/section-one/
---

# Welcome to Section One (getting familiar with language)

__Hello!__

Say _Hi_ to Python.

In this section, you will be getting yourself familiar with the Python language.

Python is an interpreted, high-level, general-purpose programming language. Created by `Guido van Rossum` and first
released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant
whitespace. Python is dynamically typed and garbage-collected language and supports multiple programming paradigms, including structured(particularly, procedural), object-oriented, and functional programming.
[(source)](https://en.wikipedia.org/wiki/Python_%28programming_language%29){:target="_blank"}

We will know more about Python in the following sub-sections.

#### Have a wonderful journey in learning Python.

<div class="section-index">
  <hr class="panel-line">
  {% for page in site.toc %}
    {% if page.parent == "/toc/section-one/" %}
      <div class="entry">
        <h5>
          <a href="{{ page.url | remove: 'index' | prepend: site.baseurl }}">{{ page.title }}</a>
        </h5>
        <p class='mb-0'>{{ page.description }}</p>
      </div>
    {% endif %}
  {% endfor %}
</div>
