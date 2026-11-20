<p align="center">
<img src="logo.svg" alt="Logo Exalex" width="110">
</p>p>

<h1 align="center">Exalex</h1>h1>
<p align="center"><strong>Toutes les lois françaises</strong>strong></p>p>

Exalex est une petite application web (un seul fichier HTML, sans dépendance à installer) qui présente les **nouvelles lois et nouveautés réglementaires en France**, classées par thème. Sous chaque fiche, l'**URL de la source officielle** est affichée pour lire le texte complet.

## Fonctionnalités

- **Onglets thématiques** : Général, Travail, Particuliers, Jeux vidéo, Créateurs (YouTubeurs, TikTokeurs, streamers), Achats & ventes, Argent & banque, Logement, Santé & social, Entreprises.
- - **Recherche** instantanée dans les fiches (titre, résumé, étiquette).
  - - **Sources officielles uniquement** : un garde-fou dans le code masque tout lien dont le domaine n'est pas dans la liste officielle (`gouv.fr`, `europa.eu`, `senat.fr`, `assemblee-nationale.fr`, `vie-publique.fr`, `legifrance.gouv.fr`, `conseil-constitutionnel.fr`, `ineris.fr`).
    - - **Badges** : « Nouveau » pendant 3 jours après l'ajout d'une fiche, « Source officielle », et « détail à confirmer sur la page » quand l'information doit être recoupée avec la source.
      - - Interface claire, lisible sur téléphone, onglets défilants, accessibilité (focus visible, contrastes).
        -
        - ## Utilisation
        -
        - Ouvrir `index.html` dans un navigateur. Aucune installation, aucun serveur.
        -
        - Pour le publier en ligne : activer **GitHub Pages** sur la branche `main` (dossier racine).
        -
        - ## Ajouter ou modifier une fiche
        -
        - Toutes les données sont dans le tableau `DATA` de `index.html`. Une fiche contient : `d` (date du texte, AAAA-MM-JJ), `a` (date d'ajout, affiche « Nouveau » 3 jours), `k` (étiquette), `t` (onglets concernés), `h` (titre), `p` (résumé court), `u` (URL officielle, obligatoire), `s` (nom du site affiché) et `c` (optionnel, « détail à confirmer »).
        -
        - Règle d'or : **ne jamais inventer un lien**. Si aucune page officielle précise n'existe, ne pas ajouter la fiche.
        -
        - ## Identité visuelle
        -
        - Palette inspirée des références **RAL Classic** (approximations HEX pour l'écran) :
        -
        - | Rôle | RAL | HEX |
        - |---|---|---|
        - | Couleur principale (navigation, en-têtes, boutons) | 6005 Vert mousse | `#2F4538` |
        - | Fond (blanc perlé, décliné en tons plus clairs) | 1013 Blanc perlé | `#EAE6CA` → `#F3F0E2` / `#FCFBF6` |
        - | Premium (filets, icônes, détails) | 1036 Or nacré | `#705335` (texte) / `#B8923F` (filets) |
        - | Texte | 7022 Gris terre d'ombre | `#4C4A44` |
        - | Accent secondaire (rare) | 3005 Rouge vin | `#5E2129` |
        -
        - Typographies : Playfair Display (titres) et Source Sans 3 (texte), chargées depuis Google Fonts.
        -
        - Le logo (`logo.svg`) représente une balance de la justice en vert et or. Il sert aussi de favicon.
        -
        - ## Contenu du dépôt
        -
        - - `index.html` : l'application complète (HTML, CSS, JS et données)
          - - `logo.svg` : logo et favicon
            - - `README.md` : ce fichier
              -
              - ## Avertissement
              -
              - Exalex est un outil d'information : les résumés sont rédigés à partir des pages officielles liées, mais **ce n'est pas un conseil juridique**. Pour toute décision, se reporter au texte officiel et, si besoin, à un professionnel du droit.
              - </strong>
