---
layout: about
title: Posters
permalink: /posters/
posters:
# use categories for stars2021 and posters/activities/etc
# and use tags for discipline (so it can have multiple)
# go through tags in this page? or show tags next to title?
---

# STaRS 2021 Posters

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

# STaRS Posters Rubrics Feedback

**Live presentations of posters are preferred over pre-recorded videos of posters. Submissions with only pre-recorded videos get 1 pt deduction from final score.**

