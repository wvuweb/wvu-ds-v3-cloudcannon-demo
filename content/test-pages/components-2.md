---
_schema: guide_page
title: Components 2
topper:
  _bookshop_name: design-system/topper/hero
  label:
  background_image:
  alt_text:
  heading: Heading
  subheading: Subheading.
  markdown:
  ctas: []
  postscript:
    markdown:
    ctas:
  settings:
    styles:
      audience: general
      tone: loud
      color_palette: option-2
      enable_blend: false
      enable_pattern: false
      tint_opacity: '0.7'
      heading_size: display-2
    layout:
      buffer:
      text_placement: mx-auto text-center
    config:
      show_label: true
content_blocks:
  - _bookshop_name: design-system/section/columns-2-1-1
    background_image:
    column_a:
      _bookshop_name: design-system/column/calendar-events
      heading: Events
      subheading: Test Subheading
      event_feed: >-
        <div id="localist-widget-66979106" class="localist-widget"></div><script
        defer type="text/javascript"

        src="https://cal.wvu.edu/widget/view?schools=wvu&departments=alumni&days=31&num=5&experience=inperson&container=localist-widget-66979106&template=dsv2-vertical-mini"></script>
      link_text: View Full Calendar
      url:
    column_aaa:
      _bookshop_name: design-system/column_sm/article-collection
      heading: Articles Test
      tags:
        - Custom Label
      limit: 5
      config:
        show_content: false
    column_bbb:
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
        show_label: true
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
    is_nested: true
  - _bookshop_name: design-system/section/contacts
    heading: Heading
    subheading: Subheading goes here.
    contacts:
      - label: Inquiries
        contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
      - label: 
        contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
      - label: Inquiries
        contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
      - label: 
        contact: 7e020d75-66f0-4628-8b44-f75931dd8bcf
    postscript:
      copy:
      ctas:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle: true
        enable_blend: false
        tint_opacity: '0.7'
        remove_container_background: false
      layout:
        buffer:
        margin:
        max_cols: 20
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: true
        show_content: false
  - _bookshop_name: design-system/section/columns-2-1
    heading: Heading
    background_image:
    alt_text:
    column_a:
      _bookshop_name: design-system/column/factoids
      heading: By the Numbers
      items:
        - pre: According to my source
          stat: 98%
          post: of web designers are cool.
          source: Anonymous
        - pre: According to my source
          stat: 40,000
          post: things happened.
          source: Anonymous
        - pre: Another cool stat is
          stat: 50+
          post: more things happened.
          source: Anonymous
      config:
      styles:
    column_aa:
      _bookshop_name: design-system/column_sm/featurettes-vertical
      heading: Heading
      subheading: Subheading.
      items:
        - title: Item 1 Title
          image: /uploads/guy-sitting-outside.jpg
          alt_text:
          label:
          badge:
          text: Item 1 text.
          ctas:
            - text: Button
              icon:
              url:
        - title: Item 1 Title
          image: /uploads/drone.jpg
          alt_text:
          label:
          badge:
          text: Item 1 text.
          ctas:
      settings:
        styles:
          audience: general
        layout:
        config:
    settings:
      styles:
        audience: general
        tone: reserved
        color_palette: option-4
        bg_subtle:
        enable_blend: false
        tint_opacity: '0.7'
        remove_container_background: false
      layout:
        buffer:
        margin:
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
    is_nested: true
  - _bookshop_name: design-system/section/faculty-members
    heading: Eberly Faculty
    subheading: Subheading goes here.
    tags:
      - Eberly Faculty
    postscript:
      copy:
      ctas:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle: true
        enable_blend: false
        tint_opacity: '0.7'
      layout:
        buffer:
        margin:
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: true
        show_content: false
        show: '2024-09-01'
        hide: '2099-09-01'
  - _bookshop_name: design-system/section/columns-2
    heading: Heading
    subheading: Subheading goes here.
    column_a:
      _bookshop_name: design-system/column/featurettes-vertical
      heading: Heading
      subheading: Subheading.
      items:
        - title: Item 1 Title
          image: /uploads/guy-sitting-outside.jpg
          alt_text:
          label:
          badge:
          text: Item 1 text.
          ctas:
        - title: Item 1 Title
          image: /uploads/drone.jpg
          alt_text:
          label:
          badge:
          text: Item 1 text.
          ctas:
      settings:
        styles:
          audience: general
        layout:
        config:
    column_b:
      _bookshop_name: design-system/column_sm/featurettes-w-icons-vertical
      heading: Heading
      subheading: Subheading.
      items:
        - title: Item 1 Title
          icon: book
          label:
          badge:
          text: Item 1 text.
          ctas:
            - text: CTA
              icon:
              url:
        - title: Item 1 Title
          icon: tree
          label:
          badge:
          text: Item 1 text.
          ctas:
      settings:
        styles:
          audience: general
        layout:
        config:
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
      config:
        edit_mode_only: false
        include_heading_postscript: true
        show: '2024-09-01'
        hide: '2099-09-01'
    is_nested: true
  - _bookshop_name: design-system/section/featurettes-vertical
    heading: Heading
    subheading: Subheading.
    items:
      - title: Item 1 Title
        image: /uploads/drone.jpg
        alt_text:
        label:
        badge:
        text: Item 1 text.
        ctas:
      - title: Item 1 Title
        image: /uploads/guy-sitting-outside.jpg
        alt_text:
        label:
        badge:
        text: Item 1 text.
        ctas:
          - text: Here is my CTA
            icon:
            url:
    postscript:
      copy:
      ctas:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle: true
        enable_blend: false
        tint_opacity: '0.7'
        remove_container_background: false
      layout:
        buffer:
        margin:
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: true
        show: '2024-09-01'
        hide: '2099-09-01'
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid: 4be86e00-49af-4f99-a085-237a781884ef
type: guide
---
