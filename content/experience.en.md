---
title: 'Experience'
summary: 'Experience and education of Ryusuke Miyazaki (宮崎 竜輔): The University of Electro-Communications, Institute of Science Tokyo.'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: collection
    id: activities
    content:
      title: Awards & Activities
      text: Awards, volunteering, qualifications, and more. Click a title for details.
      count: 0
      filters:
        folders:
          - activities
        sort_by: Date
        sort_ascending: false
    design:
      view: date-title-summary
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: me
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: me
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: me
---
