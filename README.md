# Budget des élus — V8 lot 3.8 — optimisation tablette

Version GitHub Pages issue de la V8 lot 3.7. Cette passe ne modifie ni le corpus pédagogique ni les activités : elle sécurise l’affichage sur ordinateur et tablette.

## Cibles d’affichage

- **Ordinateur : pris en charge**.
- **Tablette paysage et portrait : prise en charge et optimisée**.
- **Smartphone (< 768 px) : volontairement non pris en charge**. Un écran d’information remplace le module afin d’éviter une expérience dégradée.

## Corrections de cette passe

- sommaire latéral remplacé par un panneau superposé sur tablette ;
- largeur du contenu rendue disponible au parcours et aux activités ;
- recomposition dédiée en paysage et en portrait ;
- conversations de la mission 5 affichées en pleine largeur sur tablette ;
- cartes indicateurs maintenues en grille 2 × 2 ;
- simulateur et dossier recomposés selon l’orientation ;
- carnet simplifié sur tablette : suppression des anneaux et de la ligne latérale décorative ;
- règles de médias harmonisées (`max-width`, `object-fit`, absence de débordement) ;
- recadrage CSS des trois images contenant une bande claire dans leur fichier source (mission 1, mission 5, conclusion) ;
- cibles tactiles conservées à au moins 44 px ;
- anciens breakpoints laissés dans le fichier pour non-régression, mais neutralisés par une couche finale unique pour 768–1179 px.

## Recette de référence

La version est contrôlée aux fenêtres suivantes : 1440×900, 1180×820, 1024×768, 834×1194, 768×1024, ainsi qu’à 390×844 pour vérifier l’écran de blocage smartphone.

## Héritage V8 lot 3.7

Version GitHub Pages issue de la V8 lot 3.6. Cette passe solde les remarques de relecture encore ouvertes et corrige la lecture des quatre indicateurs à partir du corpus expert.

## Principales corrections

- Mission 1 : formulation « règle / pratique » moins injonctive et accès direct au carnet au point d’étape.
- Mission 3 : trajectoires représentées par des courbes légendées N−2 / N−1 / N ; rappel visuel de l’événement exceptionnel N−1.
- Mission 4 : les cartes n’affichent plus les trois états simultanément. Elles montrent **un seul état pour le cas** :
  - épargne brute 13 Md : **vigilance** ;
  - besoin à financer 9 Md : **vigilance** ;
  - capacité de désendettement 7,3 ans : **situation favorable** selon le repère < 8 ans, avec vigilance sur la trajectoire ;
  - taux d’autofinancement ≈ 59 % : **situation favorable** selon le repère > 50 %.
- L’activité de qualification reprend ces quatre réponses expertes et distingue le niveau du cas de sa trajectoire.
- Simulateur : la question de contrôle n’apparaît qu’après conservation des deux scénarios.
- Vigilances : consigne explicitement reliée à la comparaison des deux scénarios.
- Mission 5 : « Vos notes dans votre carnet », accès direct au carnet et interlocuteurs harmonisés (service financier, commission compétente, service porteur du projet).
- Radar final : légende graphique explicite Départ / Aujourd’hui.
- « Mes repères » et « Ressources » sont réunis sur une même page ; le carnet dispose d’un bouton direct.
- Les sources et ressources recommandées par le brief expert sont explicitées.

## Données pédagogiques

Les montants du cas restent fictifs. Ils servent à entraîner la méthode de lecture et ne décrivent pas la situation budgétaire réelle de la Nouvelle-Calédonie.