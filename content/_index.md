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
      text: |
        <div style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap; gap: 12px 14px; max-width: 1200px; margin: 0 auto; padding: 4px 20px 14px;">
          <a href="/uploads/Adarsh_ARVO26_poster2.pdf" style="display: inline-flex; align-items: center; gap: 10px; padding: 8px 18px; background: linear-gradient(90deg, #064e3b 0%, #047857 50%, #064e3b 100%); border: 1px solid rgba(110,231,183,0.45); border-radius: 999px; box-shadow: 0 4px 16px rgba(4,120,87,0.35); text-decoration: none;">
            <span style="background: #ef4444; color: #ffffff; font-weight: 800; font-size: 0.62rem; padding: 3px 9px; border-radius: 999px; letter-spacing: 1.2px; text-transform: uppercase;">New</span>
            <span style="color: #ffffff; font-weight: 600; font-size: 0.92rem; white-space: nowrap;">ARVO 2026 Poster →</span>
          </a>
          <a href="/publication/" title="Evaluating Device-Reported Image Quality Scores: Towards Task Specific Quality Gate for Deep Learning Retinal OCT Boundary Segmentation" style="display: inline-flex; align-items: center; gap: 10px; padding: 8px 18px; background: linear-gradient(90deg, #7c2d12 0%, #c2410c 50%, #7c2d12 100%); border: 1px solid rgba(254,215,170,0.45); border-radius: 999px; box-shadow: 0 4px 16px rgba(194,65,12,0.35); text-decoration: none;">
            <span style="background: #fde047; color: #7c2d12; font-weight: 800; font-size: 0.62rem; padding: 3px 9px; border-radius: 999px; letter-spacing: 1.2px; text-transform: uppercase;">Coming Soon</span>
            <span style="color: #ffffff; font-weight: 600; font-size: 0.92rem; white-space: nowrap;">Watch this space — next paper in prep</span>
          </a>
          <a href="/uploads/Adarsh-Gadari-CV.pdf" style="display: inline-flex; align-items: center; gap: 10px; padding: 8px 18px; background: linear-gradient(90deg, #1e1b4b 0%, #4338ca 50%, #1e1b4b 100%); border: 1px solid rgba(165,180,252,0.45); border-radius: 999px; box-shadow: 0 4px 16px rgba(67,56,202,0.35); text-decoration: none;">
            <span style="background: #fbbf24; color: #1e1b4b; font-weight: 800; font-size: 0.62rem; padding: 3px 9px; border-radius: 999px; letter-spacing: 1.2px; text-transform: uppercase;">PhD 2027</span>
            <span style="color: #ffffff; font-weight: 600; font-size: 0.92rem; white-space: nowrap;">Applying — CS &amp; AI · Download CV ↓</span>
          </a>
        </div>
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
