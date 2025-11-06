---
type: personne
---

# Bill Hogue

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Américain
- **Profession(s)** : Concepteur
- **Entreprise(s) associée(s)** : [[Big Five Software Co.]]

```timeline-labeled
[line-5, body-2]
date: 1983
title: Sortie de [[Miner 2049er]]
content:

date: 1984
title: Sortie de [[Bounty Bob Strikes Back]]
content:

date: 1984
title: Discussion pour une suite
content: [[Bill Hogue]] expérimente quelques concepts avec [[Jeff Zinn]] mais ça ne mènera nulle part et Bill conseille de se trouver un boulot dans la "vraie vie"

date: 1984   
title: Eloignement du secteur du jeu vidéo
content: après la sortie de [[Bounty Bob Strikes Back]], Bill quitte le secteur des jeux vidéos principalement à cause du déclin du secteur

date: 1990
title: Transfert de la licence Miner chez [[Mindscape]]
content:

date: 2024
title: Miner2049 III ?
content: [[Bill Hogue]] n'a pas abandonné de revenir au jeu vidéo et de développer une vraie suite mais à sa pension si il la prend. Et avec son pote [[Curtis Mikolyski]].
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
    dv.table(["A travaillé pour/avec/sur"], tableData);
}

```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
