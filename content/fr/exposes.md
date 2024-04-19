---
# Leave the title empty to use the site title
title: ''
date: 2022-10-24
type: landing

# Optional header image (relative to `static/media/` folder).
banner:
  caption: 'Exposés'
  image: ''

sections:
  - block: collection
    content:
      title: 2024
      filters:
        folders:
          - exposes
        exclude_featured: true
    design:
      columns: '2'
      view: compact
---