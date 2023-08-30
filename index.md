---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
# layout: home
# author_profile: true

layout: splash
permalink: /
title: Scale your web app
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header-dark-cubes-bw.jpeg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  actions:
    - label: "Estimate your project"
      url: "/contact/"
excerpt: >
  Choose a proven technical partner to develop and scale your JavaScript or PHP web application.
feature_row:
  - image_path: /assets/images/feature-development-ltr.jpg
    alt: "development"
    title: "Web development"
    excerpt: "We do full-stack web development with modern JavaScript frameworks and scalable server-side technologies."
    url: "/services/#full-stack-web-development"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/feature-infrastructure2.jpg
    alt: "infrastructure"
    title: "Web infrastructure"
    excerpt: "From bare metal to cloud, server to VM, and container to serverless, we've scaled real-world systems for decades."
    url: "/services/#web-infrastructure"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/feature-legacy.jpg
    alt: "modernization"
    title: "Legacy app modernization"
    excerpt: "Successful applications last, and technical debt accumulates. We modernize LAMP stacks and respect the legacy."
    url: "/services/#modernizing-legacy-applications"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

{% include feature_row %}

<!--
<h2>About Grimes IT</h2>

{% assign author = page.author | default: page.authors[0] | default: site.author %}
{% assign author = site.data.authors[author] | default: author %}
  {% if author.avatar %}
    <div class="author__avatar">
      <a href="{{ author.home | default: '/' | absolute_url }}">
        <img src="{{ author.avatar | relative_url }}" alt="{{ author.name }}" itemprop="image" class="u-photo">
      </a>
    </div>
  {% endif %}
  -->