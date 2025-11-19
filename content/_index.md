---
title: 'Hopla - Vols pas cher depuis Alsace'
date: 2025-11-19
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Pars d'ici, rêve plus loin
      text: Les meilleurs deals vols existent... mais tu ne les vois jamais passer à temps. Hopla détecte automatiquement les vols les moins chers depuis Strasbourg, Bâle, Karlsruhe et t'avertit avant que le prix ne remonte.
      primary_action:
        text: Télécharger Hopla
        url: '#download'
        icon: rocket-launch
      secondary_action:
        text: Voir comment ça marche
        url: '#features'
      announcement:
        text: "La première app qui scanne les prix 24/7 depuis tes aéroports locaux."
        link:
          text: "En savoir plus"
          url: "#features"
    design:
      css_class: "dark"
      background:
        color: "#C41E3A"
        image:
          filename: "coffee.jpg"
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false

  - block: stats
    content:
      items:
        - statistic: "24/7"
          description: |
            Surveillance des prix
            en temps réel
        - statistic: "0€"
          description: |
            Complètement gratuit
            sans frais cachés
        - statistic: "2 clics"
          description: |
            Du deal à la réservation
            ultra rapide
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: features
    id: features
    content:
      title: Comment ça marche
      text: Hopla détecte automatiquement les meilleurs deals pour toi
      items:
        - name: 🔍 Détection Automatique
          description: Tu définis tes destinations préférées une fois. Hopla surveille les prix 24/7 depuis tes aéroports et t'alerte dès qu'un bon plan apparaît.
        - name: 🔔 Notifications Intelligentes
          description: Pas de spam. Tu reçois une notification uniquement quand le prix passe sous ton seuil. Et tu peux partir en moins de 2 clics.
        - name: ✈️ Spontané & Flexible
          description: Un deal fou à Barcelone demain ? Parfait. Hopla te montre toutes les options pour partir du jour au lendemain.
        - name: 📱 Ultra Simple
          description: Pas besoin de coder ou de configurer des trucs compliqués. Une app, une destination, et hop.
        - name: 🎯 Local d'abord
          description: On regarde depuis Strasbourg, Bâle, Karlsruhe. Pas depuis Paris. C'est ta région qui compte.
        - name: 💰 Gratuit
          description: Complètement gratuit. Pas de frais cachés, pas d'abonnement. Juste des bons plans.

  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Pourquoi Hopla existe
          text: Les bons plans vols existent... mais tu ne les vois jamais à temps.
          feature_icon: check
          features:
            - "Pendant que Google Flights regarde vers Paris, on regarde vers ici"
            - "Tu ne cherches plus, c'est l'app qui cherche pour toi"
            - "Détection des deals en temps réel, notification avant que ça remonte"
          image: "coffee.jpg"
          button:
            text: Télécharger Hopla
            url: "#download"
    design:
      css_class: "bg-white"

  - block: testimonials
    content:
      title: "Qui sont les hoplers ?"
      text: ""
      items:
        - name: "Étudiants"
          role: "Qui veulent découvrir l'Europe sous 200€"
          image: "coffee.jpg"
          text: "Hopla rend le voyage possible, sans se ruiner."
        - name: "Jeunes actifs"
          role: "Qui rêvent de partir mais pas de se ruiner"
          image: "coffee.jpg"
          text: "Un deal fou le vendredi ? Tu parts le lendemain."
        - name: "Aventuriers"
          role: "Qui aiment l'imprévu et la spontanéité"
          image: "coffee.jpg"
          text: "Le voyage c'est pas un luxe, c'est une nécessité."
    design:
      spacing:
        padding: ["6rem", 0, 0, 0]

  - block: cta-card
    id: download
    content:
      title: Tu ouvres l'app. Tu découvres un deal fou. En deux clics tu pars.
      text: Hopla, c'est une communauté de voyageurs curieux qui veulent bouger sans se ruiner. Simple. Local. Inspirant.
      button:
        text: 📱 Télécharger Hopla gratuitement
        url: 'https://apps.apple.com/fr/app/hopla-vols-pas-chers-alsace/id6753660322'
    design:
      card:
        css_class: "bg-primary-600"
        css_style: ""

  - block: cta-card
    content:
      title: ""
      text: Disponible aussi sur Android
      button:
        text: 🤖 Télécharger sur Google Play
        url: 'https://play.google.com/store/apps/details?id=com.jj.hopla&pli=1'
    design:
      card:
        css_class: "bg-primary-600"
        css_style: ""
---
