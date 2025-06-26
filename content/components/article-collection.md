---
title: Article Collection
topper:
  _bookshop_name: design-system/topper/default
component_block:
  _bookshop_name: design-system/section/component-doc
  overview_markdown: ''
  when_to_use_markdown: Display a series of featured articles.
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
  - _bookshop_name: design-system/section/article-collection
    heading: Article Collection Heading
    subheading: Subheading goes here.
    tags:
      - Custom Label
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
        padding: py-6 py-xxl-7
        max_cols:
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
        limit:
        show_content: false
        show: '2024-09-01'
        hide: '2099-09-01'
    is_dynamic: true
  - _bookshop_name: design-system/section/columns-2-1
    heading:
    background_image:
    alt_text:
    column_a:
      _bookshop_name: design-system/column/article-collection
      heading: Article Collection Heading
      tags:
        - Custom Label
      postscript:
        copy:
        ctas:
      config:
        limit:
        show_content: false
    column_aa:
      _bookshop_name: design-system/column_sm/article-collection
      heading: Articles
      tags:
        - Custom Label
      limit: 5
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
  - _bookshop_name: design-system/section/article-collection
    heading: Article Collection Heading
    subheading: Subheading goes here.
    tags:
      - Custom Label
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
        margin: mt-n8 mt-xxl-n9
        padding: py-6 py-xxl-7
        max_cols:
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
        limit:
        show_content: false
        show: 2024-09-01T00:00:00-04:00
        hide: 2099-09-01T00:00:00-04:00
    is_dynamic: true
  - _bookshop_name: design-system/section/article-collection
    heading:
    subheading:
    tags:
      - Custom Label
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
        remove_container_background: true
      layout:
        buffer:
        margin: mt-n8 mt-xxl-n9
        padding: py-6 py-xxl-7
        max_cols:
      config:
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
        limit:
        show_content: false
        show: '2024-09-01'
        hide: '2099-09-01'
    is_dynamic: true
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid:
type: component-doc
---
