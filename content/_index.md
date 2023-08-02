---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postgraduate Student
          company: Guangzhou Medical University
          company_url: 'https://www.gzhmu.edu.cn/'
          company_logo: org-new-icon
          location: Guangzhou, China
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
             
        - title: Research Intern
          company: State Key Laboratory of Respiratory Disease
          company_url: 'http://www.sklrd.cn/'
          company_logo: org-respiratory
          location: Guangzhou, China
          date_start: '2021-03-01'
          date_end: '2021-08-31'
          description: |-
            Responsibilities include:
  
            * Participate in paper writing
  
            * Develop basic biology experiment skills
  
            * Participate in the Project of National Natural Science Foundation of China

    design:
      columns: '2'
 
 
 
  - block: collection
    content:
      title: Recent Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      email: tangguolu@stu.gzhmu.edu.cn
      phone: +86 18178969100
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
