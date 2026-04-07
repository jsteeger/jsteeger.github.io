---
title: Courses
summary: My courses
type: landing

# cascade:
#   - target:
#       path: '{/courses/*/**}'
#     type: courses
#     params:
#       show_breadcrumb: false

sections:
  - block: collection
    id: courses
    content:
      title: Courses
      filters:
        folders:
          - courses
        # tag: Course
        # kinds:
        #   - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 2
---