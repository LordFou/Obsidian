---
type: personne
---

# Roger Laboureur

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  1935 - 2025
- **Nationalité** :  Belge
- **Profession(s)** : Commentateur Sportif 
- **Entreprise(s) associée(s)** : [[RTBF]]

```timeline-labeled
[line-5, body-2]
date:  
title: 
content:
```


## Contributions Notables
- Ses envolées lyriques
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


## Controverses ou Faits Marquants


## Sources et Références
- [Hommages](https://www.rtbf.be/article/michel-lecomte-rend-hommage-a-roger-laboureur-un-personnage-savoureux-amuseur-de-la-redaction-mais-tres-grand-pro-11648966)
- [Archives Audio](https://www.rtbf.be/article/ses-commentaires-cultes-et-des-anecdotes-insoupconnees-archives-club-rend-hommage-a-roger-laboureur-podcast-11648605)
- 
