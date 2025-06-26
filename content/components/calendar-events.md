---
title: Calendar Events
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
  - _bookshop_name: design-system/section/calendar-events
    heading: Upcoming Events
    subheading:
    event_feed: >-
      <div id="localist-widget-63214382" class="localist-widget"></div><script
      defer type="text/javascript"
      src="https://cal.wvu.edu/widget/view?schools=wvu&departments=wvu_hub&days=31&num=3&experience=inperson&container=localist-widget-63214382&template=design-system-v3-section"></script>
    postscript:
      text:
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
        name:
        instance:
        edit_mode_only: false
        include_heading_postscript: true
        show: '2024-09-01'
        hide: '2099-09-01'
  - _bookshop_name: design-system/section/columns-2-1
    heading:
    background_image:
    alt_text:
    column_a:
      _bookshop_name: design-system/column/calendar-events
      heading: Events
      subheading:
      event_feed: >-
        <div id="localist-widget-81837159" class="localist-widget"></div><script
        defer type="text/javascript"

        src="https://cal.wvu.edu/widget/view?schools=wvu&departments=wvu_hub&days=31&num=3&experience=inperson&container=localist-widget-81837159&template=dsv2-vertical-mini"></script>
      link_text:
      url:
    column_aa:
      _bookshop_name: design-system/column_sm/calendar-events
      heading: Events
      subheading:
      event_feed: >-
        <div id="localist-widget-81837159" class="localist-widget"></div><script
        defer type="text/javascript"

        src="https://cal.wvu.edu/widget/view?schools=wvu&departments=wvu_hub&days=31&num=3&experience=inperson&container=localist-widget-81837159&template=dsv2-vertical-mini"></script>
      link_text:
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
