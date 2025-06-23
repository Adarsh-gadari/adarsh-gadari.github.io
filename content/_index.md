---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"
  # Apply background to entire page
  # css_class: dark
  background:
    color: black
    # image:
    #   # Add your image background to `assets/media/`.
    #   filename: blue_bg_flipped.png
    #   filters:
    #     brightness: 1.0
    #   size: cover
    #   position: center
    #   parallax: false
sections:
  - block: resume-biography-3
    # design:
    #   css_class: "bio-white-text"
    #   columns: 2

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      # css_class: "bio-white-text"
      view: article-grid
      columns: 2


  # - block: cta-card
  #   content:
  #     title: "Join Them too!"
  #     text: "Become part of our community."
  #     button:
  #       text: "Sign Up"
  #       url: "/signup/"
  #   design:
  #     card:
  #       css_class: "bg-blue-700 cta-narrow cta-left"
  #       css_style: "border: 2px solid #fff;"


  # - block: cta-card
  #   content:
  #     title: "Join US too!"
  #     text: "Become part of our community."
  #     button:
  #       text: "Sign Up"
  #       url: "/signup/"
  #   design:
  #     card:
  #       css_class: "bg-blue-700 cta-narrow cta-right"
  #       css_style: "border: 2px solid #fff;"
  #       column: 2 
---
