---
title: Article
sections:
  - type: hero_section
    template: hero_section
    title: Article
    subtitle: The optional subtitle
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: article_feed_section
    template: article_feed_section
    article_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Article
  description: This is the article page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Article
      keyName: property
    - name: 'og:description'
      value: This is the article page
      keyName: property
    - name: 'og:image'
      value: images/classic/post-5.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Article
    - name: 'twitter:description'
      value: This is the article page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
layout: advanced
---