---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: See my latest publication through ORCID
          icon: academicons/orcid
          url: https://orcid.org/my-orcid?orcid=0000-0002-2757-6718
        - text: Find the Sex- and Gender-Based Analysis tool - 5 Item (SGBA-5) here
          icon: custom/clipboard-list2
          url: https://figshare.com/articles/journal_contribution/Sex-_and_gender-based_analysis_tool_5-item_v1_0_/29090615?file=54611480
#        - text: Connect with me on LinkedIn
#          icon: brands/linkedin
#          url: https://linkedin.com
---
