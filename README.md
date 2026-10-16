# Portfolio – Douaa Boudjelti
Site statique bilingue (EN par défaut / FR), sans backend ni bibliothèque externe.

## Structure
index.html · css/style.css · js/main.js · assets/images/ · assets/documents/cv.pdf

## Publier sur GitHub Pages
1. Créez un dépôt GitHub (ex. `portfolio`), public.
2. Cliquez sur **Add file > Upload files**, glissez le CONTENU du dossier (index.html, css, js, assets) à la racine, puis **Commit changes**.
3. **Settings > Pages > Build and deployment** : Source = *Deploy from a branch*, Branch = `main`, dossier `/ (root)`, **Save**.
4. Après 1 à 2 minutes, le site est en ligne sur `https://VOTRE-NOM.github.io/portfolio/`. Tous les chemins sont relatifs, donc il fonctionne depuis cette URL.

## Modifier le contenu
- **CV** : remplacez `assets/documents/cv.pdf` en gardant le même nom.
- **Portrait** : remplacez `assets/images/douaa-boudjelti-portrait.jpg` (format 4:5 conseillé).
- **Contact** : modifiez l'e-mail et le lien LinkedIn dans la section `#contact` de index.html.
- **Textes FR** : dictionnaire `FR` en haut de js/main.js. Textes EN : directement dans index.html.
- **Études de cas** : objet `P` dans js/main.js (texte EN/FR et images).
- **Nouveau projet** : ajoutez une `<article class="card">` dans `#work` (avec `data-cat` et `data-p`), puis une entrée dans `P`, et déposez les captures dans assets/images/.

## Checklist après publication
- [ ] La page s'ouvre, le sélecteur EN/FR change tout le texte
- [ ] Le menu mobile s'ouvre et se ferme
- [ ] Les filtres de projets fonctionnent
- [ ] Chaque étude de cas s'ouvre et ses images s'affichent
- [ ] Le CV se télécharge
- [ ] L'e-mail et LinkedIn s'ouvrent
- [ ] Aucune erreur dans la console du navigateur

## À vérifier avant d'envoyer
- Les statistiques sont celles des comptes (captures du 16 sept. – 15 oct.), étiquetées comme telles.
- Confirmez que vous avez l'autorisation d'utiliser les captures et les noms des clients.
- Les captures montrent des visages floutés ou du contenu client : vérifiez-les.
