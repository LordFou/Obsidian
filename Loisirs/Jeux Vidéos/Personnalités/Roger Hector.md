![[Pasted image 20250516235000.png]]
# Roger Hector

## Présentation
Ecole de design, il était prédestiné pour une carrière dans l'industrie automobile mais le choc pétrolier de 1972-1973 l'a fait bifurqué chez Atari, c'était le tout début de la société et une période qu'il a fort apprécié. Depuis un demi-siècle, il est dans le secteur des jeux vidéos et il a créé quelques grands noms de l'histoire du jeu vidéo.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** : [[Américain]]
- **Profession(s)** : [[Artiste]], [[Designer]], [[Manager]]
- **Entreprise(s) associée(s)** : 
	- [[Atari]]
	- [[Sente]]
	- [[Sega]]
	- [[Electronic Arts]]
	- [[Disney]]
	- [[Namco]]


## Historique

```timeline-labeled
[line-5, body-2]
date: 1976 
title: Entrée chez Atari
content: Attiré par le climat californien qu'il a connu dans son enfance, il est "invité" par un ami à travailler chez Atari. A cette époque, personne n'a d'expérience dans les jeux vidéo, on engageait donc sur base des compétences annexes. Pendant un an, il a donc commencé par reproduire sur écran grâce à son diplôme en design industriel, tout cela dans la division design qui concevait les bornes de jeu.

date: 1977 
title: Entrée dans le département artistique
content: [[George Opperman]] vient le chercher pour créer un flipper avec la licence [[Superman]]. Il crèe alors toutes les illustrations de la table

date: 1977
title: Création de la borne d'arcade [[Subs]]
content: généralement ils concevaient plusieurs versions des bornes (low-cost et de qualité par exemple | borne simple ou avec accessoire)  

date: 1980
title: Sortie de [[Battlezone]]
content: Ed Rotberg lui demande de dessiner les modèles vectoriels du jeu. C'est à cette époque qu'il passe aux graphismes in-game.

date: 1980
title: Sortie de [[Warlords]]
content: Il est le premier dans la société à utiliser des story board pour présenter ses projets dont celui-ci. Il propose également de mélanger [[Pong]] et [[Breakout]] pour le jeu

date: 1980
title: Intégration à l'équipe de R&D pour la [[Cosmos]]
content: Contacté par [[Al Alcorn]], le projet est de créer la console [[Cosmos]]

date: 1981
title: Départ de chez [[Atari]] et Création de [[Videa]]
content: Suite à la non commercialisation de la [[Cosmos]], [[Roger Hector]], [[Ed Rotberg]] et [[Howie Delman]] décident de fonder [[Vidéa]]

date: ?
title: Courte vie de [[Videa]]
content: Le but était de faire des jeux arcade et de les revendre à des compagnies comme [[Williams]], [[Gottlied]], [[Atari]]. Aucun jeu ne sortira malgré des achats par celles-ci. Le marché vit le [[Crash de 1983]]

date: ?
title: Rachat de [[Videa]] par [[Sente]] Technologies
content: Les fondateurs de Videa ont des propositions de rachat par [[Coca-Cola]] ou Sente. Ils choisissent Sente car ils savent comment travaille [[Nolan Bushnel]].

date: 1984
title: Sortie de [[Chicken Shift]]
content: C'est l'époque où [[Sente]] a eu la bonne idée de sortir des bornes génériques dans laquelle on pouvait changer le jeu. On appelait ça le [[Sente System]]

date: 1987
title: Départ de [[Bally Sente]] et début chez [[Electronic Arts]]
content: Son contrat se terminait et la société était sur la pente descendant, il décide donc de partir chez EA en tant que producteur senior sur les jeux de sport, d'action et d'arcade. Ils ne mettaient pas juste des noms de stars sur une boîte mais ils écoutaient vraiment leurs idées.

date: ?
title: Arrivée chez [[Disney]]
content: Il travaillera sur des films et dessins animés. C'est là qu'il rencontrera des directeurs de chez Sega quand ceux-ci voulaient acheter des licences comme [[Mickey Mouse]] ou [[Donald Duck]]. C'était à lui d'accepter ou refuser leur travail 😈.

date: ?
title: Arrivée chez [[Sega]]
content: Après le départ de Mark Cerny de la tête du Sega Technical Institute,  Sega l'engage pour le remplacer en plein dans la folie Sonic. Il chapeautera des gens comme [[Yuji Naka]], [[Hirozaku Yasuhara]], [[Kunitake Aoki]] et [[Naoto Ohshima]] qui travaillent sur [[Sonic 2]].

date: ?
title: Rencontre avec [[Mickaël Jackson]]
content: Mickael Jackson voulait rencontrer les créateurs de son jeu préféré ([[Sonic]]). Suite à cette entrevue, il devait composer toute la bande son de [[Sonic 3]]. Malheureusement, juste avant la sortie du jeu, les révélations sur la relation de la star avec de jeunes enfants poussent Sega Japon a retirer toutes ses musiques. [[[[Howard Drossin]]]] a dû composé les musiques à remplacer en 1 semaine à la place de 4 mois.

date: ?
title: Départ de Sega
content: il part à cause d'une succesion de mauvaises décisions de leur part. Ce sera à l'époque de l'échec de la Saturn.

date: ?
title: Président chez [[Universal Studios Digital Arts]]

date: ?
title: Vice President Senior chez [[Namco Bandaï]]

date: ? 
title: Création de jeux chez [[The Singleton Foundation]]

```

## Contributions Notables


```dataviewjs
const pages = dv.pages("");
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "roger hector";
    
    if (content.toLowerCase().includes(personnalite) && lowerFileName !== personnalite) {
        results.push([page.file.link]);  // Ajouter le lien de la note dans le tableau
    }
}

// Afficher le tableau avec la colonne "A travaillé pour"
if (results.length > 0) {
    dv.table(["A travaillé pour/avec/sur"], results);
}

```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
- Il participe à la conception de la première table de flipper d'[[Atari]] -> [[The Atarians]]
- Ses notes et croquis sont régulièrement repris par [[Nolan Bushnel]] lors de ses rondes de nuit dans les bureaux, ce qui provoquait beaucoup de discussion constructive sur son travail.
- Lorsqu'[[Ed Rotberg]] lui demande s'il sait dessiner de la 3D, il lui ment, ce qui lui permet de travailler sur Battlezone. Mais ses notions de dessin d'architecture en perspective lui serviront grandement.
- Son jeu de borne d'arcade préféré pour lequel il a travaillé est [[Stompin']]. Vient ensuite [[Night Stocker]]
- Il a aussi conçu une attraction interactive pour un [[parc d'attraction]] -> [[Hautington Hotel]]
- Durant sa carrière, il croisera [[Michael Jordan]], [[Mario Andretti]] afin de préparer des jeux à leur nom.

## Sources et Références
- Retrogamer n°37 - Avril 2024
