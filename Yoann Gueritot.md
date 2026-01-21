---
type: personne
---

# Yoann Gueritot

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  1987
- **Nationalité** :  Français
- **Profession(s)** : 
	- Testeur
	- Level Designer
	- Réalisateur 
- **Entreprise(s) associée(s)** : 
	- [[CyberConnect2]]
	- [[PlatinumGames]]
	- [[Sega]]

```timeline-labeled
[line-5, body-2]
date: 2010 
title: Début de carrière dans le jeu vidéo en France
content: 

date: 2013 
title: Arrivée au Japon
content: Il est engagé au sein de [[CyberConnect2]]

date: ? 
title: Entrée chez [[PlatinumGames]]
content:

date: 2026 
title: Entrée chez [[Sega]]
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

# Anecdotes
- Premières consoles
	- [[NES]] 
	- [[Megadrive]]
- Premiers jeux
	- Final Fantasy VII
	- Suikoden
	- Katamary Damacy
	- Shadow of the Colossus
	- Shenmue
	- Jet Set Radio
- Son but était de devenir game designer mais il ne voulait pas faire des études (trop long, trop cher), donc il l'a joué au culot en passant par la filière testeur de jeux et a monté les échelons petit à petit.
- Il a utilisé des outils comme [[JIRA]] notamment pour tous les tickets de testeur.
## Sources et Références
- https://www.pointnthink.fr/fr/interview-yoann-gueritot/
