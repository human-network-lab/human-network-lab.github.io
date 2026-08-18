---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Human Network Lab
          content: Studying the human brain and body as an interacting network.
          align: center
          background:
            image:
              filename: hero-banner.png
              filters:
                brightness: 0.6
            position: center
            color: '#333'
    design:
      slide_height: '520px'
      is_fullscreen: false
      loop: false
      interval: 4000

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div style="max-width: 700px; margin: 1.5rem auto; text-align: center;">
          <p style="font-size: 1.25rem; font-style: italic; line-height: 1.6;">
            &ldquo;A man becomes creative, whether he is an artist or a scientist, when he finds a new unity in the variety of nature. He does so by finding a likeness between things which were not thought alike before.&rdquo;
          </p>
          <p style="margin-top: 0.75rem; opacity: 0.7;">
            — Jacob Bronowski, <em>Science and Human Values</em> (1956)
          </p>
        </div>
    design:
      columns: '1'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div style="max-width: 900px; margin: 1rem auto 0; padding-top: 2.5rem; border-top: 1px solid rgba(128,128,128,0.2);">
          <p style="text-align: center; font-size: 0.8rem; letter-spacing: 0.08em; text-transform: uppercase; opacity: 0.55; margin-bottom: 2rem;">
            Part of
          </p>
          <div style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center; gap: 3.5rem;">
            <a href="https://www.umk.pl/en/" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; opacity: 0.85; transition: opacity 0.2s;" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=0.85">
              <img src="/media/logos/umk.png" alt="Nicolaus Copernicus University in Toruń" width="147" height="56" style="height: 56px; width: 147px; max-width: none; flex-shrink: 0;">
            </a>
            <a href="https://www.umk.pl/en/research-university/" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; opacity: 0.85; transition: opacity 0.2s;" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=0.85">
              <img src="/media/logos/idub.png" alt="Excellence Initiative – Research University" width="56" height="80" style="height: 80px; width: 56px; max-width: none; flex-shrink: 0;">
            </a>
            <a href="https://yufe.eu/" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; opacity: 0.85; transition: opacity 0.2s;" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=0.85">
              <img src="/media/logos/yufe.webp" alt="Young Universities for the Future of Europe" width="170" height="44" style="height: 44px; width: 170px; max-width: none; flex-shrink: 0;">
            </a>
          </div>
        </div>
    design:
      columns: '1'
---
