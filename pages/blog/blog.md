---
sitemap:
    lastmod: '2024-09-18 11:45'
    changefreq: daily
allowCSS: default
allowJS: default
show_header_image: false
show_clickthrough: true
show_date: default
is_headless: false
content:
    items:
        - '@self.children'
    order:
        by: date
        dir: desc
    sibling_links: true
render:
    children:
        style: summary
        image: false
        subtitle: true
        category: true
        date: false
        which_date: date
        nested_children: true
child_type: blog_item
admin:
    children_display_order: collection
---

