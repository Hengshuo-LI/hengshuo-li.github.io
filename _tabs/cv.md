---
title: CV
layout: default_cv # the default layout is 'page'
icon: fas fa-user-tie
order: 5
---



{% include cv/career-profile.html %}

{% unless site.data.cv.sidebar.education %}
  {% include cv/education.html %}
{% endunless %}

{% include cv/experiences.html %}

{% include cv/certifications.html %}

{% include cv/projects.html %}

{% include cv/oss-contributions.html %}

{% include cv/publications.html %}

{% include cv/recommendations.html %}

{% include cv/skills.html %}