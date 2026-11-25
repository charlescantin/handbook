# Règles du jeu et mécaniques de Lux Touch (Sillysoft Games, iOS, app id 292538570)

> Notes de recherche rédigées le 2026-11-25. Version décrite : **Lux Touch 3 – World Domination, v3.24 (dernière mise à jour 2019-01-23)**, toujours la version courante sur l'App Store à la date de recherche.
>
> **Niveaux de preuve utilisés partout ci-dessous**
> - **(a)** confirmé par une source officielle portant spécifiquement sur Lux Touch (page Sillysoft « Lux Touch », instructions officielles, fiche App Store, captures d'écran officielles de l'App Store).
> - **(b)** confirmé par un test indépendant ou un joueur parlant de Lux Touch (avis App Store US/CA/GB/AU, presse).
> - **(c)** documenté seulement pour Lux Delux (bureau) / SDK Sillysoft, et supposé hérité.
> - **(d)** non vérifié.
>
> **Avertissements méthodologiques importants**
> 1. La page officielle d'instructions est **commune à Lux Touch et Lux DLX** : l'URL `/lux/dlx/instructions.php` redirige vers `/lux/touch/instructions.php`, et son texte reprend presque mot pour mot la page « Basics » du wiki Lux Delux. Certaines phrases sont donc génériques (« the map », « can increase »).
> 2. Les avis App Store (1 629 avis uniques collectés via le flux RSS public d'Apple, boutiques US, CA, GB, AU, datés du 2008-10-07 au 2026-11-21) sont des témoignages individuels ; quelques auteurs confondent manifestement Lux Touch et Lux DLX (voir section Carte).
> 3. Les captures d'écran officielles ont été lues par moi (image → chiffres) ; les chiffres lus sont de niveau (a), mais tout calcul qui en découle est classé en « Inférences ».
> 4. Sources **inaccessibles** pendant la session : web.archive.org (bloqué par la politique réseau), fils du forum sillysoft.net (403 / anti-robot), forums.macrumors.com (403), mobygames.com (403), appadvice.com (hôte non autorisé). Aucune réponse du développeur « dustin » sur le forum n'a donc pu être lue.

---

## 1. Combien de joueurs ? Couleurs/positions fixes ? Multijoueur ?

### Takeaway
Lux Touch est un jeu strictement solo : l'humain joue toujours les armées **bleues** contre des IA de couleurs fixes ; la configuration attestée est **1 humain + 4 IA (rouge, vert/sarcelle, jaune/orange, noir) = 5 joueurs**, sans aucun multijoueur (ni hot-seat, ni en ligne). Le chiffre « 5 IA » n'est étayé par aucune source.

### Cited Findings
- **(a)** « Control the Blue armies and conquer the map. » ; « Faster, free, with fun varied computer AIs! » — [Fiche App Store US, description, consultée 2026-11-25](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(a)** Capture iPad officielle n° 1 : le tableau des joueurs comporte **5 lignes** (bleu 8 pays/24 armées/0 carte/revenu 3 ; rouge 7/24/1/3 ; vert 7/26/1/3 ; orange 14/22/1/4 ; noir 6/25/0/3) et la barre latérale affiche 5 couleurs (bleu, rouge, vert, orange, noir) — [capture App Store iPad 1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/03/25/fd/0325fd5a-bc4f-8e7b-678c-8663add0e246/pr_source.png/1600x1200bb.png)
- **(a)** Captures iPhone officielles montrant des états à **4 joueurs** : bleu 11/30/0/8, rouge 9/28/0/5, vert 7/26/0/5, noir 15/30/1/10 (pas d'orange) — [capture iPhone 4](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/f0/9a/06/f09a0673-59cc-6b16-af02-f3d95f7e3b08/pr_source.png/1600x1200bb.png) ; rouge 10/30/0/3, noir 10/28/0/3, orange 11/30/0/5 visibles, barre latérale bleu/rouge/noir/orange (pas de vert) — [capture iPhone 1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/09/5a/3b/095a3be5-2083-329e-fab2-2ac977a7739d/pr_source.png/1600x1200bb.png)
- **(b)** Les joueurs décrivent systématiquement quatre adversaires : « Green, yellow, black and red, in order of difficulty » (MackClews, CA, 2010-06-23) ; « yellow, green red and black get huge amounts of armies and blue gets nothing » (westwill, CA, 2009-09-20) ; « Red… Orange… Black… Teal » (Lyuldo Drop, US, 2019-05-06, v3.24) — [flux d'avis App Store CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Couleur non choisissable et demandée par les joueurs : « Choose colour », « Manual color and location chosing » (Theperfectjez, AU, 2009-02-03 ; Verners, GB, 2009-01-20) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** Le multijoueur est un argument de la version payante, pas de Lux Touch : Lux DLX apporte « Hot-seat multi-player », « more human players » — [page officielle Lux Touch](https://sillysoft.net/lux/touch/) ; [fiche App Store](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(a, pour DLX)** « Set multiple players to Human to play hot-seat games. […] You need a Mac or PC to play online networked multi-player Lux. » — [page officielle Lux DLX](https://sillysoft.net/lux/dlx/)
- **(b)** Demandes récurrentes de multijoueur sur Lux Touch : « It's just that there's only one map…and can't play with friends » (notBARAA, AU, 2022-12-30) ; « make it linkable by internet my dad and I love playing this game but I wish we could play it together » (ryansssacc, US, 2020-08-26, v3.24) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** Lux Delux : « Games can have 2-6 players » avec IA au choix — [wiki Lux, Main Game Window](https://sillysoft.net/wiki/?Main%20Game%20Window)
- **(a)** `isGameCenterEnabled: false` (pas de Game Center) — [API iTunes Lookup](https://itunes.apple.com/lookup?id=292538570&country=us)

### Inferences
- Partie standard = 5 joueurs (bleu humain + rouge, vert, jaune/orange, noir). Le « jaune » des avis de 2008-2018 et l'« orange »/« beige » des avis récents désignent le même joueur (la teinte affichée en v3 est orange).
- Les captures à 4 joueurs sont compatibles avec une partie en cours après élimination d'une IA ; rien n'indique que le nombre de joueurs au départ varie.
- L'ordre des lignes du tableau change d'une capture à l'autre (orange avant noir sur iPad 1, noir avant orange sur iPhone 1) : l'ordre des sièges des IA semble donc tiré au sort à chaque partie, le bleu restant en tête de tableau.

### Gaps
- Aucune source officielle n'écrit noir sur blanc « 4 adversaires IA » ; le chiffre vient des captures et des avis.
- « 1 humain contre 5 IA » : aucune preuve trouvée (d).
- Impossible de confirmer si la partie peut démarrer à 4 joueurs.

---

## 2. Quelle carte ? Territoires, continents, bonus ; autres cartes ?

### Takeaway
Lux Touch 3 propose **une seule carte du monde de 42 pays en 6 continents**, avec les bonus de départ North America 5, Europe 5, Asia 7, Africa 3, South America 2, Australia 2 (identiques au Risk classique) ; les bonus de continent **augmentent en cours de partie**. Les autres cartes (100+) sont réservées à Lux DLX / Lux Delux ; l'habillage de la carte a changé avec la v3.0 (2013).

### Cited Findings
- **(a)** Écran « Bonus » : « North America bonus: 5 », « Europe bonus: 5 », « Asia bonus: 7 », « Africa bonus: 3 », « South America bonus: 2 », « Australia bonus: 2 » — [capture App Store iPad 1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/03/25/fd/0325fd5a-bc4f-8e7b-678c-8663add0e246/pr_source.png/1600x1200bb.png)
- **(a)** Écran de victoire : le vainqueur possède **42** pays (tableau « 42 / 135 / 6 / 38 ») — [capture App Store iPad 5](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/b1/02/1b/b1021b8d-7682-e9fa-2400-15d36dcf0d3a/pr_source.png/1600x1200bb.png) ; autre victoire « 42 / 221 / 4 / 39 » — [capture iPhone 5](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/0c/e5/db/0ce5dbff-7daf-7c7d-c3dd-24ccd7da9566/pr_source.png/1600x1200bb.png)
- **(a)** Noms de pays visibles sur les cartes à jouer : Ukraine, Indonesia, Afghanistan, Japan — [capture iPad 3](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/d6/4e/a8/d64ea87f-ab13-f644-dbea-55d675c1bdb9/pr_source.png/1600x1200bb.png) ; [capture iPhone 3](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/14/a9/af/14a9afa9-aaea-f16c-c928-4c007f4a9169/pr_source.png/1600x1200bb.png)
- **(a, texte commun Touch/DLX)** « Use the Bonuses button to look at the regions for the map. Continent bonus values can increase as the game progresses. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** Les autres cartes sont dans la version payante : « Get our premium game Lux DLX for… more maps » ; écran de victoire « Get Lux DLX for more game options, harder AI, and lots of maps! » / « 100+ maps and tough-as-nails AI come in Lux DLX » — [fiche App Store](https://apps.apple.com/us/app/lux-touch/id292538570) ; [capture iPad 5](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/b1/02/1b/b1021b8d-7682-e9fa-2400-15d36dcf0d3a/pr_source.png/1600x1200bb.png) ; [capture iPhone 5](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/0c/e5/db/0ce5dbff-7daf-7c7d-c3dd-24ccd7da9566/pr_source.png/1600x1200bb.png)
- **(b)** Une seule carte : « the lite version only contains one map » (Gregory Sandhills, CA, 2014-07-20, v3.0.2) ; « This is just a single world map » (CartoonBomb, US, 2016-02-16) ; « there is only one map » (MickeyCorrigan, CA, 2017-04-07, v3.12) ; « there's only one map » (notBARAA, AU, 2022-12-30, v3.24) ; déjà en 2008 : « the one map in the current version » (Shrek1895, GB, 2008-11-21) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b, contradictoire)** Quelques avis déposés sur la fiche Lux Touch parlent de plusieurs cartes : « The ability to change maps is awesome » (Procinctu, US, 2016-09-21) ; « I've tried the other maps but I like the Risk board the most » (TL22, US, 2017-04-09) ; « Anytime I try to play a map that the game didn't come with, the app crashes » (orcaraptor, US, 2014-03-14) ; un avis décrit explicitement DLX sur la fiche de Touch (« Lux DLX one of my favorites », Pumpkinnpie, US, 2024-10-15) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; contredit par les avis « one map » ci-dessus et par la description officielle (« more maps » = DLX)
- **(b)** Changement de carte/habillage avec la v3.0 : « the map I happily played for several years has even replaced by a lesser map with the old map now for sale at too high a price » (MaraKei, US, 2013-12-20, v3.0.2) ; « Simpler map and smooth gameplay » (Amy.808080, CA, 2022-04-03) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** v3.0 (2013-11-01) : réécriture majeure avec « retina map graphics » ; v2.1 (2010-07-27) : plein écran iPad — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(Base Risk classique, pour comparaison)** 42 territoires, 6 continents : North America 9 (bonus 5), South America 4 (2), Europe 7 (5), Africa 6 (3), Asia 12 (7), Australia 4 (2) — [Wikipedia, Risk (game)](https://en.wikipedia.org/wiki/Risk_(game))
- **(c)** Lux Delux inclut une carte « Classic » (« The classic map of the world », v2.0 du 2007-11-22) et plus de 900 cartes au total — [page carte Classic](https://sillysoft.net/lux/maps/Classic) ; [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game))
- **(c)** Le moteur Lux expose un « percent increase of the continents » (`getContinentIncrease()`) et Lux Delux a une option « Continent Increase » par partie — [SDK Sillysoft, Board.java](https://sillysoft.net/sdk/) ; [journal des versions Lux Delux](https://sillysoft.net/lux/changelog.php)

### Inferences
- 42 pays + bonus 5/5/7/3/2/2 + noms classiques (Ukraine, Afghanistan, Indonesia, Japan) ⇒ la carte de Lux Touch 3 reprend très probablement le découpage classique (NA 9, SA 4, Europe 7, Afrique 6, Asie 12, Australie 4) ; le décompte par continent n'a pas été lu pays par pays sur l'image.
- **Hausse des bonus observée sur les captures officielles** : sur la [capture iPad 2](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/3e/fd/8e/3efd8e33-07a3-d475-bfc0-77ad4a4b2881/pr_source.png/1600x1200bb.png) (tableau lu : bleu 23 pays/263 armées/2 cartes/revenu 20 ; rouge 5/102/1/3 ; noir 14/101/1/11), bleu a 23 pays et un revenu de 20 (23÷3 = 7 ; reste 13 pour Asie + Australie, dont la base est 9), noir a 14 pays et un revenu de 11 (14÷3 = 4 ; reste 7 pour l'Amérique du Nord, base 5) ; sur la [capture iPhone 2](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/0b/c4/86/0bc486b3-7554-e28f-f288-f35e70659de6/pr_source.png/1600x1200bb.png) (bleu 28/98/0/32 ; vert 14/34/3/7), vert a 14 pays et un revenu de 7 (4 + Australie à 3 au lieu de 2). L'attribution des continents à chaque joueur repose sur ma lecture visuelle des captures. À l'inverse, l'écran de victoire iPad 5 donne 38 = 14 + 24 (aucune hausse) et l'iPhone 5 donne 39 (+1). La hausse est donc progressive, de l'ordre de +40 à +50 % en partie avancée ; **le taux exact par tour est inconnu**.
- Les avis évoquant plusieurs cartes sur la fiche de Lux Touch concernent presque certainement Lux DLX (confusion de fiche) : aucune fonction de choix de carte n'apparaît dans les captures ni la description de Lux Touch.

### Gaps
- Taux et rythme exacts d'augmentation des bonus de continent dans Lux Touch (d).
- Liste nominative des 42 pays et de leurs frontières dans Lux Touch 3 (non publiée ; vraisemblablement la carte Classic de Lux).
- La carte d'avant la v3.0 (2008-2013) avait-elle le même découpage en 42 pays ? Non vérifié ; un joueur parle d'une « large map with lots of small countries » (Mark Williams, GB, 2008-10-14) et un autre affirme que l'ancienne carte est « now for sale » (dans DLX, non vérifié).

---

## 3. Mise en place : distribution, armées initiales, premier joueur

### Takeaway
La mise en place est entièrement automatique et aléatoire : au lancement, les 42 pays sont déjà répartis et garnis, sans choix de territoires ni placement initial par le joueur. Le nombre exact d'armées de départ et l'identité du premier joueur ne sont documentés nulle part.

### Cited Findings
- **(b)** « The initial set up of pieces happens automatically, yet that is one of the most fun and strategic parts of playing the real Risk. » (AstroPaul, US, 2015-10-25, v3.0.2) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** « You start the app for the first time and it takes you straight into a game. » (NeilC32, GB, 2010-07-19) ; « having it random, you haveto change your strategy every time » (MackClews, CA, 2010-06-23) ; « keep resetting the app until you get several countries on the same continent » (« why do i need a nickname?... », CA, 2008-10-20) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Demande toujours non satisfaite en 2025 : « the only feature I'm missing is the ability to manually choose provinces in the setup » (Sticks o'Fish, US, 2025-11-01, v3.24) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Aucun pays vide au départ : « There are no empty territories, they are occupied, just with no extra armies » (Adamwow, GB, 2011-07-04) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** Début de partie à 5 joueurs observé : pays 8/7/7/14/6 (total 42), armées 24/24/26/22/25 (total 121), cartes 0/1/1/1/0 — [capture App Store iPad 1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/03/25/fd/0325fd5a-bc4f-8e7b-678c-8663add0e246/pr_source.png/1600x1200bb.png)
- **(c)** Moteur Lux : deux modes de départ (pays choisis ou « pick the initial countries randomly ») ; chaque pays reçoit automatiquement 1 armée, puis les armées de départ restantes sont placées (« Currently Lux is set to have players place 4 armies at a time ») — [SDK Sillysoft, LuxAgent.java](https://sillysoft.net/sdk/)
- **(c)** Lux Delux : choix « random or selected or using the map's built-in starting scenario » — [wiki Lux, Main Game Window](https://sillysoft.net/wiki/?Main%20Game%20Window)

### Inferences
- 42 pays ÷ 5 joueurs ⇒ répartition initiale de 8 ou 9 pays par joueur (8+8+8+9+9), cohérente avec les 8 pays du bleu sur la capture iPad 1.
- Les totaux d'armées de la capture iPad 1 (22 à 26 par joueur au 1er tour) sont de l'ordre des 25 armées par joueur d'une partie de Risk à 5, mais la capture est prise après quelques actions : **la valeur de départ exacte ne peut pas être déduite**.
- Sur la capture iPad 1, bleu (1re ligne) a 0 carte, rouge/vert/orange 1 carte, noir (dernière ligne) 0 carte : compatible avec un ordre de jeu = ordre du tableau, bleu en premier. Indice faible, non concluant.

### Gaps
- Nombre d'armées initiales par joueur et leur répartition (égale ? aléatoire ?) : (d).
- Qui joue en premier (toujours l'humain ? aléatoire ?) : (d).
- Répartition exacte des pays (8/8/8/9/9 ?) et qui reçoit les pays supplémentaires : (d).

---

## 4. Phases du tour et formule de renfort

### Takeaway
Un tour comporte, dans l'ordre : (encaissement éventuel de cartes) → placement des renforts → attaques illimitées → fortification → fin de tour (carte gagnée si au moins une conquête). Renforts = **pays possédés ÷ 3, arrondi à l'entier inférieur, minimum 3**, + bonus des continents entièrement possédés au début du tour, + valeur des séries de cartes encaissées.

### Cited Findings
- **(a)** « On each turn you place armies, can make unlimited attacks, and then fortify your armies around 1 move each. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** « You get (# of countries owned / 3) armies per turn, with a minimum of 3. » ; « If you hold an entire bonus region at the start of your turn, you get extra armies from it. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** « You can cash-in a set of cards […] at the start of your turn for extra armies. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** Tableau des joueurs : drapeau = nb de pays, soldat = nb d'armées, carte = nb de cartes, graphique = « income (the number of armies earned at the start of their turn. effected by # of countries and continents owned) » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** Vérification de l'arrondi sur captures : orange 14 pays → revenu 4 ; joueurs à 6, 7, 8 pays → revenu 3 (minimum) — [capture iPad 1](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/03/25/fd/0325fd5a-bc4f-8e7b-678c-8663add0e246/pr_source.png/1600x1200bb.png) ; 42 pays → revenu 38 — [capture iPad 5](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/b1/02/1b/b1021b8d-7682-e9fa-2400-15d36dcf0d3a/pr_source.png/1600x1200bb.png)
- **(a)** Boutons visibles en jeu (v3) : Menu, 1-Attack / All-Attack, Manual / Auto, Bonus, Fortify, End ; en mode cartes : Later, Cash ; indicateur « Blue's turn » ; compteur « 3 Armies To Place » — [capture iPad 2](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/3e/fd/8e/3efd8e33-07a3-d475-bfc0-77ad4a4b2881/pr_source.png/1600x1200bb.png) ; [capture iPhone 2 (All-Attack)](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/0b/c4/86/0bc486b3-7554-e28f-f288-f35e70659de6/pr_source.png/1600x1200bb.png) ; [capture iPad 3](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/d6/4e/a8/d64ea87f-ab13-f644-dbea-55d675c1bdb9/pr_source.png/1600x1200bb.png) ; [capture iPhone 4](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/f0/9a/06/f09a0673-59cc-6b16-af02-f3d95f7e3b08/pr_source.png/1600x1200bb.png)
- **(a)** Placement : « you can either tap to place 1 army at a time, or tap-and-hold to place batches of armies » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(c)** Ordre des phases dans le moteur Lux : cardsPhase → placeArmies → attackPhase → (moveArmiesIn à chaque conquête) → fortifyPhase — [SDK Sillysoft, LuxAgent.java](https://sillysoft.net/sdk/)
- **(c)** Lux Delux possède une option « to not give out continent bonuses on the first turn » — [journal des versions Lux Delux](https://sillysoft.net/lux/changelog.php)

### Inferences
- 38 = ⌊42 ÷ 3⌋ (14) + 5 + 5 + 7 + 3 + 2 + 2 (24) : confirme à la fois la formule, l'arrondi inférieur et les six bonus de base.
- La formule est identique à celle du Risk classique ; la différence vient des bonus de continent qui croissent (section 2).

### Gaps
- Les bonus de continent sont-ils versés dès le tout premier tour dans Lux Touch ? (option existante dans Lux Delux ; réglage de Touch inconnu) (d).
- Existence d'une limite de temps par tour : rien ne l'indique pour Lux Touch (d).

---

## 5. Cartes : gain, séries, valeurs, encaissement forcé, élimination, bonus pays

### Takeaway
On gagne 1 carte en fin de tour si l'on a conquis au moins 1 pays ennemi ; une série = 3 cartes identiques ou 1 de chaque type (jokers « Wild Card » inclus) ; l'encaissement se fait au début du tour, est **obligatoire à 5 cartes ou plus**, et sa valeur **augmente à chaque encaissement** (premières séries ≈ 4 armées, puis progression par +5 en haut de l'échelle : 50, 55, 60, 65, 70, 75…). Éliminer un joueur donne ses cartes. La séquence « 5, 5, 5 » n'est **pas** celle de Lux Touch.

### Cited Findings
- **(a)** « You get a card at the end of your turn as long as you take over at least one enemy country. » ; « Eliminate other players from the game to get their cards. » ; « You can cash-in a set of cards (3 of a kind, or 1 of each kind) at the start of your turn for extra armies. » ; « Cards become more powerful the longer you hold on to them. » ; « You have to cash cards when you have 5 or more. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** « take over 1 enemy country per turn for a card » ; « fully eliminate an enemy and you get their cards » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(a)** Message en jeu : « Card cash is worth 60 armies (then 65,70,75) » — [capture iPad 3](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/d6/4e/a8/d64ea87f-ab13-f644-dbea-55d675c1bdb9/pr_source.png/1600x1200bb.png) ; « Card cash is worth 50 armies (then 55,60,65) » — [capture iPhone 3](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/14/a9/af/14a9afa9-aaea-f16c-c928-4c007f4a9169/pr_source.png/1600x1200bb.png)
- **(a)** Types de cartes visibles en v3 : cavalier (Ukraine, Afghanistan, Japan), canon (Indonesia), et « Wild Card » montrant cavalier + canon + fantassin ; boutons « Cash » et « Later » (report possible de l'encaissement) — mêmes captures : [iPad 3](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/d6/4e/a8/d64ea87f-ab13-f644-dbea-55d675c1bdb9/pr_source.png/1600x1200bb.png) ; [iPhone 3](https://is1-ssl.mzstatic.com/image/thumb/Purple71/v4/14/a9/af/14a9afa9-aaea-f16c-c928-4c007f4a9169/pr_source.png/1600x1200bb.png)
- **(a)** v3.0.2 (2013-12-16) : le mode Cartes affiche désormais les prochaines valeurs d'encaissement ; v3.0.1 (2013-11-12) : le joueur humain peut échanger plusieurs séries de cartes — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(b)** Début de l'échelle : « If you are the first to convert cards, then you will only get 4 or something. Better to wait if you can. » (derekkraan, CA, 2008-10-19) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Progression : « the cards keep adding +5 to the last bonus » (Anon9966, AU, 2013-03-03, v2.4) ; « Those of us that know our risk will recognize the card cashin ascending value from later versions of the board game » (Josemorero, GB, 2009-09-25) ; « The growing value of card cashes should be a toggle feature » (Souper Power, CA, 2008-10-19) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Ordres de grandeur en fin de partie : « 85 armies in 1 turn? » (Vader266, GB, 2008-10-15) ; « my opponent whips out 150 troops out of nowhere » (Haggishunt56, GB, 2011-08-21) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Les cartes ne nécessitent pas de posséder le pays illustré : « Some of cards aren't even on my territory, but I can still spend them » (TheGrey, GB, 2010-03-28) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Lisibilité : « there is no way to see which cards I currently have in my hand » (oldmankit, GB, 2015-11-09, v3.0.2 — contredit par les captures v3 qui montrent les cartes au moment de l'encaissement) ; « No explanation of wild cards » (plainjosh, US, 2017-05-15) ; « a better explanation of how the 'cards' in the game actually work » (Picasso's left ear, GB, 2025-09-14) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** Lux Delux : « If you own the country that is on a card, you get a bonus of two armies on that territory. » ; « Once you have five cards, you must turn them in » ; « When you take out another player, you get their cards. » ; « Most online games are set so that if you take out another player and the sum of your cards and theirs equals five or more, you must turn them in until you are under five. » — [wiki Lux, How the Cards Work](https://sillysoft.net/wiki/?How%20the%20Cards%20Work)
- **(c)** Symboles Lux Delux (bureau) : « A tank, a plane, and a soldier » ; dans le moteur : symboles 0, 1, 2 et joker = 3 (« Wildcard's symbol is 3, it can be anything ») — [wiki Lux, How the Cards Work](https://sillysoft.net/wiki/?How%20the%20Cards%20Work) ; [SDK Sillysoft, Card.java](https://sillysoft.net/sdk/)
- **(c)** Moteur Lux : si un agent sort de sa phase cartes avec trop de cartes, « enough sets will be automatically cashed to bring you to under five cards » ; options moteur `useCards()`, `transferCards()` (transfert à l'élimination), `immediateCash()` (encaissement immédiat après élimination à 5+ cartes), `getCardProgression()` — [SDK Sillysoft, LuxAgent.java et Board.java](https://sillysoft.net/sdk/)
- **(c)** Séquences disponibles dans Lux Delux / DLX : « 4-6-8-10-15 », « 5-10-15 », « 3,6,9... », réglages « exponential », et 5-5-5 (« best at 5-5-5 ») — [wiki Lux History](https://sillysoft.net/wiki/?Lux%20History) ; [journal des versions Lux Delux](https://sillysoft.net/lux/changelog.php) ; [wiki AgentProfiles](https://sillysoft.net/wiki/?AgentProfiles) ; un joueur décrit pour DLX « cash sequence (4, 6, 8... 5, 10, 15...) » (Ccufgu, CA, 2017-07-22) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** La valeur d'encaissement est commune à tous les joueurs (« if you hold off and someone else […] cashes their cards, you may have the benefit of the higher value ») — [wiki Lux, Strategy](https://sillysoft.net/wiki/?Strategy)
- **(Base Risk)** Séries valides : trois symboles identiques, un de chaque, ou deux cartes + joker ; 42 cartes territoire + 2 jokers ; 1 carte max par tour si conquête ; après élimination, à 6 cartes ou plus on doit échanger jusqu'à moins de 5 — [Wikipedia, Risk (game)](https://en.wikipedia.org/wiki/Risk_(game))

### Inferences
- La séquence de Lux Touch est **croissante et globale** (chaque encaissement, humain ou IA, fait monter la valeur suivante), commence vers 4 et progresse par pas de 5 dans la partie haute (…50, 55, 60, 65, 70, 75). C'est compatible avec le réglage Lux « 4, 6, 8, 10, 15, 20, 25… » mais aussi avec l'échelle du Risk classique ; les premiers paliers exacts (présence ou non d'un palier à 12) ne sont pas vérifiés.
- La séquence « 5, 5, 5… » évoquée dans l'énoncé est une option de Lux Delux, incompatible avec le message officiel « 60 armies (then 65,70,75) » de Lux Touch.
- Le bouton « Later » montre que l'encaissement est facultatif tant qu'on a moins de 5 cartes ; la mention de v3.0.1 implique qu'on peut enchaîner plusieurs séries dans le même tour (utile après avoir hérité des cartes d'un joueur éliminé).
- Les plaintes du type « l'IA encaisse toutes les 3 cartes alors que j'attends 5 » (Nani385, 2014 ; Darthvalor, 2015) reflètent le hasard des séries, pas une règle différente pour l'IA : aucune source ne documente d'avantage accordé à l'IA.

### Gaps
- Séquence exacte palier par palier dans Lux Touch (d).
- Bonus de +2 armées sur le pays figurant sur une carte encaissée : documenté pour Lux Delux (c), non confirmé pour Lux Touch.
- Encaissement immédiat en plein tour après une élimination (et la « téléportation » d'armées qui en découle dans Lux Delux) : non confirmé pour Lux Touch (d). L'écran de victoire iPad 5 montre un joueur avec 6 cartes, mais en fin de partie.
- Composition du paquet (nombre de cartes, nombre de jokers) dans Lux Touch (d).

---

## 6. Combat : résolution, « all-attack », armées à déplacer après conquête

### Takeaway
Les combats sont résolus par des jets de dés invisibles de type Risk (attaquant jusqu'à 3 dés, défenseur jusqu'à 2 selon un joueur ; non détaillé officiellement pour Lux Touch). Un tap = 1 round d'attaque en mode « 1-Attack », ou combat jusqu'à la mort d'un camp en mode « All-Attack » ; après conquête, on répartit les armées manuellement (« Manual ») ou tout avance automatiquement (« Auto »).

### Cited Findings
- **(a)** « The '1-attack' setting performs 1 attack per tap. The 'All-attack' setting does a full attack until one side loses, per tap » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** « The 'Manual' move-in setting lets you control how many armies you move into a defeated territory. The 'Auto' move-in setting will automatically move all your armies into territories that you take over. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** « Hold a finger to make continuous attacks. » ; « Hold a finger to divide large armies quickly. » ; « Attack with 3 or more armies for best odds. » — [page officielle Lux Touch](https://sillysoft.net/lux/touch/)
- **(a)** Message en mode manuel : « Tap or hold to divide your armies between the two countries » avec compteur « 3 Armies To Place » — [capture iPhone 4](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/f0/9a/06/f09a0673-59cc-6b16-af02-f3d95f7e3b08/pr_source.png/1600x1200bb.png)
- **(a)** v3.0 (2013-11-01) a ajouté les boutons rapides Auto-Advance et All-Attack — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(b)** « Chance of victories/defeat the same as real dice with the 3/2 dice for attack/defend of countries. » (Paraquat59, AU, 2014-04-25, v3.0.2) ; « Rules are risk's rules, math is based on random dice rolls. » (Kosikutioner, CA, 2008-11-05) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Dés non affichés : « Can't see the dice rolls » (smirecki, CA, 2009-12-25) ; « Risk on my touch without rolling the dice and counting the armies » (rwhitley, CA, 2008-10-24) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Soupçons récurrents de dés truqués (non prouvés) : « I consistently see attacking armies with a 2:3 ratio winning battles […] The developer claims that the algorithms are fair. » (00cho, US, 2021-12-13) ; « There's no way 30 against five loses » (Reyman440@, US, 2025-09-28) ; à l'inverse « it works both ways » (TilleyNJ, US, 2017-04-03) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Vitesse : les grosses attaques de l'IA sont très lentes alors que celles du joueur sont quasi instantanées (Gavan W., US, 2020-04-19 ; Anon9966, AU, 2013-03-03) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** Moteur Lux : l'attaquant choisit 1, 2 ou 3 dés et doit avoir au moins (dés + 1) armées dans le pays d'origine ; attaque depuis un pays possédant au moins 2 armées ; `attackTillDead` = répéter jusqu'à ce qu'un camp soit anéanti ; un pays garde toujours au moins 1 armée — [SDK Sillysoft, LuxAgent.java et Board.java](https://sillysoft.net/sdk/)
- **(c)** Après conquête : « The minimum acceptable answer is the number of attack dice you used. The maximum acceptable value is the number of armies left in the attacking country minus one. » — [SDK Sillysoft, LuxAgent.java](https://sillysoft.net/sdk/)
- **(c)** Lux Delux : « Improved pseudorandom number generator for dice rolls » — [journal des versions Lux Delux](https://sillysoft.net/lux/changelog.php)
- **(Base Risk)** Attaquant jusqu'à 3 dés, défenseur 2 (ou 3 selon l'édition), « Defenders always win ties » — [Wikipedia, Risk (game)](https://en.wikipedia.org/wiki/Risk_(game))
- **(a, pour DLX uniquement)** Lux DLX 3.6 ajoute des « Dice Settings » ; rien d'équivalent dans la fiche de Lux Touch — [fiche App Store Lux DLX 3](https://apps.apple.com/us/app/lux-dlx-2/id299813413)

### Inferences
- Lux Touch applique très probablement la mécanique de dés du moteur Lux (3 dés max en attaque, 2 en défense, égalité au défenseur), mais **ni les 2 dés du défenseur ni la règle d'égalité ne sont écrits dans une source officielle Lux Touch ou dans le SDK consulté** : ils reposent sur un avis de joueur (b) et sur la base Risk.
- Le minimum à faire entrer après conquête (= nombre de dés utilisés) est une règle du moteur (c) ; en mode « Auto » toutes les armées sauf 1 avancent.
- Contrairement au Risk physique, le joueur ne choisit pas explicitement le nombre de dés : le jeu prend le maximum possible (déduit de l'absence de tout réglage de dés dans l'interface de Touch).

### Gaps
- Nombre de dés du défenseur et règle d'égalité dans Lux Touch : pas de source officielle (c/b seulement).
- Minimum exact d'armées à avancer en mode « Manual » dans Lux Touch (d).
- Aucune preuve vérifiable d'un biais des dés ; aucune publication de l'algorithme par le développeur n'a été trouvée.
- Le fil TouchArcade mentionnant un adversaire recevant « 125 extra units » n'a pas pu être ouvert (extrait de moteur de recherche seulement) (d).

---

## 7. Fortification / déplacements de fin de tour

### Takeaway
En fin de tour, le joueur peut effectuer **autant de déplacements qu'il veut, mais chaque armée ne peut avancer que d'un seul pays (vers un pays adjacent lui appartenant)** ; chaque pays doit conserver au moins 1 armée. C'est plus souple que la règle classique (un seul transfert), mais sans déplacement en chaîne.

### Cited Findings
- **(a)** « …and then fortify your armies around 1 move each. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(b)** « When fortifying troops you can only move the troops one tile. » (Gregory Sandhills, CA, 2014-07-20, v3.0.2) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** « don't like the fact that you can fortify at the end of your turn as much as you want » (3lywa, CA, 2009-01-25) ; « I really appreciate the fortification system » (Onioneyes, US, 2014-10-28) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** On peut conquérir puis se retirer à la fortification : « make sure you take over one territory, even if you immediately retreat from there in the fortify stage of the turn » (derekkraan, CA, 2008-10-19) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** Moteur Lux : « fortifying your armies into neighboring countries » ; au début de la phase, les `moveableArmies` de chaque pays valent son nombre d'armées et diminuent à chaque sortie (une armée arrivée par fortification n'est pas re-déplaçable) ; « countries must always keep 1 army on them » — [SDK Sillysoft, LuxAgent.java et Board.java](https://sillysoft.net/sdk/)
- **(a)** Bouton « Fortify » puis « End » dans la barre latérale — [capture iPad 2](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/3e/fd/8e/3efd8e33-07a3-d475-bfc0-77ad4a4b2881/pr_source.png/1600x1200bb.png)
- **(a)** Bogue historique : v3.0.2 (2013-12-16) corrige un blocage en fortification (« fortify stall bug ») — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(b)** Bogues de déplacement encore signalés : « Sometimes armies disappear when moving country to country » (Billybeeyapper, CA, 2026-08-20, v3.24) ; compteurs doublés ou négatifs avec de grosses armées (00cho, US, 2021-12-13) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Pas d'annulation : demande d'« an undo option on fortify » (2pages, GB, 2011-05-03 ; Dr Needles, GB, 2008-10-24) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(Base Risk)** En fin de tour, déplacement d'armées d'un territoire vers un autre territoire connecté — [Wikipedia, Risk (game)](https://en.wikipedia.org/wiki/Risk_(game))

### Inferences
- Règle fixe dans Lux Touch = « chaque armée, 1 déplacement vers un voisin » ; aucune option de fortification n'est exposée dans l'interface de Touch.
- Les armées ayant combattu ou avancé pendant la phase d'attaque peuvent encore être fortifiées (le compteur du moteur est réinitialisé au début de la phase de fortification) — règle moteur (c), cohérente avec l'avis de derekkraan.

### Gaps
- Aucune confirmation officielle spécifique à Lux Touch du détail « une armée arrivée par fortification ne peut pas repartir » (c).
- La plainte de 2008 selon laquelle l'IA pourrait « attack fortify and then attack again » (Slick198369, CA, 2008-11-05) n'est corroborée par aucune autre source.

---

## 8. Victoire / défaite, scores, statistiques

### Takeaway
La seule condition de victoire est la conquête de toute la carte (élimination totale) ; un joueur sans pays est éliminé et ses cartes vont à son éliminateur. Lux Touch n'a ni score, ni statistiques, ni classement, ni succès, ni Game Center : l'écran de fin propose seulement « Play Again », « Get Lux DLX » et « Newsletter ». Si l'humain est éliminé, la partie continue entre IA ; depuis la v3.0, un menu permet de recommencer.

### Cited Findings
- **(a)** « The goal of the game is to take over the entire map. » — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(a)** Écran de fin : « Yay! You Won The Game! » + boutons « Play Again », « Get Lux DLX », « Newsletter » ; aucun score affiché — [capture iPad 5](https://is1-ssl.mzstatic.com/image/thumb/Purple62/v4/b1/02/1b/b1021b8d-7682-e9fa-2400-15d36dcf0d3a/pr_source.png/1600x1200bb.png)
- **(b)** Avant la v3.0 : « when you are the first player eliminated, the game carries on and there is no way to reset it, so you are stuck watching the AI Players battle it out » (NCK1978, CA, 2011-01-16, v2.1) ; « if the human gets eliminated the game can stalemate with a non-ending battle » (BoredinOttawa, CA, 2008-11-29) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** v2.3 (2011-10-20) : correctif pour la reprise d'une partie après l'élimination du joueur humain ; v3.0 (2013-11-01) : ajout d'un menu Restart — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(b)** Sauvegarde : absente en 1.x (« the game in progress cannot be saved », bc.mac, CA, 2008-10-12 ; partie perdue à chaque appel) ; présente ensuite (« This version saves the game when you quit », Langelil, CA, 2011-06-30, v2.1 ; « THIS HAS BEEN FIXED: Doesn't save where you left off », AstroPaul, US, 2015-10-25) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Statistiques demandées, donc absentes : « Endgame statistics » (Theperfectjez, AU, 2009-02-03) ; « maybe a leaderboard » (Bex2nite, GB, 2008-12-13) ; écran promotionnel à chaque fin de partie (« the silly nag-screen every time you finish a game », oldmankit, GB, 2015-11-09) — [flux d'avis AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** `isGameCenterEnabled: false` — [API iTunes Lookup](https://itunes.apple.com/lookup?id=292538570&country=us)
- **(a, pour DLX uniquement)** Lux DLX 3.6 : rangs gagnés par les victoires, suivi du taux de victoire, graphique de fin de partie — [fiche App Store Lux DLX 3](https://apps.apple.com/us/app/lux-dlx-2/id299813413)
- **(c)** Lux Delux en ligne : système de classement hebdomadaire au « Raw » et médailles ; victoire = éliminer tous les autres joueurs — [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game))
- **(b)** Durée typique d'une partie : « plays in 20 minutes » (Muffinchild, GB, 2010-04-02) ; « the fun filled 9 minutes it takes to conquer the world » (Greebstar, US, 2014-02-26) ; « 10-15 minutes » (AMJPRO, CA, 2008-12-20) — [flux d'avis GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)

### Inferences
- Pas de missions secrètes, pas de capitales, pas de victoire par objectifs : uniquement la domination totale.
- Aucune série de victoires, aucun rang ni succès dans Lux Touch ; ces éléments n'existent que dans DLX (3.6) et dans Lux Delux en ligne.

### Gaps
- Comportement exact en v3.24 quand l'humain est éliminé (écran de défaite ? partie IA accélérée ? proposition de rejouer ?) : non documenté (d).
- La sauvegarde automatique à la sortie est attestée par des avis (b), pas par une note de version explicite.

---

## 9. IA : quels bots, difficulté, comportement décrit par les joueurs

### Takeaway
Lux Touch n'a **aucun réglage de difficulté** : quatre IA « faciles » à personnalité fixe par couleur, que les joueurs jugent prévisibles (on gagne presque toujours une fois les schémas compris). Les noms des bots utilisés ne sont pas publiés ; d'après les comportements décrits, rouge correspond au bot « Communist » et jaune/orange à « Angry » de Lux Delux (inférence), vert à un bot orienté continents, noir à un bot accumulateur. Les IA dures (Reaper, BotOfDoom…) sont réservées à DLX.

### Cited Findings
- **(a)** « fun varied computer AIs » ; DLX = « more AIs » ; « Harder computer AI » dans DLX — [fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570) ; [page officielle Lux Touch](https://sillysoft.net/lux/touch/)
- **(b)** Pas de difficulté réglable : « their are no options to change the computer's difficulty » (Gregory Sandhills, CA, 2014-07-20) ; « maybe I should check to see if I missed a difficulty setting. Nope » (Badideas, US, 2014-03-07) ; « That you can choose the com difficulty » demandé (rjr disvr. e, CA, 2023-07-25) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Rouge : « Red will always distribute their troops evenly, and they typically take only a single territory per turn » (derekkraan, CA, 2008-10-19) ; « Red kills one country per turn, uses same number of armies on each country […] When he thinks he can win, he attacks everyone » ([M]yth, CA, 2009-01-04) ; « Red will always distribute armies equally […] will only take one country at a time until a given point and then goes chaotic » (Transitech, US, 2017-07-25) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Jaune/orange : « yellow is super agressive » (rwhitley, CA, 2008-10-24) ; « Yellow expands untill he cannot attack » ([M]yth, 2009) ; « Yellow always attacks the guy with less troops » (Not impressed 1313, CA, 2013-05-02) ; « Orange: Extremely aggressive at all points of the game » (Lyuldo Drop, US, 2019-05-06) ; « The yellow is a maniac » (Andras, GB, 2026-02-09) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Vert : « Green is a protective fighter, likes to keep continents » ([M]yth, 2009) ; « Green, is most cases, will only start attacking another region once it has conquered the current region » (Chris•, GB, 2016-02-23) ; « Watch out for green, he has the best strategy techniques » (PainKiller, US, 2016-10-01) ; après la v3.1 : « Green no longer tries to take a continent » (lfnoize, US, 2016-10-03), « the green player AI is daft » (BzzBob, AU, 2018-02-03) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Noir : « Black gets all his armies in one country and when he's ready he attack » ([M]yth, 2009) ; « Black shuts down and basically stops playing when it loses a fair amount of territory » (crtoph, CA, 2009-02-19) ; « Black sometimes goes hog wild but most it just stays and builds in one country » (Transitech, 2017) ; « Black: Aggressive early, but becomes passive really quick » (Lyuldo Drop, 2019) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Prévisibilité et facilité : « Win 199/200 games easily » (Kia 2011, CA, 2013-12-13) ; « I used to win about 95% of the time » (lyghterfluid, US, 2014-10-03) ; « it's really easy to win if you know what they are going to do and how they'll do it » (ryansssacc, US, 2020-08-26) ; « Win 199/200 » date de la v3.0.1 ; faiblesses : les IA « don't finish off players to gain their cards » (All2easy, GB, 2009-02-22) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux GB](https://itunes.apple.com/gb/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Impression d'acharnement contre l'humain (minoritaire) : « Why do black and yellow always attack me specifically? » (Nani385, US, 2014-07-26) ; « Green maybe the best strategist & persistently evil to focus most on human player » (maddog,,, US, 2016-10-28) ; à l'inverse un joueur piège les IA entre elles en Afrique (magnusviri, US, 2019-01-19) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Presse : « The AI repeats the same mistake », jeu facile une fois le comportement appris — [iPhone Life, 2008-10-25](https://iphonelife.com/blog/2427/remember-game-risk-now-play-it-iphone-lux-touch) ; la version Deluxe promet « a harder AI opponent » — [Pocket Gamer, Spanner Spencer, 2008-10-14](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation)
- **(c)** Bots Lux Delux (descriptions officielles/communautaires) : **Communist** — « determines which country has the least amount, and adds one to that one. […] Attacks to take one country, fortifies based on a communist temperment, then ends its turn » ; **Angry** — « Just attacks as much as possible » ; **Pixie** — « primarily motivated by taking and holding continents » ; **Shaft** — « hoards its armies until it is the strongest player on the board, then tries to take over the board in one turn » ; **Cluster** — défend et étend un amas de pays ; **Stinky** — « attacks totally randomly » ; plus Yakool, Boscoe, Quo, EvilPixie, Killbot, Bort, Reaper, Nefarious, BotOfDoom… — [wiki Lux, AgentProfiles](https://sillysoft.net/wiki/?AgentProfiles)
- **(c)** Code source du bot Communist : place les armées une à une sur son pays le plus faible, attaque le voisin ennemi le plus faible « till dead, with max dice », égalise ses armées en fortification, et passe à l'offensive générale quand il ne reste que des communistes ; bot Angry : place tout là où il peut attaquer le plus de pays et n'encaisse ses cartes que lorsque le jeu l'y force — [SDK Sillysoft, Communist.java et Angry.java](https://sillysoft.net/sdk/)
- **(c)** Lux Delux : « Easy ones are at the top, and harder ones are at the bottom » dans le menu des IA ; « About half of these bots were programmed by members of the community » — [wiki Lux, Main Game Window](https://sillysoft.net/wiki/?Main%20Game%20Window) ; [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game))
- **(a, pour DLX)** DLX : « Reaper, an Extra Hard AI », « BotOfDoom, a second Extra Hard AI », option « AI Teaming » — [fiche App Store Lux DLX 3](https://apps.apple.com/us/app/lux-dlx-2/id299813413)

### Inferences
- **Correspondance probable (non confirmée par le développeur)** : rouge = Communist (répartition égalitaire, 1 conquête par tour — description et code quasi identiques aux observations des joueurs) ; jaune/orange = Angry ; vert = bot de la famille Pixie (continents) jusqu'à la v3.0.x ; noir = bot accumulateur de type Shaft ou Cluster. Les joueurs classent la difficulté : vert > jaune > noir > rouge (MackClews, 2010).
- Le comportement du vert semble avoir changé avec la v3.1 (2016), et un joueur note en 2017 que « Black is more aggressive » : les IA ont pu être retouchées entre v3.0.2 et v3.12, sans mention dans les notes de version.
- Pas de « coalition contre l'humain » programmée dans Lux Touch : l'option « AI Teaming » et les bots qui s'allient contre les humains (Nefarious, BotOfDoom, Reaper) relèvent de Lux Delux/DLX.

### Gaps
- Noms exacts des quatre bots de Lux Touch : aucune source officielle accessible (les fils de forum où « dustin » aurait pu répondre étaient inaccessibles) (d).
- Aucune confirmation ni infirmation officielle d'un avantage de dés ou d'armées accordé aux IA ; un avis rapporte seulement que le développeur affirme que les algorithmes sont équitables.

---

## 10. Options/réglages dans Lux Touch, différences avec Risk et avec Lux Delux, historique des versions

### Takeaway
Lux Touch est volontairement dépouillé : aucun réglage de règles, seulement deux bascules de confort (1-Attack/All-Attack, Manual/Auto), un écran Bonus, un écran Cartes et un menu (recommencer) ; pas d'option son. Toutes les options de règles (cartes, hausse des continents, nombre de joueurs, IA, cartes, dés, hot-seat) appartiennent à Lux DLX / Lux Delux. L'app, gratuite et sans publicité ni achat intégré, n'a pas été mise à jour depuis le 2019-01-23 et des plantages au lancement sont signalés sur les iOS récents (2025).

### Cited Findings
- **(a)** « Lux Touch is fully FREE! No in-app purchases! » ; DLX = « more AIs, more maps, more settings, more hot graphics, more human players » ; « Lux Touch is a mobile version of Lux Delux » ; « Lux is NOT associated with the board game RISK » — [fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(a)** Fiche technique : version 3.24 du 2019-01-23, première sortie 2008-10-07, gratuit, 55,1 Mo, iOS 11.0+, anglais uniquement, 9+, 871 notes (moyenne 4,2) sur la boutique US — [API iTunes Lookup](https://itunes.apple.com/lookup?id=292538570&country=us) ; [fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(a)** DLX apporte « Saves your game, Harder computer AI, Hot-seat multi-player, More settings and options, Tons of different maps » — [page officielle Lux Touch](https://sillysoft.net/lux/touch/)
- **(a)** Deux bascules rapides documentées (1-attack/All-attack ; Manual/Auto) — [instructions officielles Lux Touch](https://sillysoft.net/lux/touch/instructions.php)
- **(b)** Aucune option de son, de 2013 à 2024 : « All that is missing from the menu is a way to mute the sound » (Tikibird97, US, 2013-12-20) ; « Still no sound options?!? » (DragonLost, US, 2024-03-16) ; préférences des bascules non mémorisées (« It still doesn't remember preference between restarts », Boyto, AU, 2013-12-27) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json) ; [flux AU](https://itunes.apple.com/au/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(b)** Version 1.x : ni menu, ni instructions, ni sauvegarde (« No options, no tutorial », Sandwichboy, CA, 2008-12-04 ; « no title screen, no instructions, no menu », Urby, CA, 2009-02-17) — [flux d'avis CA](https://itunes.apple.com/ca/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(a)** Historique des versions : 1.0 (2008-10-07) ; 1.0.1 (2008-10-19) ; 2.0 (2010-06-22, correctif tutoriel) ; 2.1 (2010-07-27, plein écran iPad) ; 2.2 (2011-08-29) ; 2.3 (2011-10-20) ; 2.4 (2012-02-26) ; 3.0 (2013-11-01, réécriture majeure : menu Restart, animations plus rapides, boutons Auto-Advance et All-Attack, carte retina) ; 3.0.1 (2013-11-12, échanges de plusieurs séries de cartes) ; 3.0.2 (2013-12-16, correctif fortification, valeurs de cartes à venir) ; 3.1 (2016-09-30) ; 3.11 (2016-10-04) ; 3.12 (2017-03-31) ; 3.13 (2017-11-14) ; 3.20 (2018-12-15) ; 3.22 (2019-01-16) ; 3.23 (2019-01-18) ; 3.24 (2019-01-23, stabilité et affichage) — [historique des versions, fiche App Store US](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(b)** État en 2025-2026 : « it quit working on my SE3 when I updated to iOS 18.5 » (sarighter, US, 2025-05-22) ; « with the latest Apple update it crashes all the time. With no updates in the past 6 years… » (ElvisOut, US, 2025-12-07) ; « It freezes upon opening » (Michael Noah Music, US, 2025-12-06) ; mais des avis positifs de joueurs actifs subsistent en 2026 (cuevaxcris, US, 2026-04-07 ; Average-Adam, US, 2026-11-21) — [flux d'avis US](https://itunes.apple.com/us/rss/customerreviews/page=1/id=292538570/sortby=mostrecent/json)
- **(c)** Options de Lux Delux absentes de Touch : 2 à 6 joueurs, choix des IA, « Game Options tab lets you change card and continent settings », pays choisis ou aléatoires, scénarios de départ, cartes activables/désactivables, transfert des cartes, encaissement immédiat, séquences de cartes multiples, pourcentage de hausse des continents, minuterie de tour, multijoueur en ligne, 900+ cartes, éditeur de cartes — [wiki Lux Guide](https://sillysoft.net/wiki/?Lux%20Guide) ; [wiki Main Game Window](https://sillysoft.net/wiki/?Main%20Game%20Window) ; [SDK Sillysoft, Board.java](https://sillysoft.net/sdk/) ; [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game))
- **(a, pour DLX)** Lux DLX 3 (payant, 6,99 $ US, v3.6) : 100+ cartes, hot-seat, Dice Settings, AI Teaming, langue, volume, option Biohazard, IA Reaper et BotOfDoom, rangs et taux de victoire — [fiche App Store Lux DLX 3](https://apps.apple.com/us/app/lux-dlx-2/id299813413)
- **(b)** Réception : « Voted #1 iPhone game by Wired.com readers » (février 2009) — [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game)), citant [Wired, 2009-02](https://www.wired.com/2009/02/readers-picks-o/) ; revendiqué aussi sur la [fiche App Store](https://apps.apple.com/us/app/lux-touch/id292538570)
- **(Conflit de dates)** Wikipedia situe les débuts iPhone de Lux en « December 2008 » (Lux Touch et Lux DLX) — [Wikipedia, Lux (video game)](https://en.wikipedia.org/wiki/Lux_(video_game)) ; contredit par l'API Apple (sortie de Lux Touch le 2008-10-07) — [API iTunes Lookup](https://itunes.apple.com/lookup?id=292538570&country=us) — et par l'article de [Pocket Gamer du 2008-10-14](https://www.pocketgamer.com/lux-touch/lux-touch-risks-an-iphone-adaptation)

### Inferences
- **Différences Lux Touch vs Risk classique (synthèse)** : (1) mise en place automatique et aléatoire, sans draft ni placement initial ; (2) dés invisibles, résolution instantanée, mode « jusqu'à la mort » ; (3) bonus de continent croissants au fil de la partie ; (4) fortification multiple mais limitée à 1 pays par armée ; (5) pas de missions ; (6) solo uniquement contre 4 IA à personnalité fixe ; (7) parties de 10 à 20 minutes. Identiques ou quasi : 42 pays, 6 continents, bonus de base 5/5/7/3/2/2, renforts pays÷3 (min 3), 1 carte par tour avec conquête, séries de 3, jokers, valeur de série croissante, encaissement forcé à 5 cartes, cartes de l'éliminé au vainqueur.
- **Différences Lux Touch vs Lux Delux** : Touch = un préréglage figé du moteur Lux (1 carte, 5 joueurs, IA faciles, cartes croissantes, hausse des continents activée, pays aléatoires) sans aucune des options de Delux/DLX.
- L'app étant inchangée depuis 2019, les règles décrites ici (v3.24) sont stables depuis la v3.0.2 pour les mécaniques ; seuls l'affichage et la stabilité ont évolué. Règles ou comportements ayant changé selon les versions : sauvegarde (absente en 1.x), menu/recommencer et bascules rapides (v3.0), échange de plusieurs séries (v3.0.1), affichage des valeurs futures (v3.0.2), habillage de la carte (v3.0), comportement de certaines IA (vers v3.1–v3.12, d'après des avis).

### Gaps
- Contenu exact du bouton « Menu » en v3.24 (au-delà de recommencer) : non documenté (d).
- Fils du forum Sillysoft sur Lux Touch et versions archivées (Wayback) des pages de 2008-2009 : non consultés (accès bloqué) ; d'éventuelles réponses du développeur sur les réglages figés de Touch (séquence de cartes, taux de hausse des continents, bots) restent à vérifier.
- TouchArcade, 148Apps, AppAdvice, Macworld, Common Sense Media, BoardGameGeek, Reddit, YouTube : aucun contenu exploitable sur les règles de Lux Touch n'a pu être consulté (hôtes inaccessibles ou absence de résultat) ; TechRadar le qualifie de « pretty basic » d'après un extrait de moteur de recherche non vérifié à la source.
