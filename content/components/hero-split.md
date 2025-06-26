---
title: Hero - Split
topper:
  _bookshop_name: design-system/topper/default
component_block:
  _bookshop_name: design-system/section/component-doc
  overview_markdown: ''
  when_to_use_markdown: >-
    Use this to feature content that you want to stand out, with a clear call to
    action.
  in_the_wild:
    - text:
      url:
  content_guidelines:
    - content: Heading
      content_type: string
      description: Marketing copy that grabs the user’s attention.
      max_chars: 56
      required: true
    - content: Subheading
      content_type: string
      description: A brief teaser that expands on the heading.
      max_chars: 56
      required: true
    - content: Blurb
      content_type: string
      description: More detailed copy that further elaborates.
      max_chars: 255
      required:
    - content: Call to Action
      content_type:
      description: The action you want the user to take.
      max_chars: 16
      required: true
content_blocks:
  - _bookshop_name: design-system/section/hero-split
    heading: Heading
    background_image:
    alt_text:
    lead: Subheading goes here.
    copy: More text.
    ctas:
      - text: Call to Action
        icon:
        url:
      - text: Call to Action
        icon:
        url:
    postscript_links:
      - text: Another link
        icon:
        url:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle:
      layout:
        buffer:
        margin:
        padding: py-0
        full_bleed: true
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid:
type: component-doc
---
