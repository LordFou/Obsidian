```dataviewjs
const pages = dv.pages('"Loisirs/Jeux Vidéos"');
const results = [];

for (let page of pages) {
    const content = await dv.io.load(page.file.path);
    const search_str = "wwww";

    if (content.includes(search_str) && page.file.name != "wwww") {
        results.push([page.file.link, page.file.name]); // on ajoute aussi le nom pour trier
    }
}

// Tri alphabétique par nom de fichier (indice 1 du tableau)
results.sort((a, b) => a[1].localeCompare(b[1]));

// Affichage sans afficher le nom en deuxième colonne
dv.table(["Listing"], results.map(r => [r[0]]));

```