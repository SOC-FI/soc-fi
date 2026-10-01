---
title: "Providers"
# Providers are data for the home-page table only: never render their own
# pages, and don't render a /providers/ section page either. They stay in
# .Site.Pages (list = always) so the home template can list them.
build:
  render: never
  list: never
cascade:
  build:
    render: never
    list: always
---
