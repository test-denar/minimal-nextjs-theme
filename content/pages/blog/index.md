---
title: Blog
layout: PageLayout
sections:
  - type: FeaturedPostsSection
    variant: variant-a
    colors: colors-e
    backgroundWidth: full
    title: Blog
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin: ["mt-0", "mb-0"]
        padding: ["pt-12", "pb-12"]
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
seo:
  title: Stackbit Minimal Theme Blog Page
  description: The preview of the Minimal theme blog page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Minimal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Minimal theme blog page
      keyName: property
    - name: 'og:image'
      value: images/hero.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Minimal Theme
    - name: 'twitter:description'
      value: The preview of the Minimal theme blog page
    - name: 'twitter:image'
      value: images/hero.png
      relativeUrl: true
---
