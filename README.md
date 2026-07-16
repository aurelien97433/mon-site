# Portfolio de Thomas

Site portfolio one-page présentant les projets, le blog et les coordonnées de Thomas, graphiste.

🔗 **Site en ligne :** https://aurelien97433.github.io/mon-site/

## Aperçu

Ce site est un portfolio statique (HTML/CSS) organisé en plusieurs sections accessibles via une navigation à ancres :
- **Accueil** — présentation et photo
- **Blog** — articles récents
- **Portfolio** — travaux mis en avant
- **Contact** — coordonnées et formulaire

## Structure du projet

```
mon-site/
├── index.html          # Page principale
├── style.css            # Feuille de style
└── img/                  # Images du site
    ├── logo.png
    ├── menu.png
    ├── photo-de-thomas.png
    ├── projet-1.png
    ├── projet-2.png
    ├── projet-3.png
    ├── fb.png
    ├── insta.png
    ├── twitter.png
    └── Linkedin.png
```

## Installation

Aucune dépendance ni build n'est nécessaire, ce projet fonctionne en HTML/CSS pur.

**1. Cloner le dépôt**
```bash
git clone https://github.com/aurelien97433/mon-site.git
cd mon-site
```

**2. Ouvrir le site en local**

Double-clique simplement sur `index.html`, ou ouvre-le depuis ton navigateur :
```bash
open index.html        # macOS
start index.html        # Windows
```

> ⚠️ Le fichier doit impérativement s'appeler `index.html` en minuscules, et le dossier `img/` doit rester au même niveau que `index.html` pour que les images s'affichent correctement.

**3. Servir le site avec un serveur local**

Pour un rendu plus proche de la production (utile si tu ajoutes du JS ou du fetch plus tard) :
```bash
# Avec Python
python3 -m http.server 8000

# Avec Node.js (via npx)
npx serve .
```
Puis ouvre `http://localhost:8000` dans ton navigateur.

## Déploiement

Le site est déployé automatiquement via **GitHub Pages** depuis la branche `main`.
Toute modification poussée sur `main` est publiée sous quelques minutes à l'adresse :
👉 https://aurelien97433.github.io/mon-site/

## Typographie

Le site utilise la police **[Heebo](https://fonts.google.com/specimen/Heebo)**, importée depuis Google Fonts :

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Heebo:wght@100..900&display=swap" rel="stylesheet">
```

```css
body {
  font-family: "Heebo", sans-serif;
}
```

## Palette de couleurs

- Texte principal : `#21243d`
- Liens de navigation : `#000000`

## Auteur

Site conçu par Aurélien Raynaud.
