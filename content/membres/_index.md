---
title: "Membres du Laboratoire"
subtitle: "L'équipe humaine du DISP"
type: landing

design:
  view: wide

sections:
  # ---------------------------------------------------------------------------
  # UN SEUL BLOC POUR TOUT LE MONDE, DIVISÉ EN GROUPES
  # ---------------------------------------------------------------------------
  - block: team-showcase
    content:
      title: 'Notre Équipe'
      text: 'Découvrez les visages et les expertises qui composent le laboratoire DISP.'
      
      # C'est ici que la magie opère selon la doc officielle :
      user_groups:
        - name: "Direction"
        - name: "Chercheurs"
        - name: "Marchand" # (Optionnel, juste pour tester le groupe de Guy !)
        
    design:
      max_columns: 6
      show_organizations: true
      show_role: true
      show_social: true
---