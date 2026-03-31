---
type: personne
---
![[image-516.webp]]
# Rob Fulop

## Présentation

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Américain
- **Profession(s)** : 
	- [[Développeur]]
- **Entreprise(s) associée(s)** : 
	- [[Atari]]
	- [[Imagic]]

```timeline-labeled
[line-5, body-2]
date: Fin des années 70
title: Travail de larbins chez Atari 
content: A la fin des années 70, Rob avait déjà travaillé sur quelques jeux chez [[Atari]] mais il en avait marre de se tuer à la tâche pour de maigres compensations.

date: 1981
title: Départ de chez Atari
content: La goutte d'eau qui fait déborder le vase, c'est la prime insultante qu'on lui a versée pour la version [[Atari 2600]] de [[Missile Command]] => une dinde pour Thansgiving !! Il quitte alors [[Atari]] avec d'autres développeurs et fondent [[Imagic]]

date: 1982
title: Développement et sortie de [[Demon Attack]]
content: Succès commercial avec 2 millions d'unités vendues et bras d'honneur à [[Atari]]. [[Rob Fulop]] ne travaillera que sur la version [[Atari 2600]] mais il rédigera un document de 3 pages expliquant les fondements du système pour les futurs portages. Il ne développera pas de suite au jeu négligeant l'argent qu'aurait pu rapporter un second épisode.

date: 1982
title: Développement de [[Cosmic Ark]]
content: 
```


## Contributions Notables

```dataviewjs
const pages = dv.pages("");
const results = [];
const personnalite = dv.current().file.name.toLowerCase();  // Nom de la note actuelle

for (let page of pages) {
    const content = await dv.io.load(page.file.path);
    const lowerFileName = page.file.name.toLowerCase();

    if (content.toLowerCase().includes(personnalite) && lowerFileName !== personnalite) {
        results.push({
            link: page.file.link,
            name: page.file.name.toLowerCase()
        });
    }
}

// Tri **sans localeCompare**, via comparaison de chaînes simples
results.sort((a, b) => {
    if (a.name < b.name) return -1;
    if (a.name > b.name) return 1;
    return 0;
});

// Affichage sous forme de tableau à une colonne
const tableData = results.map(item => [item.link]);

if (tableData.length > 0) {
    dv.table(["A travaillé pour/avec/sur/est lié à"], tableData);
}

```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
