---
# Leave the homepage title empty to use the site title
title: Analyse de textes philosophiques québécois assistée par ordinateur
date: 2023-06-23
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

  - block: markdown
    content:
      title: Nouvelles approches des corpus
      subtitle:
      text: |
        <p>
        L’IA et les humanités numériques sont appelées à transformer en profondeur les champs de la recherche et de l’enseignement. Auparavant, on ne pouvait mener de grands travaux de ce type sur l’histoire de la philosophie au Québec, car on ne disposait d'aucune collection conséquente de textes. Mais un patrimoine numérique est maintenant disponible et plusieurs collections de textes philosophiques ont été mis en ligne : le PPDQ, le Patrimoine philosophique du Québec (Simard et al. 2011-2020), les textes pertinents des Classiques des sciences sociales de l’Université du Québec à Chicoutimi (Tremblay et al. 2000-2020), des textes philosophiques numérisés par BAnQ (Bibliothèque et Archives nationales du Québec), ainsi que les textes issus des trois principales revues savantes en philosophie au Québec : le Laval théologique et philosophique, Dialogue et Philosophiques.
        </p>
    design:
      columns: '2'

  - block: markdown
    content:
      title: Un projet de recherche en deux volets
      subtitle:
      text: |
        1. Le premier volet propose divers types d’analyses discursives et textuelles de la vaste production écrite québécoise en philosophie. Plus spécifiquement, il vise à explorer diachroniquement et synchroniquement trois opérations essentielles de tout texte philosophique : les thèmes, les concepts et les arguments. Les fondements épistémologiques et la méthodologie pour ce type d'analyse font appel à la logique de l’argumentation, aux théories de la linguistique textuelle ainsi qu'à la philosophie du langage. Dans ce cadre, on examinera des textes philosophiques, mais on étudiera aussi le rôle de l'essai, une signature de l'histoire des idées au Québec.
        1. Le deuxième volet du projet détaille les technologies utilisées pour appuyer le traitement d'un patrimoine numérisé trop vaste pour être maîtrisé par les moyens usuels. Il en appelle à des technologies informatiques de pointe pour la LATAO, la lecture et l'analyse de texte assistées par ordinateur. Ces outils permettent une modélisation informatique et une dissection stratifiée du texte philosophique.
    design:
      columns: '2'

  - block: markdown
    content:
      title: Méthodes
      subtitle:
      text: |
        À cette fin, le projet crée des chaînes de traitements algorithmiques qui vont de la préparation initiale du corpus à l'interprétation finale des résultats, en passant par la reconnaissance des caractères, le moissonnage, l'étiquetage linguistique, la fouille de texte, l'extraction d'information, la catégorisation, ainsi que l’analyse des thèmes, des concepts et des arguments. Bref, le projet utilisera un ensemble de moyens pertinents pour aider la recherche dans toutes les phases de la saisie, de la lecture et de la compréhension d'un texte.

        Les modèles formels utilisés sont de type mathématique, statistique et logique. Quant aux modèles computationnels, ils appliquent des algorithmes issus des recherches classiques et récentes en intelligence artificielle pour le traitement automatique du langage et de la fouille de textes : bases de données de connaissances, enrobage, schémas de règles, apprentissage machine et profond, extractions de relations sémantiques.
    design:
      columns: '2'

  - block: markdown
    content:
      title: Retombées
      subtitle:
      text: |
        Un dernier pan du projet vise un transfert des méthodes, de l'expertise et des outils informatiques aux domaines universitaire et collégial de la formation et de l'enseignement. Aussi, un plan de mobilisation accompagne-t-il le projet. Ce plan prévoit des modalités de formation, de diffusion et de publication qui impliqueront la collaboration avec diverses institutions d'enseignement.

        Ce type de projet ouvre une dynamique de littératie dans le domaine des humanités numériques, littératie applicable à des textes abstraits, tels les textes philosophiques. Il aimerait contribuer à la formation d’une nouvelle génération d’étudiants et de professeurs, qu’il s’agisse des universités ou des collèges. Il souhaite ainsi les préparer à relever un défi de taille soulevé par les transformations de la recherche et de l'apprentissage à l'ère de l'économie numérique.
    design:
      columns: '2'

  - block: collection
    content:
      title: Actualités
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
      page_type: actualites
    design:
      view: card
      columns: '1'
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./equipe/" cta_text="Équipe de recherche →" %}}
    design:
      columns: '1'
---