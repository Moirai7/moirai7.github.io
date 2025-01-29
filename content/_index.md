---
# Leave the homepage title empty to use the site title
title: Lan Zhang
date: 2025-01-29
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: 'News'
      text: >-
        <ul>
        <li><b>[2023-08-08]</b> I'm happy to share that I have joined the School of Informatics, Computing, and Cyber Systems at Northern Arizona University as an Assistant Professor.</li>
        </ul>
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      text: |-
        [See All Publications >>](./publication)
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: teaching
    content:
      title: 'Teaching & Mentoring'
      text: |-
        **Courses at NAU**
        - CS 440 Software Architecture
        - CS 470/570 Artificial Intelligence
        - CS 599 Machine Learning
        - CS 599 Deep Learning
        - CS 567 Advanced Software Assurance

        **Courses at PSU**
        - Cyber 366 Malware analysis

        <br />

        **Current PhD Students**
        - Moiz Abdullah(strating in Fall 2025)
    design:
      columns: '2'
  - block: markdown
    id: service
    content:
      title: 'Services'
      text: |-
        **Technical Program Committee**
        - [EAI ICECI 2024] 
        
        **External Reviewers**
        - [JCS] Journal of Computer Security
        - [TIFS] IEEE Transactions on Information Forensics & Security
        - [JCN] Journal of Computer Networks 
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: lan[dot]zhang[at]nau[dot]edu
      # phone: 
      # appointment_url: 
      address:
        street: SICCS ROOM 210
        city: Flagstaff
        region: AZ
        country: United States
        country_code: US
      autolink: true
    design:
      columns: '2'
---
