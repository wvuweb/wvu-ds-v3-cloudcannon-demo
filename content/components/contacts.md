---
title: Contacts
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
  - _bookshop_name: design-system/section/contacts
    heading: Heading
    subheading: Subheading goes here.
    contacts:
      - label: For Inquiries, Contact
        contact: 00a7afd0-ccc1-45b2-8e6f-29286df3a21f
      - label: For Inquiries, Contact
        contact: c950fe4e-3c25-4e99-a07e-840eab35f5c7
      - label: For Inquiries, Contact
        contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
    postscript:
      copy:
      ctas:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle:
        enable_blend: false
        tint_opacity: '0.7'
        remove_container_background: false
      layout:
        buffer:
        margin:
        max_cols:
        padding: py-6 py-xxl-7
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
        show_content: false
  - _bookshop_name: design-system/section/columns-2-1
    heading:
    background_image:
    alt_text:
    column_a:
      _bookshop_name: design-system/column/contacts
      heading: Contacts
      people:
        - label: For Inquiries, Contact
          contact: 00a7afd0-ccc1-45b2-8e6f-29286df3a21f
        - label: For Inquiries, Contact
          contact: c950fe4e-3c25-4e99-a07e-840eab35f5c7
        - label: For Inquiries, Contact
          contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
      config:
        show_content: false
    column_aa:
      _bookshop_name: design-system/column_sm/contacts
      heading: Contacts
      people:
        - label: For Inquiries, Contact
          contact: 00a7afd0-ccc1-45b2-8e6f-29286df3a21f
        - label: For Inquiries, Contact
          contact: c950fe4e-3c25-4e99-a07e-840eab35f5c7
        - label: For Inquiries, Contact
          contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
      config:
        show_content: false
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
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
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
    is_nested: true
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid:
type: component-doc
---
