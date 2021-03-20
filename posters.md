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
  <h3>✨ Poster Submission Instructions ✨</h3>

Please follow instructions in <a href="https://ggc-stars.github.io/stars2021/update/2021/03/07/poster-submission-instructions.html"> this post </a> to submit your posters.
</div>

<div align="left">
  <h3>✨ Poster Judging Information ✨</h3>

Posters will be judged according to criteria posted <a href="https://ggc-stars.github.io/stars2021/update/2021/03/09/rubrics-feedback-posters.html">here</a>.
<br>
Note: <b>Live presentations of posters are preferred over pre-recorded videos of posters. Submissions with only pre-recorded videos get 1 pt deduction from final score.</b>
</div>

<div align="left">
  <h3>✨ STaRS 2021 Posters (Example) ✨</h3>

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
</div>

<ul>
{% for poster in site.data.stars2021.posters %}
  <li><a href="{{ poster["Poster title"] | datapage_url: '/stars2021/posters' }}">{{poster["Poster title"]}}</a></li>
{% endfor %}
</ul>
---


