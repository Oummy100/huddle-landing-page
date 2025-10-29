# Objectif

Huddle Landing Page
Ce projet consiste à réaliser une page d’atterrissage (landing page) pour la plateforme fictive Huddle. L’objectif est de mettre en pratique les compétences en HTML et CSS acquises, en créant une page web moderne, responsive et attrayante.

Structurer le contenu avec des balises HTML sémantiques.
Mettre en forme la page grâce au CSS : couleurs, typographies, espacements, boutons, etc.
Intégrer des images, des icônes et des logos.
Rendre la page responsive pour une expérience optimale sur tous les appareils.
Créer une navigation claire et un pied de page complet avec des liens et des réseaux sociaux.


## Spécifications
 Respect de la structure HTML sémantique, Utilisation correcte des polices, Respect de la palette de couleurs, Page responsive  & Utilisation de Flexbox pour la mise en page, Accessibilité & Code propre, indenté, et fichiers bien organisés

 ### Ma structure
```
 body
├── header
│ ├── nav
│ │ ├── img (logo)
│ │ └── button (Try It Free)
│ └── section (hero)
│ ├── div.titre
│ │ ├── h1
│ │ ├── p
│ │ └── button (Get Started)
│ └── div.image
│ └── img (mockup)
│
├── main
│ ├── div.div1
│ │ ├── section.partie1 (text)
│ │ └── section.partie2 (image)
│ ├── div.div2
│ │ ├── section.partie1 (text)
│ │ └── section.partie2 (image)
│ └── div.div3
│ ├── section.partie1 (text)
│ └── section.partie2 (image)
│
├── div.une_petite_div4
│ ├── h2
│ └── button
│
└── footer
├── section.contact
│ ├── img (logo)
│ ├── div.localisation
│ │ └── ol > li (adresse, tel, mail)
│ └── ul (liens)
├── section.contenair
│ └── div.reseau (icônes)
└── p (copyright)  

```

### Proprétés CSS

--Body

font-size: 18px → taille de base du texte

font-family → police globale

font-weight: 400 → poids normal par défaut

Layout global (flex / grid / spacing)

display: flex → placer éléments en ligne ou colonne

flex-direction → orientation (row ou column)

gap / row-gap → espacement entre enfants

justify-content / align-items → alignement horizontal / vertical

display: grid + grid-template-columns → mise en colonnes responsive

--Dimensions & espace

width, height → taille des éléments

padding → espace interne

margin → espace externe

border-radius → coins arrondis

--Background

background-image → image decorative en arrière plan

background-color → couleur de fond

var(--Couleur) → utilisation d’une variable définie plus haut

--Typographie

font-size → taille du texte

font-family → police

font-weight → épaisseur

text-align → centrage du texte

--Effets visuels

box-shadow → ombre pour relief

transform: translateY() → déplacement d’un bloc verticalement

transition + :hover → effet d’interaction (survol bouton, lien, icône)

--Boutons & interactions

cursor: pointer → main au survol

border: none → bouton sans bordure

background + color → style du bouton

:hover couleur différente → feedback visuel

--Liens

text-decoration: none → pas de soulignement par défaut

a:hover → underline + couleur accentuée

Footer (grid)

grid-column: span X → un élément occupe X colonnes du grid

align-items: center → centrage vertical

## GitHub Page

 https://oummy100.github.io/huddle-landing-page/