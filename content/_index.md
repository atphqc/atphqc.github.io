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
        label: Blogue de recherche
        url: ./#blogue
        icon_pack: fas
        icon: newspaper
      cta_alt:
        label: Voir les activités
        url: ./#activites
        icon_pack: fas
        icon: calendar-plus
#      cta_note:
#        label: >-
#          <div id="activites-bouton">
#          
#          <a href="#activites">{{< icon name="calendar-plus" pack="fas" >}} Voir les activités</a>
#          </div>
      text: |
        <p>
        Le groupe de recherche sur l’analyse de textes philosophiques québécois assistée par ordinateur (<abbr title="Analyse de textes philosophiques québécois assistée par ordinateur">ATPHQC</abbr>) est porteur d’un projet interdisciplinaire visant à explorer un large corpus historique issu de la philosophie québécoise à l’aide d’outils informatiques inspirés de l’intelligence artificielle​.
        Le projet est financé par le <abbr title="Conseil de recherche en sciences humaines du Canada">CRSH</abbr> dans le cadre des <a href="https://www.sshrc-crsh.gc.ca/funding-financement/programs-programmes/insight_grants-subventions_savoir-fra.aspx">subventions Savoir</a>.
        </p>

  - block: collection
    id: blogue
    content:
      title: Blogue de recherche
      subtitle: Échos des travaux effectués par le groupe et dernières nouvelles du projet
      text:
      count: 3
      filters:
        folders:
          - blogue
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      sort_by: 'Date'
      order: desc
      page_type: post
      archive:
        enable: true
        text: Voir tous les billets
    link: blogue/
    design:
      view: card
      columns: '2'

  - block: collection
    id: activites
    content:
      title: Activités
      subtitle: Activités organisées par le groupe de recherche
      text:
      count: 3
      filters:
        folders:
          - event
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: 
      archive:
        enable: true
        text: Voir toutes les activités
    design:
      view: 2
      columns: '2'
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <img src="./sshrc-fip-full-color-fra.png"
          alt="Logotype du Conseil de recherche en sciences humaines du Canada."
          title="Conseil de recherche en sciences humaines du Canada" />
    design:
      columns: '2'
---