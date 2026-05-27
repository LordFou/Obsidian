---
type: personne
---

# Andy Swann

## Présentation
- A 16 ans, il présente un jeu à la société [[Domark]]. Malgré leur refus, c'est là qu'il rencontrera pour la première fois [[Richard Naylor]] qui lui donnera des conseils techniques un exemplaire de [[The Living Daylights]].
- Bien décidé à devenir programmeur à plein temps, il passera un entretien qui n'aboutira pas chez [[Rare]].
- Passé à la programmation ST, il recevra un coup de fil de [[Richard Naylor]] lui demandant s'il pouvait encore programmer sur [[ZX Spectrum]]. A partir de là, il fut engagé par [[Enigma Variations]].
- [[Mark Mason]] lui apprendra l'initie au [[Programmers Development System]] (PDS)

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
