# Rob King

## Présentation
Brève introduction sur la personnalité : rôle dans l’industrie du jeu vidéo, importance, impact.

## Informations Générales
- **Date de naissance** :  
- **Nationalité** :  
- **Profession(s)** : (Développeur, Designer, Compositeur, Journaliste, etc.)  
- **Entreprise(s) associée(s)** : (Studios ou éditeurs avec lesquels il/elle a travaillé)  

## Contributions Notables
| Année | Projet / Jeu | Rôle        | Studio / Éditeur    |
| ----- | ------------ | ----------- | ------------------- |
| 1996  | Heroes 3     | Compositeur | New World Computing |

```dataviewjs
const pages = dv.pages("");
for (let page of pages) {
    const content = dv.io.load(page.file.path);
    const lowerFileName = page.file.name;
    
    content.then(text => {
	
	if (text.includes("Rob King") && lowerFileName !== "Rob King") 
		{
            dv.table(["A travaillé pour "], [[page.file.link]]);
        }
    
    });
}
```

## Récompenses et Distinctions
Lister les prix et reconnaissances obtenues.

## Controverses ou Faits Marquants
Évoquer les polémiques ou événements notables liés à cette personne.

## Sources et Références
- [Lien vers une source](#)
- [Article détaillé](#)
