```dataviewjs
const pages = dv.pages('"Loisirs/Jeux Vidéos"');
const result = [];

for (const page of pages) {
  const content = await app.vault.read(page.file);
  if (content.includes("2025")) {
    result.push([page.file.link]);
  }
}

dv.table(["Jeux 2025"], result);
```