---
title: "Magnet Board Theming"
layout: single
hidden: true
---
Things you need to know before designing your own theme:
- Every theme is a CSS file whose name starts with 'theme-'.
- These files are typically stored in the same directory as
  urdumb.html, although it is likely not a necessary condition.
- Themes must be linked in urdumb.html using something like
   <link rel="stylesheet" href="theme-insertthemenamehere.css" />
- Take inspiration from existing themes: copy the file, change the
  values.
- When a theme is selected in URDUMB, the team colours will be set using
  CSS variables --preferred-team-A-colour and
  --preferred-team-B-colour. The user can still change colours after
  loading the theme.
