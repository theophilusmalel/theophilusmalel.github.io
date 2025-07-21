# Welcome to Jekyll!
#
# This config file is meant for settings that affect your whole blog, values
# which you are expected to set up once and rarely edit after that. If you find
# yourself editing this file very often, consider using Jekyll's data files
# feature for the data you need to update frequently.
#
# For technical reasons, this file is *NOT* reloaded automatically when you use
# 'bundle exec jekyll serve'. If you change this file, please restart the server process.

# Site settings
# These are used to personalize your new site. If you look in the HTML files,
# you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
# You can create any custom variable you would like, and they will be accessible
# in the templates via {{ site.myvariable }}.

title: "Theophilus Malel"
email: "Theophilusmalel@gmail.com"
description: >-
  A highly skilled Network Security Engineer with extensive experience in Fortinet technologies, firewall configurations, SD-WAN, endpoint security, VPNs, and cybersecurity projects. 
  Proven expertise in securing enterprise infrastructure, leading national security deployments, and continuously staying updated with modern security solutions.

#twitter_username: reyparlour
github_username: theophilusmalel
minimal_mistakes_skin: dark
search: true

# Build settings
markdown: kramdown
remote_theme: mmistakes/minimal-mistakes

# Outputting
permalink: /:categories/:title/
paginate: 5
paginate_path: /page:num/
timezone: Africa/Nairobi

include:
  - _pages

# Plugins
plugins:
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-gist
  - jekyll-feed
  - jemoji
  - jekyll-include-cache

author:
  name   : "Theophilus Malel"
  avatar : "/assets/images/bio-photo.jpg"
  bio    : "Network Security Engineer | Fortinet Specialist | Cybersecurity Leader | CyberSecurity Consultant | Ethical Hacker"
  links:
    - label: "LinkedIn"
      icon: "fab fa-fw fa-linkedin"
      url: "https://linkedin.com/in/theophilusmalel"
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/theophilusmalel"
    #- label: "Certifications"
      #icon: "fas fa-fw fa-certificate"
      #url: "https://github.com/reyparlour/certifications"
    - label: "Email"
      icon: "fas fa-fw fa-envelope"
      url: "theophilusmalel@gmail.com"

footer:
  links:
    - label: "LinkedIn"
      icon: "fab fa-fw fa-linkedin"
      url: "https://linkedin.com/in/theophilusmalel"
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/theophilusmalel"
    #- label: "Email"
      #icon: "fas fa-fw fa-envelope"
      #url: "mailto:rey.parlour@example.com"

defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

  # _pages
  - scope:
      path: "_pages"
      type: pages
    values:
      layout: single
      author_profile: true

category_archive:
  type: liquid
  path: /categories/
tag_archive:
  type: liquid
  path: /tags/
```

---






