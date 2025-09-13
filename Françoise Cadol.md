---
type: personne
---

# Françoise Cadol

## Présentation
- Très active dans le [doublage](https://fr.wikipedia.org/wiki/Doublage "Doublage"), elle est la voix française régulière de [Sandra Bullock](https://fr.wikipedia.org/wiki/Sandra_Bullock "Sandra Bullock"), [Angelina Jolie](https://fr.wikipedia.org/wiki/Angelina_Jolie "Angelina Jolie"), [Tilda Swinton](https://fr.wikipedia.org/wiki/Tilda_Swinton "Tilda Swinton"), [Gong Li](https://fr.wikipedia.org/wiki/Gong_Li "Gong Li") et [Rose Byrne](https://fr.wikipedia.org/wiki/Rose_Byrne "Rose Byrne") mais aussi de [Brenda Strong](https://fr.wikipedia.org/wiki/Brenda_Strong "Brenda Strong"), [Patricia Arquette](https://fr.wikipedia.org/wiki/Patricia_Arquette "Patricia Arquette"), [Michaela McManus](https://fr.wikipedia.org/wiki/Michaela_McManus "Michaela McManus") et [Jill Hennessy](https://fr.wikipedia.org/wiki/Jill_Hennessy "Jill Hennessy").

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
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
