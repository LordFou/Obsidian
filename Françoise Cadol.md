---
type: personne
---

# Françoise Cadol

## Présentation
- Très active dans le doublage, elle est la voix française régulière de [[Sandra Bullock]], [[Angelina Jolie]]
- Elle est également connue pour avoir prêté sa voix à de nombreux personnages du jeu vidéo, dont notamment à [[Lara Croft]] dans les jeux [[Franchise Tomb Raider|Tomb Raider]] entre 1996 et 2008. Elle est également la voix de l'avocate [[Kate Walker]] dans la quadrilogie [[Syberia]] (2001-2022) de [[Benoît Sokal]] ainsi que celle de [[Madison Paige]] dans [[Heavy Rain]].

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
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
    dv.table(["A travaillé pour/avec/sur"], tableData);
}

```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
- En 2025, les développeurs d'une compilation des Tomb Raider 4-5-6 ont utilisé une IA pour générer sa voix 

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
