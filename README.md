# Based on https://leo3418.github.io/collections/multilingual-jekyll-site/set-up-polyglot.html

Also pulls from https://github.com/george-gca/multi-language-al-folio/tree/main

UI from https://github.com/nisabmohd/Aria-Docs

# TODO

[x] Github build
[x] Add GH Discussions
[x] Add search indicator
[x] Page navigation logic
  - Next (unless current page == last page)
  - Previous (unless current page == first page)
  - Switch next/previous for `ar` locale
[x] Site navigation on page view
[x] Bread Crumbs for `ar`
[x] Scroll top
[x] Print view
[x] Footer should be at bottom of page
[x] Language switcher for `en` (e.g. `default_lang`)
[x] favicons
[x] Translation documentation


<!-- https://leo3418.github.io/collections/multilingual-jekyll-site/localize-date-format.html -->
{%- assign date_format = site.data.l10n.date_format | default: "%b %-d, %Y" -%}
{{ page.date | date: date_format }}
