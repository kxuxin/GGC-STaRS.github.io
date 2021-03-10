---
layout: about
title: Posters
permalink: /posters/
posters:
# use categories for stars2021 and posters/activities/etc
# and use tags for discipline (so it can have multiple)
# go through tags in this page? or show tags next to title?
---
<div align="left">
  
  <h1>✨ JEYLL YAT THEME ✨</h1>

</div>

# Poster Submission Instructions

Please follow instructions in [this post](https://ggc-stars.github.io/stars2021/update/2021/03/07/poster-submission-instructions.html) to submit your posters.

# Poster Judging Information

Posters will be judged according to criteria posted [here](https://ggc-stars.github.io/stars2021/update/2021/03/09/rubrics-feedback-posters.html).

Note: **Live presentations of posters are preferred over pre-recorded videos of posters. Submissions with only pre-recorded videos get 1 pt deduction from final score.**

# STaRS 2021 Posters (Example)

<div class="page-segments">
    <ul class="page-segments-list">
        {% assign items = site.categories.stars2021 | where_exp: "post", 'post.categories[1] == "posters" ' %}
        {% for item in items %}
            {% if item != nil %}
            <li> {% include views/post-item.html %} </li>
            {% endif %}
        {% endfor %}
    </ul>
</div>

---


