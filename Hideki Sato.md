---
type: personne
---

# Hideki Sato

## Présentation
- L'ingénieur qui se cache derrière toutes les consoles [[Sega]]
	- Architecte de la [[Master System]] (et des modèles [[SG-1000]])
	- Directeur du département R&D au début des années 90, il va modeler l'ensemble des consoles [[Sega]] de la [[Megadrive]] à la [[Dreamcast]]
	- Président de 2001 à 2003
	- Départ en 2008 pour fonder [[Advance Create]]

## Informations Générales
- **Date de naissance** :  1949 - Février 2026
- **Nationalité** :  Japonais
- **Profession(s)** : Ingénieur
- **Entreprise(s) associée(s)** : [[Sega]]

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
- [Lien vers une source](#)
- [Article détaillé](#)
