# Portfolio Tex Tshiteya — Spécialiste Marketing Numérique & Gestion de Projets

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fogoulajesse%2Fportfolio-tex-tshiteya)

Site portfolio one-page officiel de **Tex Tshiteya**, reproduisant fidèlement le design system brutaliste éditorial « Dossier » (noir / blanc / gris, angles droits stricts, typographie Bebas Neue & Inter).

---

## Architecture du Projet

```text
├── index.html          # Structure sémantique, SEO, JSON-LD, CSS critique inliné
├── vercel.json         # Configuration optimisée Vercel (en-têtes de sécurité, mise en cache CDN)
├── README.md           # Documentation et guide de déploiement
├── .gitignore          # Fichiers exclus du versionnement
└── assets/
    ├── style.css       # Design system complet, grain SVG, animations GPU 60fps
    ├── main.js         # Interactions Vanilla JS (< 5 Ko), accordéon, menu mobile, scroll-reveal
    ├── favicon.svg     # Favicon vectoriel brutaliste
    ├── tex-tshiteya.avif # Portrait N&B compressé haute performance (8.5 Ko)
    ├── tex-tshiteya.webp # Portrait N&B format WebP (17.9 Ko)
    └── tex-tshiteya.jpg  # Portrait N&B format standard de repli (31.8 Ko)
```

---

## Déploiement

### Option 1 : Déploiement en 1 clic sur Vercel (Recommandé)
1. Rendez-vous sur [vercel.com/new](https://vercel.com/new).
2. Importez le dépôt GitHub `ogoulajesse/portfolio-tex-tshiteya`.
3. Cliquez sur **Deploy** : le site est instantanément en ligne avec HTTPS, CDN mondial et compression Brotli.

### Option 2 : Déploiement via le CLI Vercel
```bash
npm i -g vercel
vercel --prod
```

### Option 3 : Déploiement sur GitHub Pages
1. Rendez-vous dans les `Settings > Pages` de ce dépôt GitHub.
2. Choisissez la branche `main` et le dossier racine `/root`.
3. Enregistrez : le site est publié à l'adresse `https://ogoulajesse.github.io/portfolio-tex-tshiteya/`.

---

## Identité & Contact du Titulaire
* **Nom** : Tex Tshiteya
* **Rôle** : Spécialiste en Marketing Numérique & Gestion de Projets
* **Localisation** : Kinshasa, République Démocratique du Congo
* **Courriel** : tshiteyatex@gmail.com
* **Téléphone** : +243 89 244 57 55
* **LinkedIn** : https://linkedin.com/in/tex-tshiteya-939b26427
