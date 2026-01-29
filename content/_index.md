---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          attachment: fixed
          # parallax: false
  - block: collection
    id: research
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
    content:
      title: Research
      text: ""
      count: 6
      filters:
        folders:
          - publication
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: resume-experience
    id: experience
    content:
      filters:
        - type: experience
          username: admin
          show_more: false
    design:
      # Hugo date format
      date_format: '2006'
      # Education or Experience section first?
      is_education_first: false

  - block: markdown
    id: projects
    content:
      title: Projects
      text: |-
        I have participated and contributed in the following projects:

        - **CARAML**: 2025 - Present
        - **[Greece4.0](https://greece40.gr/)**: 2024 - 2025
        - **[I.C.Humans](https://sites.google.com/view/ichumans/home)**: 2023 - 2025
        - **[ACTYS](https://actys.ims.forth.gr/)**: 2022 - 2024
      
    design:
      view: list
      columns: 1

  - block: experience
    id: education
    content:
      filters:
        type: education
      username: admin
      show_more: false
    design:
      # Hugo date format
      date_format: 'January 2006'
      is_education_first: True

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  
  - block: markdown
    id: contact
    content:
      title: 'Contact Info'
 
      text: |-
        Feel free to [e-mail](mailto:nikodim@ics.forth.gr) me. 
        <table borderwidth="0">
        <tbody>
        <tr><td width="15%"><strong>Address:</strong></td><td>Institute of Computer Science, <br>Foundation for Research and Technology - Hellas <br>N. Plastira 100, Vassilika Vouton, GR-700 13 <br>Heraklion, Crete, Greece</td></tr>
        <tr><td><strong>Building:</strong></ul></td><td>AMI facilities</td></tr>
        <tr><td><strong>Office:</strong></ul></td><td>2.16</td></tr>
        <tr><td><strong>Phone:</strong></td><td>+30 2811 392540</td></tr>
        </tbody></table>
    design:
      columns: 1
    # design:
    #   card:
        # Card background color (CSS class)
      # css_class: "bg-primary-700"
      # css_style: ""
---
