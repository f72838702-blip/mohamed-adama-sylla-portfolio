# Portfolio — Mohamed Adama SYLLA

Site vitrine professionnel pour **Mohamed Adama SYLLA**, Instituteur diplômé de l'ENI & Directeur d'Établissement Éducatif (École Maternelle & Formative Kanké Cireya, Dixinn Gare, Conakry, Guinée).

## Stack
- HTML5 + Tailwind CSS (CDN) + JavaScript vanilla (aucun build)
- Lucide Icons (CDN) + Google Fonts
- Polices : Playfair Display (titres) + Plus Jakarta Sans (corps)
- Design « Corporate Educational » — bleu marine / vert émeraude / or doux

## Sections
1. Hero (accroche + stats clés + photo)
2. À propos & philosophie pédagogique
3. Parcours — timeline interactive filtrable (Direction / Enseignement / Formations)
4. Domaines d'expertise (4 cartes)
5. Formations & certifications (grille)
6. Langues & compétences transversales (barres animées)
7. Contact (formulaire `mailto:` + boutons `tel:` / WhatsApp / e-mail)

## Aperçu local
Double-cliquer sur `index.html` ou ouvrir via un serveur :
```
cd mohamed-adama-sylla-portfolio
python -m http.server 8000
```
→ http://localhost:8000

## Déploiement Vercel
1. `npm i -g vercel` (si pas déjà installé)
2. `cd mohamed-adama-sylla-portfolio`
3. `vercel` → suivre les prompts
4. `vercel --prod` pour la production

Le dossier contient un seul `index.html` → Vercel le détecte automatiquement.

## À remplacer
- **Photo (Hero)** : remplacer le bloc placeholder `<!-- Photo à insérer -->` par une `<img src="assets/adama-sylla.jpg" ...>` dans la `.photo-frame`.
- **CV (PDF)** : placer un `assets/cv-adama-sylla.pdf` et pointer le bouton « Télécharger mon CV » dessus (retirer l'`alert` JS associée).

## Contact
- ✉️ adamamohamedsylla@gmail.com
- 📞 +224 626 33 20 25 / +224 660 77 9 080