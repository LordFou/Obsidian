---
type: personne
---

# Claude Guillemot

## Présentation
- Homme plus discret que ses autres frères, il travaillait dans l'ombre et dirigeait notamment [[Guillemot Corporation]] dont on connait quelques marques comme 
	- [[Thrustmaster]]
	- [[Hercules]]

## Informations Générales
- **Date de naissance** :  1957 - 2026 (Décès dans un crash d'avion de tourisme)
- **Nationalité** :  Français
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
- **Entreprise(s) associée(s)** : 
	- [[Ubisoft]] (Fondateur)

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

| Description | URL |
| ----------- | --- |
|             |     |
