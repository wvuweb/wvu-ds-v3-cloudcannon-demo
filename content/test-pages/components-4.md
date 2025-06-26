---
_schema: guide_page
title: Components 4
topper:
  _bookshop_name: design-system/topper/hero
  label:
  background_image:
  alt_text:
  heading: Heading
  subheading: Subheading.
  markdown: ''
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
  - _bookshop_name: design-system/section/place
    heading: Heading
    subheading: Subheading goes here.
    image: /uploads/guy-sitting-outside.jpg
    alt_text:
    text: Descriptive text goes here.
    ctas:
      - text: Call to Action
        url:
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle:
        enable_blend: false
        tint_opacity: '0.7'
      layout:
        buffer:
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
  - _bookshop_name: design-system/section/poster
    heading: Heading
    subheading: Subheading goes here.
    image: /uploads/pride.jpg
    alt_text:
    body:
    ctas:
    postscript_links:
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
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
  - _bookshop_name: design-system/section/columns-2-1-1
    background_image:
    column_a:
      _bookshop_name: design-system/column/faculty-members
      heading: Faculty
      tags:
        - Eberly Faculty
      postscript:
        copy:
        ctas:
      config:
        show_content: false
    column_aaa:
      _bookshop_name: design-system/column_sm/factoids
      heading: By the Numbers
      items:
        - pre: Pre text
          stat: 95%
          post: Post text.
          source: Source
        - pre: Pre text
          stat: 95%
          post: Post text.
          source: Source
        - pre: Pre text
          stat: 95%
          post: Post text.
          source: Source
      config:
        edit_mode_only: false
        source:
          disable: false
      styles:
        container:
          margin_bottom: mb-4
        factoid:
          font: wvu-shout
          size: display-1
          color: text-wvu-gold
        divider:
    column_bbb:
      _bookshop_name: design-system/column_sm/poster
      heading: Headline
      subheading: Here is my subheading.
      label: My Label
      image:
      url:
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
  - _bookshop_name: design-system/section/quote
    quote_text: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis ligula
      rutrum risus suscipit volutpat. Nam a libero eu magna vulputate elementum.
      Duis id lacinia risus. Integer et dolor elit. Curabitur luctus ut magna id
      pharetra.
    quote_author: Firstname Lastname
    title: Professor of Psychology
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
        max_cols: 12
        padding: py-6 py-xxl-7
      config:
        edit_mode_only: false
        include_heading_postscript: false
        show: '2024-09-01'
        hide: '2099-09-01'
  - _bookshop_name: design-system/section/social-media-accounts
    heading: Follow Us
    items:
      - platform: Facebook
        icon: facebook
        username:
        url: https://www.wvu.edu
      - platform: Instagram
        icon: instagram
        username:
        url:
      - platform: Twitter / X
        icon: x-twitter
        username:
        url:
      - platform: YouTube
        icon: youtube
        username:
        url: https://www.wvu.edu
    settings:
      styles:
        audience: general
        tone: default
        color_palette: option-1
        bg_subtle:
        enable_blend: false
        tint_opacity: '0.7'
      layout:
        buffer:
        margin:
        padding: py-5
      config:
        edit_mode_only: false
        include_heading_postscript: false
properties:
  exclude_from_navigation: false
  exclude_from_search_engines: false
  meta_description:
  social_image:
uuid: 4e048e0e-9353-4669-b102-d12444bf6794
type: guide
---
