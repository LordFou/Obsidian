---
type: personne
---

# Laurant Weill

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Français
- **Profession(s)** :   
	- 
- **Entreprise(s) associée(s)** : 
	- Fondateur de [[Loriciel]]

```timeline-labeled
[line-5, body-2]
date: 1981
title: création d'un ordinateur
content: avec des potes, il crée un micro ordinateur de A à Z qu'il présente à des sociétés mais leur jeunesse les décrédibilise et on leur répond qu'on ne croit pas aux processeurs 16bit et qu'on va rester sur les proco 68000

date: 
title: Import de l'[[Oric-1]] en France
content: Emerveillé par les spec de la machine, il voulait absolument le distribuer en France. 

date :
title: Participation au Dakar des neiges
content: C'était sur moto-neige. Pas du tout entrainé à la chose comparé à d'autres participants. Ils ont gagné leur catégorie et ont édité un jeu qui représente cette course [[Harricana]].

date: 1994
title: création de Visiware
content: 

```


## Contributions Notables

```dataviewjs
const pages = dv.pages("");
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "laurant weill";
    
    if (content.toLowerCase().includes(personnalite) && lowerFileName !== personnalite) {
        results.push([page.file.link]);  // Ajouter le lien de la note dans le tableau
    }
}

// Afficher le tableau avec la colonne "A travaillé pour"
if (results.length > 0) {
    dv.table(["A travaillé pour/avec/sur"], results);
}

```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
- Il s'est engueulé avec Steve Jobs pour une fonctionnalité de menu qu'il démontrait dans une réunion. Mais il ne l'avait pas reconnu.

## Sources et Références
- https://www.youtube.com/watch?v=N-KklTyhL0g
- 
