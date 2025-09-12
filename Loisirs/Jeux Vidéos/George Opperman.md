![[Pasted image 20250517232307.png]]
# George Opperman

## Présentation
Responsable du département artistique chez [[Atari]] (1977), c'est notamment lui qui a créé le logo de la société.

![[Pasted image 20250517004924.png]]
## Informations Générales
- **Date de naissance** :  1935 (1985)
- **Nationalité** :  
- **Profession(s)** : Designer Artistique (?)
- **Entreprise(s) associée(s)** : 
	- [[Atari]]

## Contributions Notables

```dataviewjs
const pages = dv.pages("");
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);  // Utilisation de await pour attendre le contenu
    const lowerFileName = page.file.name.toLowerCase();
    const personnalite = "george opperman";
    
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
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
