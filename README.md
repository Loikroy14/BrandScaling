# Agence de brand scaling pour marques de vêtements canadiennes

Page d'atterrissage statique (un seul fichier, `index.html`, aucune dépendance).

## Positionnement

> L'équipe de croissance des marques de vêtements canadiennes : marque, publicité,
> contenu, site et rétention, pilotés ensemble dans un seul plan, sur vos chiffres.

Cible : marques de vêtements canadiennes à drops, ~15 000 à 150 000 $ CA par mois.

## Nom provisoire : Brand Scaling

Le nom final n'est pas choisi. Tout ce qui dépend de lui est dans le bloc
`window.AGENCE` en haut du `<body>` de `index.html` :

```js
window.AGENCE = {
  nom: "Brand Scaling",
  courriel: "bonjour@votreagence.ca",
  lienRendezVous: "https://calendly.com/VOTRE-LIEN/appel-20-min",
  marquePilote: "Spoon"
};
```

Changez ces valeurs et la page se met à jour. Pour que le nom soit aussi dans le HTML
brut (aperçus de liens, moteurs de recherche), remplacez aussi `Brand Scaling` partout
dans le fichier.

## À faire avant de mettre en ligne

- Nom final et domaine.
- Remplacer `lienRendezVous` par un vrai lien Calendly (ou Cal.com) et le courriel.
- Confirmer avec Spoon qu'on peut citer leur nom sur la page.
- Valider la garantie « mois offert si on manque une date ».
- Héberger : GitHub Pages, Netlify ou Cloudflare Pages servent `index.html` tel quel.
