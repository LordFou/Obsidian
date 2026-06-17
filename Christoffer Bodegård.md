---
type: personne
---

# Christoffer Bodegård

## Présentation
- Diplômé en game writing à Skövde en 2015, dernier de sa promo, il enchaîne d’abord les contrats de narrative design sur des projets d’horreur et de survie, fonde une boîte qui s’écroule en 2017, puis décide de tout reprendre lui-même : code gameplay, modélisation 3D, écriture, direction artistique. 
- Il détestait la programmation mais après la faillite de sa boîte, il a appris a apprécié et surtout à garder la main sur la base du code de ses projet.
- Pour lui, plus le joueur possède de contexte autour d'un choix, plus ce choix lui semble avoir du poids sur le jeu. C'est ce qu'il avait démontré dans son mémoire de fin d'étude et qui semble se confirmer avec le succès de son jeu [[Esoteric Ebb]].

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Suédois
- **Profession(s)** : [[Développeur]]
- **Entreprise(s) associée(s)** : (Studios ou éditeurs avec lesquels il/elle a travaillé)  

```timeline-labeled
[line-5, body-2]
date:  
title: 
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
- Interview de Point
