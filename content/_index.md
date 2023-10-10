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
      cta:
        label: Actualités
        url: ./#actualites
        icon_pack: fas
        icon: newspaper
      cta_alt:
        label: Présentation
        url: presentation
      cta_note:
        label: >-
          <div style="text-shadow: none;">
          <a href="#activites">Voir les activités</a>
          </div>
      text: |
        <p>
        Le groupe de recherche sur l’analyse de textes philosophiques québécois assistée par ordinateur est le véhicule d’un projet interdisciplinaire visant à explorer un large corpus historique issu de la philosophie québécoise à l’aide d’outils informatiques inspirés de l’intelligence artificielle​.
        Le projet est financé par le <abbr title="Conseil de recherche en sciences humaines du Canada">CRSH</abbr> dans le cadre des <a href="https://www.sshrc-crsh.gc.ca/funding-financement/programs-programmes/insight_grants-subventions_savoir-fra.aspx">subventions Savoir</a>.
        </p>

  - block: collection
    id: actualites
    content:
      title: Actualités
      subtitle: Dernières nouvelles du projet
      text:
      count: 3
      filters:
        folders:
          - actualites
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      sort_by: 'Date'
      order: desc
      page_type: actualites
      archive:
        enable: true
        text: Voir toutes les actualités
    link: post/
    design:
      view: card
      columns: '2'

  - block: collection
    id: activites
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