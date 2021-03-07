---
layout: poster
title: Example poster title
students: Student Name
faculty: Dr Faculty Name
poster_file: 'Analysim SfN Global Connectome Jan 2021'
video_kaltura: 1_2dkygr62
tags: biology it
# TODO:
# - and use tags for discipline
# - use a layout to auto display the content below
---

Submit your poster as a PDF file like one below. Also upload a video file as MP4 or MKV (see below).

{%- assign poster_file = page.path | split: "/" | pop | pop | join: "/" | append: "/images/" | append: page.poster_file -%}
[![poster thumbnail]({{ poster_file | append: ".png" | relative_url }})]({{ poster_file | append: ".pdf" | relative_url }})

<iframe id="kaltura_player" src="https://cdnapisec.kaltura.com/p/2022371/sp/202237100/embedIframeJs/uiconf_id/40989281/partner_id/2022371?iframeembed=true&playerId=kaltura_player&entry_id=1_2dkygr62&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[leadWithHTML5]=true&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_332bbn8b" width="853" height="880" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Kaltura Player"></iframe>

