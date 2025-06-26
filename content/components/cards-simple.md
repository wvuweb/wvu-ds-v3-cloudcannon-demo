---
title: Cards - Simple
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
  - _bookshop_name: design-system/section/cards-simple
    heading: Heading
    subheading: Subheading.
    items:
      - title: Item 1 Title
        image:
        alt_text:
        label:
        badge:
        text: Item 1 text.
        url:
      - title: Item 1 Title
        image:
        alt_text:
        label:
        badge:
        text: Item 1 text.
        url:
      - title: Item 1 Title
        image:
        alt_text:
        label:
        badge:
        text: Item 1 text.
        url:
    postscript:
      copy:
      ctas:
    settings:
      styles:
        audience: general
        tone: default
        card_c: option-2
        bg_subtle:
        enable_blend: false
        tint_opacity: '0.7'
        remove_container_background: false
      layout:
        buffer:
        margin:
        padding: py-6 py-xxl-7
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
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
