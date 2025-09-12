![[Pasted image 20250517232627.png]]
# Nolan Bushnel

## Présentation
- Fondateur d'[[Atari]]

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
- **Entreprise(s) associée(s)** : (Studios ou éditeurs avec lesquels il/elle a travaillé)  

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
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
- Régulièrement le soir, il passe dans les bureaux de la société et regardent les travaux de ses employés. Quand quelque chose lui plaisait, il l'emportait.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
