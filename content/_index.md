---
# Leave the homepage title empty to use the site title
title: Analyse de textes philosophiques québécois assistée par ordinateur
date: 2023-09-21
type: landing

sections:
  - block: hero
    content:
      title: |
        Analyse de textes philosophiques québécois assistée par ordinateur
      image:
        filename: welcome.jpg
      text: |
        <p>
        En mai 2021, le programme Savoir du CRSH, le Conseil de Recherches en Sciences Humaines du Canada, accordait au LANCI, le Laboratoire d’analyse cognitive de l’information de l’UQÀM, une importante subvention de recherche. Son objectif principal est d’analyser un corpus historique de textes philosophiques québécois à l'aide d'outils informatiques utilisant des acquis récents de l'intelligence artificielle (IA).
        </p>

  - block: collection
    content:
      title: Actualités
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: actualites
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Activités
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '2'
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./equipe/" cta_text="Équipe de recherche →" %}}
    design:
      columns: '1'
---