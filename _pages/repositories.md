---
layout: page
permalink: /repositories/
title: Projects
description: 
nav: true
nav_order: 3
---

This page contains a list of selected collaborative repositories in which I am/was involved in the development.  
More information is available on my [GitHub profile](https://github.com/VHPL-UIS).

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
