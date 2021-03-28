---
layout: about
title: Posters
permalink: /posters/
posters:
# use categories for stars2021 and posters/activities/etc
# and use tags for discipline (so it can have multiple)
# go through tags in this page? or show tags next to title?
---
### ✨ Poster Submission Instructions ✨

Please follow instructions in <a href="https://ggc-stars.github.io/stars2021/update/2021/03/07/poster-submission-instructions.html"> this post </a> to submit your posters.

### ✨ Poster Judging Information ✨

Posters will be judged according to criteria posted <a href="https://ggc-stars.github.io/stars2021/update/2021/03/09/rubrics-feedback-posters.html">here</a>.

Note: <b>Live presentations of posters are preferred over pre-recorded videos of posters. Submissions with only pre-recorded videos get 1 pt deduction from final score.</b>

### ✨ STaRS 2021 Posters for Judging ✨

<div class="page-segments">
    <ul class="page-segments-list">
    {% for poster in site.data.stars2021.posters %}
        <li>
            <span class="post-meta">{{ poster["students"] }} - supervised by {{ poster["faculty"] }}</span><br>
            <span>
                <a class="post-link" href="{{ poster["Poster title"] | datapage_url: '/stars2021/posters' }}">
                {{ poster["Poster title"] | escape }}
                </a>
            </span><br>
            <span class="post-excerpt">{{ poster["tags"] }}</span>

        </li>
    {% endfor %}
</ul>
</div>
---


