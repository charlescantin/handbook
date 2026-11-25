# Lux Touch (Sillysoft Games, id App Store 292538570) — interface, écrans, menus et interactions

Notes de recherche rédigées le 2026-11-25. Version courante sur l'App Store : **3.24 (23 janvier 2019)**, nom de fiche « Lux Touch 3 - World Domination » (US/CA-en) / « Lux Touch » (CA-fr).

**Convention de preuve utilisée partout ci-dessous**

- **[VU]** = observé directement par moi dans une capture d'écran ou une image de vidéo téléchargée et visionnée.
- **[OFFICIEL]** = affirmé par Sillysoft (fiche App Store, notes de version, site sillysoft.net) ou par Apple (métadonnées de la fiche).
- **[AVIS]** = rapporté par un utilisateur ou un journaliste (non vérifié par moi).
- **[INFÉRENCE]** = déduction de ma part ; à traiter comme hypothèse.
- **non vérifié** = aucun élément trouvé ; je n'ai pas pu lancer l'app.

**Corpus visuel réellement visionné**

| Réf. | Source | Date | Ce que c'est |
|---|---|---|---|
| IP1–IP5 | 5 captures iPhone de la fiche App Store (16:9, 1334×750), via [iTunes Lookup API CA](https://itunes.apple.com/lookup?id=292538570&country=ca) (identiques US et CA-fr) | consultées 2026-11-25 ; mises en ligne à l'époque 3.x (date exacte inconnue) | Captures marketing : écran réel + bandeaux publicitaires bleu marine ajoutés par-dessus |
| ID1–ID5 | 5 captures iPad de la même fiche (4:3, 2048×1536) | idem | idem |
| IL1–IL3 | 3 captures 480×320 dans [iLounge, « iPhone Gems: Puzzle, Board + Mystery Games »](https://www.ilounge.com/index.php/articles/comments/iphone-gems-puzzle-board-mystery-games) | 24 nov. 2008 | Version 1.0.x |
| PG1 | Capture 478×318 dans [Pocket Gamer, « Lux Touch risks an iPhone adaptation »](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation/) | 14 oct. 2008 | Version 1.0 |
| YT-a | Vignettes (4 images) de [« Lux Touch iPhone Game Review », Art of the iPhone](https://www.youtube.com/watch?v=mH7PLtH-eUs) | « il y a 18 ans » (≈ 2008) | v1.x, filmé à l'écran |
| YT-b | Vignettes de [« Lux Touch - iPhone game review », iOSlide](https://www.youtube.com/watch?v=W_OHvyRxkAA) | ≈ 2010 | v1.x/2.x |
| YT-c | Vignettes de [« Lux Touch iPhone App Review », AppRemarks](https://www.youtube.com/watch?v=4FxmsfPCYL8) | ≈ 2012 | v2.x |
| YT-d | Vignettes + image HD de [« Lux touch review ipod and iPad », iOS Game time](https://www.youtube.com/watch?v=P2eqdArQf4A) | ≈ 2015 | v3.0.x, capture directe 1136×640 |
| YT-e | Vignettes de [« Lux Touch iOS Gameplay », Gamers Channel For Every One](https://www.youtube.com/watch?v=sNNmXj3Zcgc) | ≈ 2016 | v3.x sur iPad |
| YT-f | Vignettes + image HD de [« Lux Touch Game Play », Old School Media](https://www.youtube.com/watch?v=RjYsQlFi8MI) | ≈ 2019 | v3.x, avec surimpression de l'outil de streaming |
| YT-g | Vignettes + images HD de [« Lux Touch 3 (Risiko) Gameplay #2/#3/#4 », Sebastiano Trunfio](https://www.youtube.com/watch?v=gIGw3GdJNIs) ([#4](https://www.youtube.com/watch?v=G0ObsOpDGxU)) | ≈ 2020 | v3.24 sur iPhone à encoche |

Limites : YouTube a refusé les pages de lecture (HTTP 429) ; je n'ai donc ni descriptions, ni transcriptions, ni dates exactes — seulement les titres, chaînes, âges relatifs affichés par la recherche YouTube le 2026-11-25 et les 3–4 vignettes automatiques par vidéo. Le forum Sillysoft a renvoyé « Access denied » (HTTP 403). web.archive.org n'a été accessible que pour un instantané (5 janv. 2009).

---

## 1. Quels écrans existent et comment navigue-t-on (du lancement à la fin de partie) ? Que contient le menu principal ?

### Takeaway
Lux Touch n'a pas de menu principal classique : l'app ouvre (après un écran d'accueil non documenté) directement sur le plateau de jeu, et toute l'interface tient en **un seul écran** (carte + colonne de boutons à droite) dont le contenu change selon la phase ; les seuls « écrans » additionnels documentés sont la superposition des bonus, le mode cartes et la boîte de fin de partie « Play Again / Get Lux DLX / Newsletter ». L'interface est **uniquement en anglais** : il n'existe aucun libellé français dans l'app.

### Cited Findings

**Inventaire des écrans/états documentés (version 3.x actuelle)**

| # | Écran / état | Preuve | Libellés exacts (anglais) |
|---|---|---|---|
| 1 | Écran d'accueil / de chargement | [AVIS] seulement : « fails to load when opening. Just shows the welcome screen » (s2k626, US, 8 déc. 2025) ; « freezing before it even passes the main screen » (Das_bomb, CA, 2 nov. 2013) — [flux d'avis App Store US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) | Contenu **non vérifié** (aucune capture trouvée) |
| 2 | Plateau — placement des armées | [VU] IP4, YT-d | Colonne : `Menu`, `1-Attack`, `Manual`, `Bonus`, compteur `3` / `Armies To Place` ; bandeau d'aide : `Tap or hold a blue country to place armies` |
| 3 | Plateau — attaque | [VU] IP2, ID2, ID4, YT-d, YT-f | Colonne : `Menu`, `1-Attack` ou `All-Attack`, `Manual` ou `Auto`, `Bonus`, `Fortify`, `End` ; bandeau : `Blue's turn` |
| 4 | Plateau — déplacement après conquête / fortification | [VU] IP4 | Flèche verte à double pointe entre deux pays ; bandeau : `Tap or hold to divide your armies between the two countries` |
| 5 | Plateau — tour des IA | [VU] YT-g, YT-e | Colonne réduite au seul bouton `Menu` ; étiquette de bonus isolée possible (`Europe bonus: 8`) |
| 6 | Superposition « Bonus » | [VU] IP1, ID1 | `North America bonus: 5`, `South America bonus: 2`, `Europe bonus: 5`, `Africa bonus: 3`, `Asia bonus: 7`, `Australia bonus: 2` |
| 7 | Mode cartes | [VU] IP3, ID3 | Colonne : `Menu`, `Later`, `Cash` ; cartes `Afghanistan`, `Japan`, `Ukraine`, `Indonesia`, `Wild Card` ; bandeau : `Card cash is worth 50 armies (then 55,60,65)` |
| 8 | Menu (bouton `Menu`) | [OFFICIEL] « Menu for restarting game! » (notes 3.0, 1er nov. 2013) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570) | Contenu exact du menu **non vérifié** (aucune capture du menu ouvert) |
| 9 | Fin de partie — victoire | [VU] IP5, ID5 | `Yay! You Won The Game!` + texte promo ; boutons `Play Again`, `Get Lux DLX`, `Newsletter` |
| 10 | Fin de partie — défaite | — | **non vérifié** |
| 11 | Réglages, aide/règles in-app, statistiques, « À propos » | — | **Aucun élément trouvé** ; voir question 4 |

- [OFFICIEL] Notes de version 3.0 (1er nov. 2013), mot pour mot : « - Faster animation! - Auto-Advance and All-Attacks quick modes! - Menu for restarting game! - Larger iphone5 screen size supported! - Retina quality map graphics! » — [fiche App Store US, historique des versions](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [VU] La boîte de fin de partie (victoire) est un panneau blanc translucide à bord noir, centré, avec « Yay! You Won The Game! » puis, sur iPhone (IP5), « 100+ maps and tough-as-nails AI come in Lux DLX, for serious strategists. » et, sur iPad (ID5), « Get Lux DLX for more game options, harder AI, and lots of maps! ». Dessous, trois boutons « pilule » rouge-orangé brillants empilés : `Play Again` (icône globe), `Get Lux DLX` (icône parchemin + plume), `Newsletter` (icône enveloppe). La carte reste visible derrière ; la colonne de droite ne montre plus aucun bouton ; le bandeau affiche encore `Blue's turn`. — [capture iPhone n°5](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/0c/e5/db/0ce5dbff-7daf-7c7d-c3dd-24ccd7da9566/pr_source.png/1334x750bb.png), [capture iPad n°5](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/b1/02/1b/b1021b8d-7682-e9fa-2400-15d36dcf0d3a/pr_source.png/2048x1536bb.png)
- [AVIS] L'app démarre directement en partie, sans menu : « You start the app for the first time and it takes you straight into a game. No instructions, tutorial or anything » (NeilC32, GB, 19 juil. 2010) ; « There is no way to set up a game, no menu, no options, nothing. As soon as you click the app icon, the game sets itself up » (2dart, CA, 14 févr. 2012) ; « le jeu commence sans crier gare au lancement » (Antoine D., FR, 12 août 2010) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] En 2008, « the big draw back to this version is no menus or options of any kind » (Mattjeff, oct. 2008) — [MacRumors, fil « Lux Touch »](https://forums.macrumors.com/threads/lux-touch.578393/)
- [AVIS] Avant la 3.0, impossible de recommencer : « when you are the first player eliminated, the game carries on and there is no way to reset it, so you are stuck watching the AI Players battle it out » (NCK1978, CA, 16 janv. 2011, v2.1) ; « I waited 35 min for the AI to stop fighting » (CA, 15 mars 2011) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] L'écran de fin est perçu comme un « nag-screen » : « the silly nag-screen every time you finish a game (to check out the developer's other game) » (oldmankit, GB, 9 nov. 2015, v3.0.2) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] Reprise de partie : aucune sauvegarde en v1 (« as soon as you get a phonecall, you've lost everything. No automatic save », ry.an, AU, 2 oct. 2009) ; à partir de la v2.x la partie est conservée à la sortie (« This version saves the game when you quit », Langelil, CA, 30 juin 2011) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json), [CA](https://itunes.apple.com/ca/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json). [OFFICIEL] Notes 2.2 (29 août 2011) : « Fixes resuming game when the human player is no longer alive. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [OFFICIEL] Langue de l'app : « Languages: English » ; `languageCodesISO2A: ['EN']` y compris sur la boutique CA-fr — [iTunes Lookup CA-fr](https://itunes.apple.com/lookup?id=292538570&country=ca&lang=fr_ca). Seule la **fiche** est traduite en français (nom « Lux Touch », description « Contrôlez les armées bleues et conquérez la carte », notes « Plus stable sur tous les appareils… »).
- [AVIS] « c'est en anglais et on ne sais jamais quoi touché. En français please » (yanns10, FR, 7 avr. 2009) — [flux d'avis FR](https://itunes.apple.com/fr/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)

**Libellés anglais relevés (tous [VU]) et équivalents français**

Il n'existe **aucun libellé français officiel** (app non localisée). La colonne de droite ci-dessous est une traduction de travail proposée par moi, pas un texte de l'app.

| Libellé in-app (EN, exact) | Où | Traduction de travail (non officielle) |
|---|---|---|
| `Menu` | colonne droite | Menu |
| `1-Attack` / `All-Attack` | colonne droite (bascule) | 1 attaque / Attaque totale |
| `Manual` / `Auto` | colonne droite (bascule) | Manuel / Auto |
| `Bonus` | colonne droite | Bonus |
| `Fortify` | colonne droite | Fortifier |
| `End` | colonne droite | Fin (du tour) |
| `Later` / `Cash` | mode cartes | Plus tard / Encaisser |
| `Armies To Place` (v1 : `Army To Place`) | compteur | Armées à placer |
| `Blue's turn` | bandeau bas-droite | Tour des Bleus |
| `Tap or hold a blue country to place armies` | bandeau | Touchez ou maintenez un pays bleu pour placer des armées |
| `Tap or hold to divide your armies between the two countries` | bandeau | Touchez ou maintenez pour répartir vos armées entre les deux pays |
| `Card cash is worth 50 armies (then 55,60,65)` | bandeau | L'échange de cartes vaut 50 armées (puis 55, 60, 65) |
| `Wild Card` | carte | Joker |
| `Yay! You Won The Game!` | fin de partie | Bravo ! Vous avez gagné la partie ! |
| `Play Again` / `Get Lux DLX` / `Newsletter` | fin de partie | Rejouer / Obtenir Lux DLX / Infolettre |

**Flux de navigation reconstitué**

```
Icône → [écran d'accueil — contenu non vérifié]
      → Plateau (partie créée automatiquement, joueur = Bleu ; ou partie reprise)
           ├─ (début de tour, si jeu de cartes valide) Mode cartes : Later | Cash
           ├─ Placement : compteur « N Armies To Place »
           ├─ Attaque : bascules 1-Attack/All-Attack et Manual/Auto ; Fortify ; End
           ├─ Fortification → End
           ├─ Tour des IA (seul « Menu » reste affiché)
           ├─ Bonus → superposition des valeurs de continents (sortie : non vérifiée)
           └─ Menu → recommencer la partie (autres entrées : non vérifiées)
      → Victoire : « Yay! You Won The Game! » → Play Again | Get Lux DLX | Newsletter
      → Défaite : écran non vérifié
```

### Inferences
- [INFÉRENCE] Il n'y a pas d'entrées « New Game », « Resume », « Help » ou « More Games » : aucun de ces libellés n'apparaît dans les captures, les vidéos ou les avis. L'équivalent de « New Game » est `Play Again` (fin de partie) et le redémarrage via `Menu` ; l'équivalent de « More Games » est `Get Lux DLX`.
- [INFÉRENCE] La reprise est automatique (pas de bouton « Resume ») : les avis parlent d'une partie « sauvegardée quand on quitte » et la note 2.2 parle de « resuming game », sans jamais mentionner de bouton.
- [INFÉRENCE] `Newsletter` ouvre un formulaire d'inscription à l'infolettre Sillysoft (le site propose « Add your email address to get our special newsletter » sur [sillysoft.net/lux/touch](https://sillysoft.net/lux/touch/)) ; `Get Lux DLX` renvoie à la fiche App Store de Lux DLX. Destinations exactes non vérifiées.
- [INFÉRENCE] Le bandeau `Blue's turn` encore affiché sur l'écran de victoire indique que la boîte de fin est une simple superposition sur le plateau, pas un écran distinct.

### Gaps
- Contenu de l'écran d'accueil (logo ? bouton ?) : aucune capture.
- Contenu exact du `Menu` ouvert (entrées, confirmation de redémarrage, lien vers les règles ?) : aucune capture ni description.
- Écran de défaite (texte, boutons) : non documenté.
- Comportement exact à la reprise après fermeture (dialogue ou reprise silencieuse) : non vérifié.
- Fil du forum Sillysoft [« LUX Touch (iPhone) »](https://sillysoft.net/forums/viewtopic.php?t=15416) inaccessible (HTTP 403).

---

## 2. Que montre le plateau de jeu et où se trouve chaque élément ?

### Takeaway
Le plateau occupe environ 94 % de la largeur ; une colonne sombre étroite à droite porte, de haut en bas, une barre verticale de rapport de forces puis les boutons contextuels ; le tableau des joueurs est en bas à gauche, le logo LUX en haut à droite sur la carte et un bandeau d'état/d'aide d'une ligne en bas à droite.

### Cited Findings

**Disposition (version 3.x, paysage) — tout [VU] sur IP1–IP5, ID1–ID5, YT-d**

| Élément | Position | Description observée |
|---|---|---|
| Carte du monde | toute la zone à gauche de la colonne | 42 territoires (le tableau affiche « 42 » pays quand Bleu possède tout, IP5/ID5), 6 continents ; liaisons maritimes en pointillés |
| Logo `LUX` | haut-droite, posé sur la carte (recouvre le nord-est de l'Asie) | Lettres rouges + globe terrestre sur un parchemin déroulé ; aucune fonction interactive démontrée |
| Barre de rapport de forces | haut de la colonne droite (≈ tiers supérieur) | Barre verticale à segments empilés, un par couleur de joueur vivant ; entièrement bleue à la victoire |
| Boutons contextuels | colonne droite, sous la barre | Icône blanche + libellé blanc : drapeau `Menu` ; épée `1-Attack` / bombe `All-Attack` ; deux soldats + double flèche `Manual` / soldats + flèche `Auto` ; étoile `Bonus` ; château `Fortify` ; octogone « stop » `End` |
| Compteur d'armées à placer | bas de la colonne droite (à la place de `Fortify`/`End`) | Grand chiffre blanc + `Armies To Place` + pictogramme de soldats |
| Tableau des joueurs | bas-gauche, sur la carte | Tableau blanc ; en-tête de 4 icônes (drapeau, soldat, cartes, graphique) ; une ligne par joueur vivant, chiffres dans la couleur du joueur |
| Bandeau d'état / d'aide | bas-droite, juste à gauche de la colonne | Fond violet/indigo, texte blanc gras, une ligne |
| Compteurs d'armées | sur chaque territoire | Bulle sphérique brillante teintée de la couleur du propriétaire, chiffre blanc ; figurines de soldats derrière la bulle |
| Sélection | sur la carte | Pays attaquant éclairci (lavande) + flèches rouges vers les voisins attaquables ; flèche verte double entre deux pays pendant un transfert |

- [OFFICIEL] Signification des colonnes du tableau des joueurs : « flag = # of countries ; army = # of armies ; card = # of cards ; graph = income (the number of armies earned at the start of their turn. effected by # of countries and continents owned) » — [sillysoft.net, Lux Touch Instructions](https://sillysoft.net/lux/touch/instructions.php) (consulté 2026-11-25)
- [VU] Exemple de tableau (ID1) : 5 lignes — bleu `8 24 0 3`, rouge `7 24 1 3`, vert `7 26 1 3`, orange `14 22 1 4`, noir `6 25 0 3` ; donc **5 joueurs** (1 humain bleu + 4 IA). À la victoire (IP5) : une seule ligne bleue `42 221 4 39`. — [capture iPad n°1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/03/25/fd/0325fd5a-bc4f-8e7b-678c-8663add0e246/pr_source.png/2048x1536bb.png)
- [OFFICIEL] Le joueur humain est toujours bleu : « Control the Blue armies and conquer the map. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [VU] La couleur de remplissage d'un territoire est celle de son **propriétaire** (bleu, rouge, vert sarcelle, orange, noir) ; le **contour épais** est celui du **continent** : Amérique du Nord orange, Amérique du Sud rouge sombre, Europe bleu clair, Afrique brun, Asie vert, Australie violet (IP2, ID2). En vue `Bonus` (IP1/ID1), les territoires sont remplis de la couleur de leur continent et une étiquette rectangulaire translucide par continent donne « Nom / bonus: N ».
- [VU] Valeurs de bonus au départ : Amérique du Nord 5, Amérique du Sud 2, Europe 5, Afrique 3, Asie 7, Australie 2 (IP1/ID1). Des images de vidéo montrent `Europe bonus: 8` et `Europe bonus: 9` en cours de partie (YT-g). — [vidéo #3](https://www.youtube.com/watch?v=gIGw3GdJNIs), [vidéo #4](https://www.youtube.com/watch?v=G0ObsOpDGxU)
- [OFFICIEL] « Use the Bonuses button to look at the regions for the map. Continent bonus values can increase as the game progresses. » — [Lux Touch Instructions](https://sillysoft.net/lux/touch/instructions.php)
- [VU] Les figurines derrière les bulles changent avec la taille de l'armée : fantassins à mousquet de style napoléonien (1 à 4 figurines selon l'effectif), cavalier pour « 53 », canon pour « 120 » (ID2). Beaucoup de territoires n'ont **aucune bulle** (IP2, IP3, IP5). — [capture iPad n°2](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/3e/fd/8e/3efd8e33-07a3-d475-bfc0-77ad4a4b2881/pr_source.png/2048x1536bb.png)
- [AVIS] Sens de l'absence de chiffre : « There are no empty territories, they are occupied, just with no extra armies » (Adamwow, GB, 4 juil. 2011) ; « 1 if theres no number on top of a country, or 1 plus the number on top of a country » (TheZimm, oct. 2008) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json), [MacRumors](https://forums.macrumors.com/threads/lux-touch.578393/)
- [VU] Mode cartes (IP3, ID3) : les cartes du joueur sont affichées **sur la carte, au-dessus du territoire qu'elles représentent** — petites cartes blanches à halo violet portant le nom du pays et une illustration (cavalier pour Afghanistan/Japan/Ukraine, canon pour Indonesia, cavalier + canon + fantassin pour `Wild Card`) ; les bulles d'armées sont masquées ; la colonne ne propose que `Menu`, `Later` (icône cercle barré) et `Cash` (icône de cartes). — [capture iPhone n°3](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/14/a9/af/14a9afa9-aaea-f16c-c928-4c007f4a9169/pr_source.png/1334x750bb.png)
- [AVIS] Confirmation dès 2008 : « each card represents a region (they actually appear over the region they represent when you view the cards) » — [MacRumors](https://forums.macrumors.com/threads/lux-touch.578393/)
- [OFFICIEL] Notes 3.0.2 (16 déc. 2013) : « Cards mode tells you the upcoming cash values. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Les cartes en main ne sont pas consultables hors de la phase d'échange : « there is no way to see which cards I currently have in my hand » (oldmankit, GB, 9 nov. 2015) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [VU] Pendant le tour des IA, la colonne ne garde que `Menu` (YT-g) ; les joueurs éliminés disparaissent du tableau (2 lignes en IP2, 3 en ID2).
- [VU] Aucun indicateur textuel de phase du type « Placement / Attaque / Fortification » : la phase se lit par les boutons présents et par le bandeau d'aide.

### Inferences
- [INFÉRENCE] La barre verticale colorée représente la part de chaque joueur dans le **total des armées** : en IP2, Bleu 98 armées contre Vert 34 (74 %) et la barre est bleue à ≈ 75 % ; en IL2 (2008), Rouge 246 armées sur ≈ 424 (58 %) occupe un peu plus de la moitié de la barre alors qu'il ne possède que 11 pays sur 42. Sillysoft ne documente pas cette barre.
- [INFÉRENCE] Une étiquette de bonus isolée (`North America bonus: 5` en IP4, `Europe bonus: 8` en YT-g) s'affiche momentanément quand un joueur détient un continent entier ; non confirmé par une source.
- [INFÉRENCE] Le chiffre de la bulle pourrait être soit le total d'armées (pays sans bulle = 1 armée), soit les armées au-delà de la première (témoignage MacRumors 2008). Les captures ne permettent pas de trancher ; les bulles « 1 » visibles en IP5/ID5 à côté de pays sans bulle rendent la question réelle.
- [INFÉRENCE] La carte est fixe et plein écran (pas de défilement ni de zoom) : toutes les images, de 2008 à 2020, montrent le même cadrage.

### Gaps
- Signification officielle de la barre colorée : non documentée.
- Règle exacte d'affichage des bulles (pays à 1 armée) : non vérifiée.
- Position d'un éventuel indicateur du nombre de cartes à venir ou du tour en cours : rien d'autre que le tableau et le bandeau.
- Comment on referme la superposition `Bonus` : non vérifié ; un avis signale un blocage (« Sometimes gets stuck on the map screen showing the bonuses. Only way out is to delete and reinstall the app », TrewGrit, US, 27 juil. 2023 — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)).

---

## 3. Comment le joueur exécute-t-il chaque action au toucher ?

### Takeaway
Tout se fait par **toucher simple** ou **toucher maintenu** sur les pays : un toucher = une armée (ou une attaque), maintenir = placement par lots ou attaques continues ; deux bascules (`1-Attack`/`All-Attack`, `Manual`/`Auto`) accélèrent le jeu depuis la 3.0. Aucun zoom, aucune annulation et aucun bouton « tout placer » ne sont documentés.

### Cited Findings

| Action | Geste documenté | Preuve |
|---|---|---|
| Placer des renforts | Toucher un pays bleu = 1 armée ; toucher maintenu = lots d'armées | [OFFICIEL] « you can either tap to place 1 army at a time, or tap-and-hold to place batches of armies » — [Instructions](https://sillysoft.net/lux/touch/instructions.php) ; [VU] bandeau `Tap or hold a blue country to place armies` (YT-d) |
| Attaquer | Sélection d'un pays à soi (il s'éclaircit, flèches rouges vers les cibles), puis toucher le pays ennemi ; maintenir = attaques continues | [VU] IP2/ID2 (surbrillance + flèches) ; [OFFICIEL] « Hold a finger to make continuous attacks. » — [sillysoft.net/lux/touch](https://sillysoft.net/lux/touch/) |
| Attaquer (versions ≤ 2.x) | Toucher **ou glisser** vers un pays ennemi | [VU] bandeau `Tap or slide an enemy country to attack.` lu sur une image basse résolution de [YT-c](https://www.youtube.com/watch?v=4FxmsfPCYL8) (≈ 2012) |
| Mode d'attaque | `1-Attack` : 1 lancer par toucher ; `All-Attack` : combat jusqu'à la défaite d'un camp, par toucher | [OFFICIEL] « The '1-attack' setting performs 1 attack per tap. The 'All-attack' setting does a full attack until one side loses, per tap » — [Instructions](https://sillysoft.net/lux/touch/instructions.php) |
| Avancer après conquête | `Manual` : on choisit combien d'armées entrent ; `Auto` : toutes les armées entrent automatiquement | [OFFICIEL] « The 'Manual' move-in setting lets you control how many armies you move into a defeated territory. The 'Auto' move-in setting will automatically move all your armies into territories that you take over. » — [Instructions](https://sillysoft.net/lux/touch/instructions.php) |
| Répartir manuellement | Toucher (1 armée) ou maintenir (lots) sur l'un des deux pays reliés par la flèche verte | [VU] IP4 `Tap or hold to divide your armies between the two countries` ; [OFFICIEL] « Hold a finger to divide large armies quickly. » — [sillysoft.net/lux/touch](https://sillysoft.net/lux/touch/) |
| Fortifier | Bouton `Fortify`, puis déplacements d'un pas | [OFFICIEL] « then fortify your armies around 1 move each » — [Instructions](https://sillysoft.net/lux/touch/instructions.php) ; [AVIS] « When fortifying troops you can only move the troops one tile » (Gregory Sandhills, CA, 20 juil. 2014) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) |
| Échanger des cartes | En début de tour : `Cash` pour encaisser, `Later` pour reporter ; obligatoire à 5 cartes ou plus | [VU] IP3 ; [OFFICIEL] « You can cash-in a set of cards (3 of a kind, or 1 of each kind) at the start of your turn… You have to cash cards when you have 5 or more. » — [Instructions](https://sillysoft.net/lux/touch/instructions.php) |
| Choisir quel jeu de cartes encaisser | Toucher les cartes pour changer la sélection | [AVIS] « you can tap on the cards to chane which ones you want to cash if you have more than one valid set » (oct. 2008) — [MacRumors](https://forums.macrumors.com/threads/lux-touch.578393/) |
| Encaisser plusieurs jeux | Possible depuis la 3.0.1 | [OFFICIEL] « Human players can cash multiple card sets when they have lots of cards. » (12 nov. 2013) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570) |
| Finir la phase / le tour | Bouton `End` | [VU] IP2 ; bandeau partiellement lisible « …our turn or fortify to advance rounds » sur [YT-f](https://www.youtube.com/watch?v=RjYsQlFi8MI) |
| Voir les bonus | Bouton `Bonus` | [VU] IP1 ; [OFFICIEL] [Instructions](https://sillysoft.net/lux/touch/instructions.php) |
| Recommencer | Bouton `Menu` | [OFFICIEL] notes 3.0 |
| Annuler (undo) | **Aucun** documenté | [AVIS] demande d'« an undo option on fortify as the small screen sometimes selects wrong move » (2pages, GB, 3 mai 2011) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json) |
| Zoom par pincement / défilement | **Aucun** documenté | aucune source |

- [OFFICIEL] Conseil du développeur qui reconnaît la petitesse des cibles : « Pinky fingers are your smallest, use them. » — présent en janvier 2009 ([instantané Wayback du 5 janv. 2009](https://web.archive.org/web/20090105212927/http://sillysoft.net:80/lux/touch/)) et toujours en ligne en 2026 ([sillysoft.net/lux/touch](https://sillysoft.net/lux/touch/))
- [OFFICIEL] Notes 3.0.1 : « Quick-buttons for Auto-Advance and All-Attack modes. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [VU] Les bascules changent d'icône et de libellé selon l'état : épée + `1-Attack` (IP1, IP4) contre bombe + `All-Attack` (IP2) ; soldats + double flèche + `Manual` (IP1, IP4) contre soldats + flèche simple + `Auto` (IP2, ID2).
- [AVIS] Rapidité du maintien : « When you attack and hold down a battle between 1000 on both sides can be over in a second » (Anon9966, AU, 3 mars 2013) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Les bascules ne s'appliquent pas aux IA : « If I am on auto the game should switch to auto. I want to play faster but I have to wait for each color to make their move. » (FGD Wiggle, US, 24 août 2019) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Placement initial non interactif : « Pas de stratégie au choix des positionnements, c'est auto attribué par l'IA » (Lanflure, FR, 1er oct. 2016) ; demandes répétées de choisir ses pays de départ (2009, 2020, 2023, 2025) — [flux d'avis FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)

### Inferences
- [INFÉRENCE] La séquence d'attaque est « toucher son pays (sélection, flèches rouges) puis toucher la cible » ; les flèches rouges observées partent toujours d'un pays éclairci vers des voisins ennemis. La persistance du geste « glisser » en 3.x n'est pas vérifiée.
- [INFÉRENCE] Il n'existe pas de bouton « placer tout » : le maintien fait office d'accélérateur, et les avis de 2010 se plaignent justement que le lot part d'un seul coup.
- [INFÉRENCE] Le passage attaque → fortification → fin se fait par `Fortify` puis `End`, `End` pouvant être touché directement pour sauter la fortification (les deux boutons coexistent en IP2).

### Gaps
- Taille des lots lors d'un toucher maintenu, et accélération éventuelle : non documentées.
- Désélection d'un pays, annulation d'un transfert en cours : non vérifiées.
- Existence d'une confirmation avant `End` ou avant le redémarrage : non vérifiée.

---

## 4. Quels réglages existent ? Y a-t-il une aide ou des règles dans l'app ?

### Takeaway
Lux Touch n'a pratiquement **aucun réglage** : ni son, ni difficulté, ni vitesse des IA, ni couleur, ni nombre de joueurs ; les seuls « réglages » sont les deux bascules de la colonne et le redémarrage via `Menu`. L'aide in-app se limite à un bandeau d'astuces contextuelles d'une ligne ; les règles complètes sont sur le site web du développeur.

### Cited Findings
- [OFFICIEL] Les options sont réservées à la version payante : « Get our premium game Lux DLX for... more AIs, more maps, more settings, more hot graphics, more human players » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570) ; « Lux DLX… featuring… More settings and options » — [sillysoft.net/lux/touch](https://sillysoft.net/lux/touch/)
- [AVIS] « No features: No way to disable sound. No way to configure AI difficulty. No multiplayer. » (Worldjoe, US, 4 juil. 2018, v3.13) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] Pas de coupure du son, demande la plus fréquente de 2014 à 2024 : « the sound effects are much too loud and I don't see any way to turn them off » (christofow, CA, 15 janv. 2014) ; « Still no sound options?!? » (DragonLost, US, 16 mars 2024) ; « ALLOW SOUNDS TO BE MUTED WITHOUT HAVING TO TURN OFF PHONE RINGER » (US, 2 mai 2024) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] Réponse rapportée du développeur : « Impossible de couper le son du jeu… signalé au dev qui m'indique que si je veux cette option il faut prendre la version payante » (Mikadenancy, FR, 29 nov. 2021) — [flux d'avis FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] Difficulté unique : « The game is set to a single difficulty. No way to change it. No instructions or how to. » (BlondieHound, CA, 1er janv. 2012) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Pas de choix de couleur ni d'adversaires : « I hate that you can't select your color or opponents, and it's AI only, no human players » (njpodder, oct. 2008) — [MacRumors](https://forums.macrumors.com/threads/lux-touch.578393/)
- [AVIS] Un seul mode de cartes (valeurs croissantes) : « this game only allows escalating matches » (ST.plaidman, CA, 30 mai 2011) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Avis discordant : « Tous les paramètres du joueur sont modifiables quand c'est son tour » (Carambar69, FR, 31 janv. 2026) — [flux d'avis FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json). Cet avis parle aussi d'un jeu « acheté », ce qui laisse penser qu'il décrit Lux DLX ou simplement les bascules.
- [OFFICIEL] Règles publiées sur le web (texte intégral consulté) : but « take over the entire map » ; à chaque tour on place, on attaque sans limite, on fortifie ; une carte par tour si l'on conquiert au moins un pays ; éliminer un joueur donne ses cartes ; encaissement obligatoire à 5 cartes ; revenu = (pays possédés / 3), minimum 3, plus bonus de continents ; explication du tableau et des deux bascules — [Lux Touch Instructions](https://sillysoft.net/lux/touch/instructions.php)
- [AVIS] Les règles sont un **lien externe**, pas un écran : « I think that the instructions should be within the app and not a link » (Scottc00, GB, 30 avr. 2011) ; « go to their site and read the instructions then enjoy! » (drbadmofo, AU, 17 nov. 2010) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json), [AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Absence d'aide dès l'origine : « there is no help screen » (bruthahood, AU, 24 nov. 2008) ; « The in-game hints are very helpful » (_Corin_, AU, 1er févr. 2009) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [OFFICIEL] Une forme de tutoriel existait en 1.0 : notes 1.0.1 (19 oct. 2008) « Fixes tutorial bug. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Toujours pas de tutoriel en 2020 : « maybe make a tutorial, when I first started it took me around a week to learn » (ryansssacc, US, 26 août 2020) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Pas de statistiques : « All you get at the end of game is a "you won" message. If it had scores, stats… » (dzeikei, AU, 5 févr. 2009) ; « mettre des stats » (FR, 4 déc. 2011) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [OFFICIEL] `isGameCenterEnabled: False` — [iTunes Lookup](https://itunes.apple.com/lookup?id=292538570&country=us)

### Inferences
- [INFÉRENCE] Le « tutoriel » de 2008 correspond au bandeau d'astuces contextuelles (les textes « Tap or hold… » visibles dès les captures iLounge de novembre 2008), pas à un écran pédagogique séparé.
- [INFÉRENCE] Si un lien vers les règles existe dans l'app en 3.x, il se trouve dans `Menu` ; non vérifié.
- [INFÉRENCE] L'avis US du 20 juin 2020 (« Having to pay for basic settings like sound », Joelnh) décrit le renvoi vers Lux DLX pour obtenir un réglage du son, cohérent avec la réponse du développeur rapportée en 2021.

### Gaps
- Aucune capture d'un écran de réglages, d'aide, de statistiques ou « À propos » ; je conclus à leur absence par convergence d'avis, sans preuve directe.
- Présence ou non d'un lien « Instructions » dans le menu 3.x : non vérifiée.

---

## 5. Publicités, achats intégrés, liens promotionnels : où apparaissent-ils ?

### Takeaway
Pas de régie publicitaire ni d'achat intégré : la seule promotion est l'auto-promotion de Lux DLX (texte + bouton `Get Lux DLX`) et de l'infolettre (`Newsletter`), affichée dans la boîte de fin de partie après chaque victoire.

### Cited Findings
- [OFFICIEL] « Lux Touch is fully FREE! No in-app purchases! No risk download! 100% free! » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [OFFICIEL] Confidentialité déclarée : « The developer does not collect any data from this app » (« Données non recueillies » sur la fiche CA-fr) — [fiche App Store CA-fr](https://apps.apple.com/ca/app/lux-touch/id292538570?l=fr-CA)
- [VU] Promotion in-app : texte « 100+ maps and tough-as-nails AI come in Lux DLX, for serious strategists. » (iPhone) / « Get Lux DLX for more game options, harder AI, and lots of maps! » (iPad) et boutons `Get Lux DLX` et `Newsletter` sur l'écran de victoire (IP5, ID5).
- [AVIS] Absence de publicité confirmée sur dix ans : « no ads » (Zakpol, GB, 16 juil. 2017) ; « without the need to push Advertisements » (Lyuldo Drop, US, 6 mai 2019) ; « No Ads!! … no ads or pop ups » (US, 12 sept. 2022) ; « No ads, a good risk clone » (US, 1er nov. 2025) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] En 2010 : « exactement le même mais adapté à l'écran de l'iPad, et sans pub ajoutée » (Lu2p, FR, 23 juin 2010) — [flux d'avis FR](https://itunes.apple.com/fr/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] L'auto-promotion est parfois perçue comme de la publicité : « Would love if it knew I paid for the upgraded version so I don't see ads » (thedeancorp, US, 24 déc. 2018) ; « the silly nag-screen every time you finish a game » (GB, 9 nov. 2015) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [OFFICIEL] Notes 3.0.1 : « Our full featured game Lux DLX has also been updated. For more maps and settings, check out Lux DLX on the app store. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [OFFICIEL] Autres apps Sillysoft listées sur la fiche (« Plus d'apps par Sillysoft Games ») : Lux DLX 3 (payant), Lux USA - American Civil War, Lux Roman Empire Conquest, Meowzers Action Cats, Mission Me, Turtoa — [fiche App Store CA-fr](https://apps.apple.com/ca/app/lux-touch/id292538570?l=fr-CA)

### Inferences
- [INFÉRENCE] La boîte promotionnelle n'apparaît qu'en fin de partie ; aucune capture ni avis ne signale de bannière pendant le jeu.
- [INFÉRENCE] La phrase « No more just leaving a blank banner I guess » (Mabrurh, CA, 18 nov. 2025) vise les autres jeux qui exigent une connexion pour afficher leurs publicités, pas Lux Touch.

### Gaps
- Écran de défaite : contient-il aussi la promotion Lux DLX ? Non vérifié.
- Destination exacte des boutons `Get Lux DLX` et `Newsletter` (App Store intégré, Safari, formulaire in-app) : non vérifiée.
- Présence éventuelle d'un lien Lux DLX dans le `Menu` : non vérifiée.

---

## 6. À quoi ressemble le design visuel ? Sons et musique ?

### Takeaway
Contrairement à l'hypothèse « fond spatial étoilé », le design actuel (3.x, depuis nov. 2013) est une **carte ancienne sur parchemin sépia** (rose des vents, galions gravés, volutes baroques) avec des territoires texturés aux couleurs franches ; l'original de 2008 utilisait un **océan bleu profond** texturé. Le son se limite à des effets de combat forts, impossibles à couper dans l'app.

### Cited Findings

**Version 3.x — tout [VU] sur IP1–IP5 / ID1–ID5**
- Fond : parchemin beige-sépia vieilli avec méridiens/parallèles fins, grande **rose des vents** brune en haut au centre (lettres W / E visibles), trois **gravures de voiliers** (ouest de l'Amérique du Nord, sud de l'Atlantique, est de l'Asie), **volutes ornementales** dans les coins ; un petit dragon/serpent de mer gravé à l'est de l'Asie est visible sur [YT-d](https://www.youtube.com/watch?v=P2eqdArQf4A).
- Territoires : aplats à texture de relief (aspect pierre/cuir) ; contours de continents épais et colorés ; frontières internes plus fines et sombres ; liaisons maritimes en **pointillés** bruns.
- Couleurs des joueurs : bleu roi (humain), rouge brique, vert sarcelle, orange doré (appelé « yellow » par les joueurs), noir/anthracite.
- Colonne de droite : dégradé bleu ardoise foncé ; icônes blanches à léger relief ; libellés blancs gras à contour sombre.
- Typographie in-app : sans-serif grasse de type Helvetica/Arial pour tous les textes (boutons, étiquettes de bonus, bandeau, boîte de fin). Les titres penchés en capitales usées (« TAKE OVER THE WORLD », « SHOW NO MERCY! », « WILL YOUR BORDERS HOLD? », « CALL FOR REINFORCEMENTS », « FAST-PACED WORLD DOMINATION ») sont des **bandeaux marketing ajoutés aux captures**, pas des éléments de l'app.
- Animations : gerbes de particules sur les lieux de combat — explosion orange/jaune et nuage de particules violet-bleu (ID4), nuage de particules noires (YT-f, YT-g) ; la couleur du nuage correspond à celle d'un des belligérants. — [capture iPad n°4](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/2d/0b/8f/2d0b8f65-f3c6-fa93-53a6-e8b36e785712/pr_source.png/2048x1536bb.png)
- Icône de l'app : globe bleu et blanc (Amériques) avec étoile dorée en relief en haut à droite, sur fond de rayons rouge-orangé — [icône 512 px](https://is1-ssl.mzstatic.com/image/thumb/Purple124/v4/5c/86/09/5c86098f-4b09-2f90-b098-4f56d597eaf8/AppIcon-0-1x_U007emarketing-0-0-GLES2_U002c0-512MB-sRGB-0-0-0-85-220-0-0-0-6.png/512x512bb.jpg)

**Sources complémentaires**
- [OFFICIEL] « Retina quality map graphics! » et « Faster animations! » (3.0, nov. 2013) ; « Improved display of very large armies » (3.1, 30 sept. 2016) ; « Adjusted colours for better visibility during night-shift mode » (3.20, 15 déc. 2018) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Les couleurs ajustées gênent un joueur daltonien : « Please make the players(colors) easier to see… The original colors worked fine but now it's just a loosing battle. » (knmoham, US, 4 juin 2020) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] « Short and simple animation but interesting » (Amy.808080, CA, 3 avr. 2022) ; « une interface grossière » (Lanflure, FR, 1er oct. 2016) ; « I love the newer interface » (divingwill, GB, 20 nov. 2013) — flux d'avis [CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [GB](https://itunes.apple.com/gb/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Un utilisateur attribue un plantage de 2018 aux « firework animations » (Cmreigrut, US, 18 nov. 2018) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] Sons : « loud bombing sound effects » (Maximus88888, US, 26 déc. 2019) ; « the gun sounds also coming through my speaker even when my phone is on silent » (Moose_Tash, GB, 30 avr. 2020) ; « Great graphics and good sound » (Paraquat59, AU, 25 avr. 2014) — flux d'avis [US](https://itunes.apple.com/us/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json), [GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [AVIS] Le jeu ignore le commutateur silencieux avec des écouteurs : « the game doesn't respect the silent switch on my iPhone when I'm using headphones » (Randall King, US, 12 févr. 2019) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [OFFICIEL] Historique audio : « Fix for SFX not respecting volume keys » (2.3, 20 oct. 2011) ; « Play music in the background from other apps » (2.4, 26 févr. 2012) ; « Sound effects and background music co-exist. » (3.0.1, 12 nov. 2013) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Indicateurs d'attente introduits en 2.0 : « the spinning wheel/"computer is thinking"/"computer is attacking" just adds to the sensation of being slow » (irish_kiwi, AU, 25 juin 2010) ; « status updates that block out some of the screen » (neilft, GB, 13 août 2010) — flux d'avis [AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json), [GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)

### Inferences
- [INFÉRENCE] Il n'y a pas de musique propre au jeu : les notes de version parlent de « background music » au sens de la musique d'autres apps, et les avis ne citent que des bruitages (explosions, tirs). Un avis de 2019 parle de « music/sounds » sans plus de précision ; non tranché.
- [INFÉRENCE] Les figurines napoléoniennes, le parchemin et les galions visent une ambiance « jeu de plateau d'époque » alignée sur Lux DLX 3, dont la 3.0 partage le socle technique (« big rewrite to modernize the Lux codebase »).

### Gaps
- Nature exacte des sons (liste des bruitages, jingle de victoire) : aucune source audio consultée.
- Animation de victoire (feux d'artifice ?) : seulement un avis indirect.
- Police exacte : identification visuelle approximative uniquement.

---

## 7. iPhone ou iPad, paysage ou portrait, écrans modernes, mode sombre, accessibilité, Mac ?

### Takeaway
App universelle iPhone/iPad depuis la 2.0 (juin 2010), avec la **même disposition** sur les deux (l'iPad montre simplement plus de carte en hauteur) et uniquement des preuves d'affichage **paysage** ; figée depuis janvier 2019, elle ne déclare aucune fonction d'accessibilité, précède le mode sombre d'iOS, n'est pas proposée sur Mac Apple Silicon et connaît des plantages signalés sur les iOS récents.

### Cited Findings
- [OFFICIEL] `features: ['iosUniversal']` ; iOS/iPadOS 11.0 minimum ; 55,1 Mo ; compatibilité affichée : iPhone, iPad, iPod touch, **Apple Vision (visionOS 1.0 ou ultérieur)** — [iTunes Lookup US](https://itunes.apple.com/lookup?id=292538570&country=us), [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [OFFICIEL] **Mac** : la fiche ne liste pas le Mac, et les données de la page portent `isIOSBinaryMacOSCompatible: false` pour Lux Touch (alors que d'autres apps de la même page portent `true` avec la mention « Designed for iPad. Not verified for macOS. ») — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570) (données embarquées, consultées 2026-11-25)
- [OFFICIEL] **Accessibilité** : « The developer has not yet indicated which accessibility features this app supports. » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [OFFICIEL] Historique des adaptations d'écran : « Uses the full display on iPads. » (2.0, 22 juin 2010) ; « Larger iphone5 screen size supported » (3.0, 1er nov. 2013) ; « Optimized display for plus sized iPhones » (3.11, 4 oct. 2016) ; « Support for iPhone X and Display Zoom mode » (3.13, 14 nov. 2017) ; « Better display on iPhone X, XR, and XS devices » (3.20–3.24, déc. 2018 – janv. 2019) — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [VU] **iPhone (16:9) et iPad (4:3) : même structure** — carte, colonne droite, tableau bas-gauche, logo haut-droite, bandeau bas-droite. Différences observées : sur iPad la carte est plus haute (nord du Canada, Groenland et pointe de l'Amérique du Sud davantage visibles, grande zone de parchemin vide en bas) ; le tableau des joueurs flotte plus haut (≈ 65–75 % de la hauteur en ID2/ID5, contre le coin bas-gauche en IP1/IP4) ; la colonne de droite a la même largeur relative et les mêmes boutons. Sur iPhone 16:9, le haut de l'Amérique du Nord et le Groenland sont **rognés** par le bord supérieur (IP1–IP5).
- [VU] Sur iPhone à encoche (≈ 2020, YT-g), le plateau est affiché dans un rectangle centré avec des **marges noires** latérales et l'indicateur d'accueil d'iOS reste visible en bas ; l'image ne s'étend pas bord à bord. — [vidéo #3](https://www.youtube.com/watch?v=gIGw3GdJNIs)
- [VU] Toutes les captures (2008–2019) et toutes les images de vidéos (2008–2020) sont en **paysage** ; aucune image en portrait.
- [AVIS] Orientation : « The screen turns upside down and soon after the game starts it always crashes » (Lorisidae, AU, 3 nov. 2013, v3.0) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] Cadrage : « The display doesn't properly fit the screen since the new update and I can't see Greenland anymore » (PeteWTF, GB, 1er oct. 2016, v3.1) ; « there are some regions that aren't on the screen » (mr.cats147, US, 3 juin 2020, v3.24) — flux d'avis [GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [US](https://itunes.apple.com/us/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)
- [AVIS] iPad en 2010 : « The map has been scaled up for the bigger iPad screen, but it seems other interface elements haven't been. Now the armies count is a tiny little circle in each country » (Dai Jones, GB, 23 juin 2010, v2.0) ; corrigé par « Clearer army numbers » (2.1, 27 juil. 2010) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json), [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)
- [AVIS] Préférence pour l'iPad : « Still works on iPhone XS… but phone screen is too small for that to be practical » (AlgoTectodo, US, 25 nov. 2018) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] État en 2025 : « with the latest Apple update it crashes all the time. With no updates in the past 6 years » (ElvisOut, US, 7 déc. 2025) ; « keep freezing up on my iPhone » (US, 10 déc. 2025) ; « PLEASE update w/ios 26 » (cinderfire8, US, 30 nov. 2025) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- [OFFICIEL] Notes globales : 4,25/5 sur 871 évaluations (US), 4,39/5 sur 161 (CA) au 2026-11-25 — [iTunes Lookup US](https://itunes.apple.com/lookup?id=292538570&country=us), [CA](https://itunes.apple.com/lookup?id=292538570&country=ca)

### Inferences
- [INFÉRENCE] Paysage uniquement (les deux sens, vu l'avis « upside down ») ; pas de mode portrait. Non confirmé par une source explicite.
- [INFÉRENCE] Pas de prise en charge du **mode sombre** : la dernière version (janv. 2019) est antérieure à iOS 13 (sept. 2019) ; l'app dessine de toute façon une interface entièrement personnalisée. La mention « night-shift mode » des notes concerne la lisibilité des couleurs sous Night Shift, pas un thème sombre.
- [INFÉRENCE] Pas de **VoiceOver** ni de **Dynamic Type** utilisables : interface graphique sur mesure (carte, bulles), aucune fonction déclarée, aucun avis n'en parle. À vérifier sur appareil.
- [INFÉRENCE] Pas d'adaptation aux formats postérieurs à l'iPhone XS Max (multitâche iPad Split View, iPad Pro 11"/13" récents) : aucune note de version après 2019 ; l'app s'afficherait à l'échelle avec bandes.

### Gaps
- Confirmation directe du verrouillage paysage, du comportement en Split View/Stage Manager et sur visionOS : non vérifiée.
- Comportement VoiceOver réel : non testé, aucune source.
- Je n'ai pas pu vérifier sur appareil si l'app se lance encore sous l'iOS courant ; les avis de fin 2025 sont contradictoires (plantages pour certains, « still love playing it » pour d'autres).
- Version Android : **il n'existe pas de Lux Touch sur Google Play** au 2026-11-25. La page développeur ne liste que Lux DLX (`com.sillysoft.LuxDLX`), Mission Me, Turtoa et Meowzers — [Google Play, Sillysoft Games](https://play.google.com/store/apps/developer?id=Sillysoft+Games&hl=en). Aucune comparaison Android de Lux Touch n'est donc possible ; je n'ai pas analysé les captures Android de Lux DLX.

---

## 8. Comment l'interface a-t-elle évolué (2008 → aujourd'hui) ?

### Takeaway
Trois états d'interface : **v1 (oct. 2008)**, carte sur océan bleu avec seulement trois boutons (`Bonus`, `Fortify`, `End`) ; **v2 (juin 2010 – 2012)**, même habillage étendu à l'iPad, avec reprise de partie et indicateurs d'attente, très critiqué pour sa lenteur ; **v3 (nov. 2013 – janv. 2019)**, refonte graphique « parchemin » Retina avec `Menu`, bascules rapides et figurines, puis simples adaptations d'écran. Plus aucune mise à jour depuis le 23 janvier 2019.

### Cited Findings

**Chronologie officielle** — [fiche App Store US, historique des versions](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570)

| Version | Date | Changement d'interface déclaré |
|---|---|---|
| 1.0 | 7 oct. 2008 | Sortie (iPhone / iPod touch) |
| 1.0.1 | 19 oct. 2008 | « Fixes tutorial bug. » |
| 2.0 | 22 juin 2010 | « Uses the full display on iPads. » |
| 2.1 | 27 juil. 2010 | « Clearer army numbers. Performance improvements. » |
| 2.2 | 29 août 2011 | Correctif de reprise de partie quand l'humain est éliminé |
| 2.3 | 20 oct. 2011 | iOS 5 ; effets sonores respectant les touches de volume |
| 2.4 | 26 févr. 2012 | Musique d'autres apps en arrière-plan |
| 3.0 | 1er nov. 2013 | Menu de redémarrage, animations plus rapides, modes Auto-Advance et All-Attack, écran iPhone 5, carte Retina, réécriture du code |
| 3.0.1 | 12 nov. 2013 | Encaissement de plusieurs jeux de cartes ; stabilité, batterie |
| 3.0.2 | 16 déc. 2013 | Le mode cartes annonce les prochaines valeurs d'échange |
| 3.1 / 3.11 | 30 sept. / 4 oct. 2016 | iOS 10, iPhone Plus, affichage des très grandes armées |
| 3.12 | 31 mars 2017 | « Bugfixes » |
| 3.13 | 14 nov. 2017 | iPhone X et mode Zoom de l'affichage |
| 3.20 → 3.24 | 15 déc. 2018 → 23 janv. 2019 | Affichage iPhone X/XR/XS, couleurs ajustées pour Night Shift, correctifs de plantage |

Metacritic indique une sortie au 30 septembre 2008, ce qui contredit le 7 octobre 2008 de l'App Store — [Metacritic, Lux Touch](https://www.metacritic.com/game/lux-touch/) (date vue dans un extrait de recherche seulement ; l'App Store fait foi).

**État 2008 (v1.0.x) — [VU] sur IL1–IL3, PG1, YT-a**
- Fond **bleu profond texturé** (océan) ; liaisons entre territoires en **traits clairs pleins** ; boussole discrète derrière le tableau ; petit dragon/serpent de mer argenté en bas au centre.
- Logo : « Lux » en lettres sombres de style gothique sur parchemin avec globe, haut-droite.
- Colonne de droite : barre verticale colorée, puis seulement `Bonus` (étoile), `Fortify` (château), `End` (octogone). **Pas de `Menu`, pas de bascules.** En placement : `Bonus` puis `1` / `Army To Place` + pictogramme.
- Bandeau d'aide bas-droite, fond sarcelle translucide : « Tap or hold to divide your armies between the two countries. » (IL1).
- Tableau bas-gauche déjà identique (4 icônes) ; les **joueurs éliminés restent affichés** avec une ligne de zéros (IL3 : lignes `0 0 0 0`).
- Territoires en aplats lisses, bulles d'armées colorées **sans figurines**.
- Captures : [iLounge](https://www.ilounge.com/index.php/articles/comments/iphone-gems-puzzle-board-mystery-games) (24 nov. 2008), [Pocket Gamer](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation/) (14 oct. 2008)
- [AVIS] Presse 2008 : « recreates the Risk gameplay in a colourful and concise manner, offering simple touchscreen controls » (Spanner Spencer) — [Pocket Gamer](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation/) ; iLounge note B+ et décrit « a map of most of the world… initially colored either blue, red, green, yellow, or black » (Jeremy Horwitz) — [iLounge](https://www.ilounge.com/index.php/articles/comments/iphone-gems-puzzle-board-mystery-games)
- [AVIS] Manques de 2008 : ni menu, ni son coupable, ni sauvegarde (« when i get a phone call or go back to home menu the game doesn't save total fun killer ») ; longues pauses en fin de partie sans indicateur (« Some kind of "thinking" icon would help ») ; forte consommation de batterie — [MacRumors](https://forums.macrumors.com/threads/lux-touch.578393/) (10–14 oct. 2008)

**État 2010–2012 (v2.x) — [VU] sur YT-b, YT-c**
- Même habillage bleu et même colonne `Bonus` / `Fortify` / `End` ; bandeaux d'aide lus : « Tap or hold countries you own to place armies » (lecture approximative, YT-b) et « Tap or slide an enemy country to attack. » (YT-c).
- [AVIS] La 2.0 a dégradé l'ergonomie : « slow, unresponsive to taps and has a clunky feel… Precision has gone in troop deploying » (irish_kiwi, AU, 25 juin 2010) ; « you tap once and suddenly every army you've got spare goes on one spot instead of just one » (Franton, GB, 8 juil. 2010) ; « a destroyed colour is no longer recorded on the board » (irish_kiwi) ; « Seul les couleurs bleu et noir sont un poil mieux visible… Pas de bouton pour quitter la partie » (Marcomp, FR, 2 août 2010) — flux d'avis [AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json), [GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json), [FR](https://itunes.apple.com/fr/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] La 2.1 a rétabli la netteté : « fixed the blurriness and unresponsiveness » (neilft, GB, 13 août 2010) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=3/id=292538570/sortby=mostrecent/json)
- [AVIS] Presse 2010 : « There's very little meat to this version of Lux and the interface could use a little work, but it's the best Risk imitator zero dollars can buy. » — [Kotaku, « The iPhone's Best Free Games Right Now »](https://kotaku.com/the-iphones-best-free-games-right-now-5686675) (11 nov. 2010)

**État 2013–2019 (v3.x) = interface actuelle — [VU] sur IP/ID, YT-d à YT-g**
- Voir questions 1, 2 et 6. Résumé des ajouts : fond parchemin, logo LUX rouge, `Menu`, bascules `1-Attack`/`All-Attack` et `Manual`/`Auto`, figurines, annonce des prochaines valeurs d'échange, boîte de fin avec trois boutons, tableau limité aux joueurs vivants.
- [AVIS] Accueil de la 3.0 : « The retina display support is very welcome and looks great » (Jac1709, AU, 2 nov. 2013) ; « The new version is a graphic and function improvment » (Sylvano18, CA, 14 nov. 2013) ; mais plantages sur iPad 1 et iPod touch 4 au lancement — flux d'avis [AU](https://itunes.apple.com/au/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json), [CA](https://itunes.apple.com/ca/rss/customerreviews/page=2/id=292538570/sortby=mostrecent/json)

**Contexte 2026 (ne concerne pas Lux Touch directement)**
- [OFFICIEL] Le 18 octobre 2026, Sillysoft annonce « the biggest Lux DLX update in years » sur Android, « iPhone & iPad: coming soon », avec notamment un tableau des joueurs plus intelligent (« a tap brings up your cards any time on your turn »), un graphique de fin de partie, des statistiques et « a Sound Effects volume slider ». L'annonce ne mentionne **pas** Lux Touch. — [sillysoft.net, News #94](https://sillysoft.net/news/#94)

### Inferences
- [INFÉRENCE] Le « fond spatial étoilé à bordures lumineuses » évoqué dans la consigne ne correspond à aucune version documentée de Lux Touch ; l'ancien fond bleu foncé à traits clairs (2008–2012) peut en donner l'impression sur des vidéos sombres.
- [INFÉRENCE] Le geste « slide » pour attaquer a pu disparaître ou subsister en 3.x ; les textes officiels actuels ne parlent que de « tap » et « hold ».
- [INFÉRENCE] Les captures de la fiche App Store datent de la période 3.1–3.24 (format 16:9 iPhone 6/7 et iPad Retina ; identiques à l'interface filmée vers 2015–2020). Elles montrent donc bien l'interface courante, à l'exception d'éventuels ajustements de teintes de la 3.20.
- [INFÉRENCE] Les améliorations annoncées pour Lux DLX en octobre 2026 (curseur de volume, cartes consultables, statistiques) correspondent exactement aux manques reprochés à Lux Touch ; rien n'indique qu'elles y seront portées.

### Gaps
- Aucune capture nette de la v2.x sur iPad (2010–2012).
- Date exacte de mise en ligne des captures actuelles de la fiche : inconnue.
- Vidéos YouTube : dates exactes, descriptions et transcriptions non obtenues (HTTP 429).

---

## 9. Quels reproches et quels éloges d'interface reviennent chez les utilisateurs et les critiques ?

### Takeaway
Éloges : simplicité, rapidité des parties, lisibilité de la carte, absence de publicité, jeu hors ligne. Reproches récurrents, par ordre de fréquence dans les 750 avis lus (AU, CA, FR, GB, US ; 2008–2026) : **impossible de couper le son**, **tours des IA trop lents** avec de grosses armées, **aucun réglage ni tutoriel**, **imprécision du toucher / erreurs de sélection sans annulation**, cartes peu expliquées, puis plantages liés aux mises à jour d'iOS.

### Cited Findings

Source commune : flux d'avis App Store « most recent », 3 pages × 5 pays, 750 avis uniques, extraits le 2026-11-25 — [US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json), [FR](https://itunes.apple.com/fr/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json). Tous les éléments ci-dessous sont des [AVIS].

**Reproches**

| Thème | Citations représentatives |
|---|---|
| Son non désactivable | « this game needs a mute option. The audio is not necessary to the game play » (Gavan W., US, 19 avr. 2020) ; « Please Integrate mute » (FR, 2 avr. 2017) ; « Sound off option please » (AU, 24 août 2022) ; « It's like sudoku with noise » (Dino buddy, CA, 5 mai 2014) |
| Volume lié à la sonnerie (v2.x) | « it overrides the phone's volume control. I think its linked to the ringer volume » (CA, 11 mai 2011) ; « Lux makes me miss calls » (CA, 30 mai 2011) |
| Lenteur des tours IA | « when the computer attacks with a large army it takes foreverrrrr » (Gavan W., 2020) ; « when the AI makes the same attack it can take 20 minutes » (Anon9966, AU, 3 mars 2013) ; « Frustratingly slow when computer attacks with lots of armies » (GB, 21 avr. 2016) |
| IA trop rapide à suivre (avis inverse) | « how fast the A.I. is... you can barely understand what's going on half the time! » (Worlygirl, US, 4 mars 2018) |
| Aucun menu / réglage | « Needs menu: Please add a menu and options, a tutorial would be good too. » (GB, 27 avr. 2011) ; « il manque un menu pour changer les paramètres, changer le nombre de joueur par exemple ou la difficulté » (Bossu78, FR, 22 janv. 2012) ; « I could[n't] figure out how to bring up ANY menu in this game » (GadgetsPlus, CA, 29 févr. 2012) |
| Pas d'instructions | « those new to the game may be lost as there is nearly no documentation » (Heirware, AU, 24 déc. 2009) ; « Having the instructions clear at the beginning would be more helpful. Especially to explain the cards clearly » (Aza_85, GB, 3 août 2017) |
| Cartes incomprises | « a better explanation of how the 'cards' in the game actually work as their appearance seems random » (GB, 14 sept. 2025) ; « There's no indication of how territories or cards give armies » (GB, 15 juil. 2010) |
| Toucher imprécis, erreurs | « the controls are touchy and I often was attacking the wrong country or reinforcing the wrong country » (Rom 12, AU, 1er oct. 2009) ; « Imprécision du toucher » et « armées qui bougent en lots intempestifs » (GGMFTC, FR, 2 sept. 2010) ; « the small screen sometimes selects wrong move » (2pages, GB, 3 mai 2011) |
| Lot involontaire au maintien | « Quicker army movements when you have 100 units in one country it is slow to move/reinforce » (Theperfectjez, AU, 3 févr. 2009) contre « you tap once and suddenly every army… goes on one spot » (Franton, GB, 8 juil. 2010) |
| Bogues de fortification | « Fortification freezes when you are winning and you have to force close » (GB, 20 nov. 2013) ; « Occasionally loose an army or two when fortifying » (CA, 6 avr. 2017) ; « pieces disappear instead of reinforcing my position » (US, 25 sept. 2021) ; compteur qui double (00cho, US, 13 déc. 2021) |
| Couleurs peu distinctes | avis daltonien (knmoham, US, 4 juin 2020) |
| Cadrage | Groenland ou régions hors écran (GB 2016, US 2020) |
| Pas de sauvegarde (v1) | très nombreux avis 2008–2010 ; ex. « an incoming txt message wipes the game! » (AU, 14 avr. 2009) |
| Batterie / chauffe | « my iphone 5s heats up dramatically » (AU, 2 nov. 2013) ; « High battery drain app » (CA, 6 avr. 2017) |
| Plantages après mises à jour | vagues d'avis 1 étoile : v2.0 (juin 2010, lenteur), v2.3 (oct. 2011, iOS 5), iOS 11.4/12 (2018), v3.22 (16–18 janv. 2019, iPhone X), fin 2025 |
| Écran de fin promotionnel | « silly nag-screen » (GB, 9 nov. 2015) |

**Éloges**

| Thème | Citations représentatives |
|---|---|
| Simplicité et prise en main | « Great game. Simple to use. Looks good. » (ADHemsley, GB, 14 févr. 2014) ; « Easy, simple, brilliant » (GB, 1er sept. 2015) ; « Simple mais efficace » (FR, 8 août 2018) |
| Parties rapides | « Fast-paced » ; « With Lux, that's reduced to about 10 minutes » (oldmankit, GB, 2015) ; « Rapide et fluide. De super partie rapide sans tour interminable » (FR, 13 déc. 2014) ; « It's a nice way to kill 3-4 minutes » (US, 17 janv. 2019) |
| Lisibilité | « Graphics are nice, but not overwhelming. Map is easy to understand. » (VanillaSpice, AU, 29 nov. 2008) ; « I'm pretty impressed with the amount of complexity that's fit into such a small screen » (kristarella, AU, 6 juil. 2010) ; « its a great interface » (Kustav101, AU, 20 août 2009) |
| Lancement immédiat | « The app loads faster than any other game I have played » (Locky015, GB, 2 oct. 2014) |
| Sans publicité, hors ligne | « no ads, 100% free » (US, 17 déc. 2021) ; « you can play offline! » (US, 18 janv. 2019) ; « the only game I could play without an internet connection » (CA, 18 nov. 2025) |
| Graphismes 3.x | « I favor Lux's gameplay & graphics » (US, 25 janv. 2019) ; « Looks good, sounds good, doesn't stutter » (Franton, US, 26 juin 2023, par ailleurs 1 étoile pour l'IA) |
| Meilleure que la version payante en fluidité (2009–2010) | « Cette version gratuite est meilleure que la payante: plus rapide, plus réactive, plus simple » (jpmu, FR, 22 mars 2009) |

- [AVIS] Critiques professionnelles : Pocket Gamer (14 oct. 2008) salue des « simple touchscreen controls » — [source](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation/) ; iLounge (24 nov. 2008) note B+ et prévoit qu'on se lasse « of the map, computer AI, and difficulty level » — [source](https://www.ilounge.com/index.php/articles/comments/iphone-gems-puzzle-board-mystery-games) ; Kotaku (11 nov. 2010) : « the interface could use a little work » — [source](https://kotaku.com/the-iphones-best-free-games-right-now-5686675)
- [OFFICIEL] Argument de la fiche : « Voted #1 iPhone game by Wired.com readers! » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch-3-world-domination/id292538570) (sondage d'origine non retrouvé)

### Inferences
- [INFÉRENCE] Les reproches « pas de menu » et « pas de bouton pour recommencer » sont antérieurs à la 3.0 et partiellement résolus ; « pas de son coupable », « pas de difficulté », « pas de tutoriel », « tours IA lents » et « pas d'annulation » restent valables en 3.24, puisqu'ils sont encore formulés entre 2020 et 2025.
- [INFÉRENCE] Le conseil officiel d'utiliser l'auriculaire et les plaintes de sélection erronée désignent le même problème : des cibles tactiles trop petites sur les petits territoires (Europe, Asie du Sud-Est, Amérique centrale) sans zoom ni confirmation.
- [INFÉRENCE] La simplicité extrême (un seul écran, zéro réglage, démarrage direct) est à la fois le premier motif d'éloge et le premier motif de reproche.

### Gaps
- Je n'ai lu que les 3 premières pages « most recent » par pays (750 avis) ; les avis plus anciens que ceux renvoyés par le flux ne sont pas couverts.
- Pas de test critique récent (TouchArcade, 148Apps, AppAdvice, Macworld, Slide to Play, Common Sense Media) trouvé pour Lux Touch ; AppAdvice et AppSpy ont traité Lux DLX, non analysé ici.
- Le fil TouchArcade de 2008 cité par un membre de MacRumors n'a pas été retrouvé.
- Sondage Wired.com « #1 iPhone game » : source primaire non retrouvée.
