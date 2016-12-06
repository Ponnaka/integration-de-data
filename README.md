# PHIK

Ponnaka Tith (Ponnaka)

Hugo Deléglise (Pipapou)

Ikram Jendari (Ikramounette)

Kevin Barbou Des Courières (lRedOx)


<h3>TESTER LE CODE</h3>
Après avoir télécharger l'ensemble des fichier dont vous avez besoin : **'index.html' ; 'style.css' ; 'correcteur.js' ; 'lemmatiseur.js' ; 'feel.js' ; 'dictionnaire/' ; 'Feel/' ; 'images/' ; 'lemm'**.

Ce code ne marche que sur le navigateur **MOZILLA Firefox** car sur les autres navigateur, l'ouverture des fichiers .json est impossible sur les autres navigateurs testés.

Après avoir entrer un **Pseudo Twitter** dans le formulaire (Exemple : 'tpmp'), cliquer sur Lancer puis attender quelques secondes (cela dépend de votre ordinateur), ensuite les tweets vont apparaître avec pour chacun leurs % de "sentiments" en fonction du nombre d'expression traitée par la fonction dans 'feel.js' puis le % globale de "sentiments" des tweets récupérés. Si des tweets ont des % "null", c'est soit les expression n'étaient pas présentes dnas 'FEEL.json' ou soit que la lémmatisation n'a pas été parfaite (Notre lémmatisation n'étant pas parfaite, elle doit être optimisé).




<li><h4>Technologies :</h4></li>

 - [x] Code en JavaScript
 - [x] Récupération des Tweets sans l'API Twitter 1.1
 - [x] Correction orthographique avec le dictionnaire "dictionnaire"
 - [x] Lemmatisation programmée par nos soins
 - [x] Vectorisation des mots lemmatisés avec le dictionnaire émotionnel « feel »
 - [x] Interface en HTML et CSS
 - [ ] Graphique pour avoir quelque chose de visuel et plus rapide à analyser
 - [ ] Des statistiques plus complexes
 - [ ] Traiter les hashtags
 - [ ] Optimiser le traitement du langage
 - [ ] Rendre le dictionnaire dynamique


<li><h4>Fonctionnalités :</h4></li>

<p>Dans un premier temps, nous indiquons au logiciel le pseudo dont nous souhaitons traiter les tweets.  A noter que le logiciel fonctionne seulement sur les tweets en français.</p>

<p>Les tweets récupérés seront caractérisés selon 6 émotions qui sont la joie, la colère, la tristesse, le dégoût, la surprise et la peur. Nous aurons également une valence moyenne (positif/négatif) pour chacun d’eux.</p>

<p>Pour chacune des émotions une moyenne globale des tweets sera calculée et une liste nous permettra de voir tous les tweets en détail ainsi que le pseudo de l’auteur et des 6 émotions.</p>
