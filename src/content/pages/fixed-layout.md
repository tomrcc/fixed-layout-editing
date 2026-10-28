---
_schema: fixed
layout: fixed
title: Fixed Layout
seo:
  page_description: >-
    A page whose section order is set by the layout, while every section stays
    a live-rendering component in the Visual Editor.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
hero:
  heading: A fixed layout, built from components
  subheading: >-
    This page reuses the **same components** as the page builder, but the
    layout decides their order. Editors change the content of each section;
    they can't move, add or remove sections.
  image:
    image_path: /src/assets/images/transparent-bg/undraw-data-input.svg
    alt_text: An illustration of someone filling in a form on a large screen.
  button:
    text: See the page builder
    link: /
intro:
  heading: Why components instead of plain editable regions?
  text_content: >-
    Text and image regions only swap content in place. Wrapping each section in
    a component region means the whole section re-renders in the Visual Editor
    whenever its data changes, so anything computed in the template updates
    live too.


    Try these on this page:


    - Clear the heading of this block and watch the heading element disappear.

    - Add a link to the button on the next section and watch the button appear.

    - Toggle **Flipped** on either side-by-side section to swap its image side.

    - Pick a new image and see it run through the same image pipeline as the
    live site.
feature:
  heading: One component, two places
  text_content: >-
    The two side-by-side sections are the same `LeftRight` component the page
    builder uses, bound to separate fields in this page's front matter.


    Developers reuse this layout for any page that needs a set structure, such
    as landing pages or campaign pages, without writing new components.
  image:
    image_path: /src/assets/images/transparent-bg/undraw-hello.svg
    alt_text: An illustration of someone sitting at a desk with a monitor and books.
  flipped: false
  button:
    text: Read the docs
    link:
closing:
  heading: Structure for developers, content for editors
  text_content: >-
    The order of sections lives in `src/layouts/FixedPage.astro`. To change it,
    a developer edits the layout, and every page using it follows.


    Editors still get inline text editing, image pickers and sidebar controls
    for every field.
  image:
    image_path: /src/assets/images/transparent-bg/undraw-startup.svg
    alt_text: An illustration of someone sitting at a desk.
  flipped: true
  button:
    text: CloudCannon Docs
    link: https://cloudcannon.com/documentation/
---
