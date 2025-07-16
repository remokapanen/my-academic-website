---
title: 'Ranki'
date: 2025-07-12
type: landing

sections:
  - block: hero
    content:
      title: 'Ranki'
      subtitle: 'Project Overview'
    design:
      spacing:
        padding:
          - "5rem"
      text_color_light: true

  - block: markdown
    content:
      title: 'Mikä Ranki?'
      text: |
        Ranki on yhdellä napinpainalluksella päivittyvä yleisessä jaossa oleva lääketieteelliseen peruskoulutukseen keskittyvä Anki-pakka, jonka tarkoituksena on tehostaa oppimista ja ennen kaikkea säästää opiskelijoiden aikaa. 

        Pakka päivittyy jatkuvasti sitä tahtia, mitä allekirjoittanut kerkeää. 
    design:
      columns: '1'
      spacing:
        padding:
          - "3rem"

  - block: markdown
    content:
      title: 'Oppaat'
      subtitle: 'GitBook Integration'
      text: |
        ## 

        Tarkat ohjeet Rankin lataamiseen ja sen käyttöön löytyvät alla olevasta GitBookista.

        Aiheesta löytyy myös [opetusvideo](https://youtu.be/XwG-Fju94tU?si=BmxbPRwGbzqZb5PK)

  - block: collection
    content:
      title: 
      filters:
        folders:
          - rankiproject
    design:
      view: article-grid
      fill_image: false
      columns: 3
      spacing:
        padding:
          - "3rem"
      background:
        color: 'light'

  - block: collection
    content:
      title: 'Päivitykset'
      subtitle: 'Latest Updates'
      filters:
        folders:
          - post
        tags:
          - ranki
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
        author: ''
        category: ''
        tag: ''
        language: ''
        page_type: ''
        sort_by: 'Date'
        sort_ascending: false
        number: 5
    design:
      columns: '1'
      spacing:
        padding:
          - "3rem"
      background:
        color: 'light'
---

