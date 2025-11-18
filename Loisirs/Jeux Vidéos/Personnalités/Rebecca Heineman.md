---
type: personne
---

# Rebecca Heineman

## Présentation
- Pionnière de la visibilité LGBT dans le milieu du jeu vidéo

## Informations Générales
- **Date de naissance** :  1963 - 2025
- **Nationalité** :  
- **Profession(s)** : 
	- Concepteur
	- [[Game Designer]]
	- [[Programmeur]]
- **Entreprise(s) associée(s)** : 
	- Co-fondatrice d'[[Interplay]], puis de Mac Play (?)
- **Pseudo** : [[Burger Becky]]

```timeline-labeled
[line-5, body-2]
date:  
title: 
content:
```


## Contributions Notables
- [[Bard's Tale 3]]
- [[Dragon Wars]] (= Bard's Tale 4)
- [[Doom]] en version [[3DO]]
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
- Sacrée championne de [[Space Invaders]] en 1980 sur [[Atari 2600]]

## Controverses ou Faits Marquants
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
