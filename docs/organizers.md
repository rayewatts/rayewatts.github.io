---
layout: page
title: The Organizers
permalink: /organizers/
poster_img: /assets/images/blank-square.jpg
poster_alt: TODO! A description of the poster image
---


## Allow us to introduce ourselves

The PSST Challenge is a collaboration between Oregon Health and Science University (OHSU) and Portland State
University (PSU). Our proposed activities will be supported via a grant from the National Institute on Deafness
and Other Communication Disorders NIH (R01-DC015999-04S1), the purpose of which is to promote the use of clinical
datasets of aphasic speech by the mainstream machine learning community, and which includes travel support for
participating students.


<div id="the-psst-people">
{%- for person in site.challenge_organizers -%}
    <div class="person">
        <div class="portrait"><img src="{{person.portrait}}" alt="{{person.portrait_alt}}" /></div>
        <p><strong>{{person.name}}</strong> {{person.bio}}</p>
    </div>
{%- endfor -%}
</div>