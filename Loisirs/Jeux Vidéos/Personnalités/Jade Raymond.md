# Jade Raymond

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
- **Entreprise(s) associée(s)** : (Studios ou éditeurs avec lesquels il/elle a travaillé)  

```timeline-labeled
[line-5, body-2]
date: mai 2025  
title: Jade Raymond quitte [[Heaven Studio]]
content: Le projet Fairgames a des problèmes de qualité et on ne sait pas trop si elle quitte ou si on lui demande de quitte (?)
```


## Contributions Notables

```dataviewjs
const pages = dv.pages("");
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "jade raymond";
    
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
- Entre 2010 et 2025, elle accumule les changements de société et les projets annulés.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
