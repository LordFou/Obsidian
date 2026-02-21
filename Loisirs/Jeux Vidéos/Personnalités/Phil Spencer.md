---
type: personne
---

# Phil Spencer

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
- **Entreprise(s) associée(s)** : 
	- [[Microsoft]]

```timeline-labeled
[line-5, body-2]
date: Février 2026  
title: Il quitte son poste de CEO chez [[Microsoft]] Gaming
content: après 38 ans chez [[Microsoft]] (il avait commencé comme interne en 1988), il part à la retraite.
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
