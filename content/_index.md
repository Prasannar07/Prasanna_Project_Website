---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 80%
      icon: python
      icon_pack: fas
      name: Python
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: ROCHESTER INSTITUTE OF TECHNOLOGY
      company_logo: RIT_logo
      company_url: ""
      date_end: ""
      date_start: "2023-01-01"
      description: |2-
          Responsibilities include:
          * Utilizing ML techniques like decision trees and random forests to classify uncertainty in future coastal damages and adaptation costs from mean sea-level rise as high-end/ non-high end using Python.
          * Performing hyper-parameter tuning, cross validation, and feature importance to increase the efficiency of the model. (Using Pandas, NumPy, SciKit-Learn and Matplotlib libraries).
      location: Rochester, NY
      title:  Research Assistant
    - company: BASSEIN CATHOLIC CO-OPERATIVE BANK
      company_logo: job
      company_url: ""
      date_end: "2021-11-01"
      date_start: "2019-09-01"
      description: |2-
          Responsibilities include:
          * Collaborated with internal teams and customers to identify and define data conversion requirements. Performed modification and rectification on the data before data migration that ensured the accuracy of migrated data to 70%.
          * Implemented data filtration and aggregation on the accounts to identify duplicated accounts and created linkage between savings and business accounts which reduced reduplication by 80%.
          * Executed data filtration on the bank accounts and analyzed the inactive accounts to identify the current active accounts and notified clients about their finances that brought down the number of inactive accounts by 20%.
      location: Mumbai, India
      title: Banking Data Analyst
    title: Experience
  design:
    columns: "2"



- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects



- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured



- block: contact
  content:
    address:
      city: Rochester
      country: United States
      country_code: US
      postcode: "14623"
      region: New York
    contact_links:
    email: pr1408@rit.edu
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    phone: 443-642-8218
    text: Feel free to contact me
    title: Contact
  design:
    columns: "2"
  id: contact
type: landing
---
