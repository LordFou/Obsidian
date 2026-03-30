---
type: personne
---

![[Pasted image 20250517232627.png]]
# Nolan Bushnel

## Présentation
- Né en Utah et mormont de naissance, ce n'est pas un enfant facile.
- Son loisir radio amateur va développer 
- Co-Fondateur d'[[Atari]] avec Alan 

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Américain
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

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "nolan bushnel";
    
    if (content.toLowerCase().includes(personnalite) && lowerFileName !== personnalite) {
        results.push([page.file.link]);  // Ajouter le lien de la note dans le tableau
    }
}

// Afficher le tableau avec la colonne "A travaillé pour"
if (results.length > 0) {
    dv.table(["A travaillé pour/avec"], results);
}

```

## Récompenses et Distinctions
- Plus jeune radio amateur du pays (10 ans)

## Controverses ou Faits Marquants
- Régulièrement le soir, il passe dans les bureaux de la société et regardent les travaux de ses employés. Quand quelque chose lui plaisait, il l'emportait.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
