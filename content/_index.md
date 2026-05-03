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
  - block: markdown
    content:
      title: "ARVO 2026 Poster Presentation <span style='color: #ef4444; font-weight: bold;'>New</span>"
      subtitle: "Presenting our latest work at ARVO 2026"
      text: |
        <div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; padding: 20px; display: flex; justify-content: center; align-items: center; border: 2px solid #333; border-top: 2px solid #333; border-bottom: 2px solid #333;">
          <div style="width: 95%; max-width: 1400px;">
            <iframe src="/uploads/Adarsh_ARVO26_poster2.pdf" style="width: 100%; aspect-ratio: 16/9; border: 1px solid #ddd; border-radius: 8px;"></iframe>
            <div style="text-align: center; margin-top: 15px;">
              <a href="/uploads/Adarsh_ARVO26_poster2.pdf" download style="padding: 10px 20px; background-color: #059669; color: white; text-decoration: none; border-radius: 5px; display: inline-block;">
                Download Poster
              </a>
            </div>
          </div>
        </div>
    design:
      spacing:
        padding: ["0", 0, "0", 0]
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
