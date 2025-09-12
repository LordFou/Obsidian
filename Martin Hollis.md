---
type: personne
---

# Martin Hollis

## Présentation
- Ingénieur dans la team "bis" chez [[Rare]]

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : Ingénieur
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

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "martin hollis";
    
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
- Capable de citer la filmographie de [[Georges Lazenby]], un des acteurs incarnant [[James Bond]] dans le film de 1969 : "Au service de sa majesté"
- C'est lui qui a convaincu [[Rare]] d'accepter de faire [[GoldenEye 007]] pour [[Nintendo]] qui avait récupéré la licence. On pense qu'il considérait ça comme un défi technique, lui l'expert qui pouvait tirer le meilleur parti des puissantes machines de la société.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
