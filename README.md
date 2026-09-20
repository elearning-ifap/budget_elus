# Budget élus — V8 lot 3.12

## Évolution de cette version

La page « Mes repères et ressources » a été recentrée sur l’usage apprenant :

- suppression du bloc « Références et ressources recommandées dans le corpus expert » ;
- suppression des ressources Bee Assist de l’espace apprenant (l’expertise reste créditée dans la page dédiée) ;
- remplacement par trois accès officiels : rapports budgétaires DBAF, article 84 de la loi organique sur Légifrance, publications de la CTC Nouvelle-Calédonie ;
- explicitation de l’utilité des liens pour préparer ou approfondir un dossier budgétaire réel ;
- suppression d’une mention « corpus expert » encore visible dans l’activité sur les indicateurs.

Cette version conserve l’intégralité des corrections tablette de la V8 lot 3.11.

Correctif tablette Android / Xiaomi : la distinction smartphone-tablette ne repose plus sur la seule largeur CSS du navigateur.

- smartphone : écran de relais conservé ;
- tablette Android/iPad : module autorisé même si Chrome ou Moodle expose moins de 768 px CSS ;
- mise en page tablette forcée par classe appareil ;
- portrait et paysage conservés ;
- logique pédagogique et données inchangées par rapport à la V8 lot 3.10.

# Budget des élus — V8 lot 3.10 — principes budgétaires illustrés

Version GitHub Pages consolidant les passes tablette, relecture Émilie et fondamentaux renforcés. La V8 lot 3.10 améliore la mémorisation des six principes sans modifier leur contenu de fond.

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

## V8 lot 3.9 — palier de fondamentaux renforcé
- Le bloc « Quatre repères pour lire le dossier avec méthode » devient un véritable palier d'apprentissage.
- Les principes ne sont plus seulement nommés : chaque principe comporte une explication courte et son usage pour l'élu.
- « Unité et universalité » sont présentées ensemble afin de garder six repères : annualité, unité/universalité, spécialité, équilibre réel, sincérité et antériorité.
- Les sections fonctionnement / épargne / investissement sont reliées explicitement.
- Le cycle précise, pour chaque étape, le repère documentaire et l'action attendue de l'élu.
- Les quatre indicateurs sont définis avant les activités de calcul et d'interprétation.
- Aucune date juridique nouvelle n'a été ajoutée à ce palier.

## V8 lot 3.10 — principes budgétaires illustrés
- Le contenu des six principes reste inchangé sur le fond : la passe porte sur l'UX et la mémorisation.
- Les six blocs documentaires sont remplacés par des cartes courtes à révélation.
- Chaque principe dispose d'un pictogramme SVG intégré au module, d'une phrase-clé et d'un développement en deux niveaux : « Ce que cela signifie » et « Votre réflexe d'élu ».
- Une seule carte est ouverte à la fois afin de limiter la densité visuelle.
- Un indicateur `0/6 → 6/6` matérialise l'exploration des principes ; la synthèse apparaît après consultation des six cartes.
- Les pictogrammes sont des SVG HTML/CSS : aucune image supplémentaire, aucun média externe, aucun risque de flou sur tablette.
- Sur tablette, la grille passe à 2 × 3 ; la carte ouverte prend la largeur disponible pour conserver une lecture confortable.
- La consultation des principes est persistée dans l'état du module afin que la synthèse reste acquise à la reprise.