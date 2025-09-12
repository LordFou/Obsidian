# Émi Lefèvre

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  Française
- **Profession(s)** : Directrice de création
- **Entreprise(s) associée(s)** : [[Plane Studio]]

## Contributions Notables

```dataviewjs
const pages = dv.pages("");
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "émi lefèvre";
    
    if (content.toLowerCase().includes(personnalite) && lowerFileName !== personnalite) {
        results.push([page.file.link]);  // Ajouter le lien de la note dans le tableau
    }
}

// Afficher le tableau avec la colonne "A travaillé pour"
if (results.length > 0) {
    dv.table(["A travaillé pour"], results);
}

```

## Récompenses et Distinctions
- [[Pégases Award|Pégases]] 2025 avec Caravan SandWitch

## Controverses ou Faits Marquants
- [[Transgenre]]

## Sources et Références

