---
# Leave the title empty to use the site title
title: ''
date: 2022-10-24
type: page

# Optional header image (relative to `static/media/` folder).
banner:
  caption: 'Pubications'
  image: ''

sections:
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
