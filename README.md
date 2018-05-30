
# Keyword Tags using Browser Web Components

This is my first tryout of browser web components. I made a keyword tags component, and did a [YouTube presentation](https://www.youtube.com/watch?v=ZhbM1pG38eg&feature=youtu.be) on my findings!

[Live Demo](http://www.mikecirone.com/keyword-tags/)

## Web Components - 3 Main Aspects

  - The actual web component part
  - shadow DOM
  - templates and slots

Below discusses having global styling apply to shadow DOM. Summary: all measures to achieve this are deprecated.

https://stackoverflow.com/questions/25211111/can-shadow-dom-elements-inherit-css?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa

## TODO:

  - test that things work right with multiple component instances
  - bug: input changes height if no tags in it
  - bug: can add an empty tag
