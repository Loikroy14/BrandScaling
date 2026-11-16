# Agence de brand scaling pour marques de vêtements canadiennes

Page d'atterrissage statique (un seul fichier, `index.html`, aucune dépendance).

## Positionnement

> Programme Envergure : des ventes chaque mois, pas juste les jours de drop.
> L'équipe de croissance des marques de vêtements canadiennes : marque, publicité,
> contenu, site et rétention, pilotés ensemble dans un seul plan, sur vos chiffres.

Cible : marques de vêtements canadiennes à drops, ~30 000 à 300 000 $ CA par mois, dont la croissance plafonne parce que tout repose sur le fondateur. La page vend un seul résultat (le palier suivant) et une seule offre.

## Nom : Envergure

Domaine visé : envergureagence.com (pas encore acheté). Tout ce qui dépend de lui est dans le bloc
`window.AGENCE` en haut du `<body>` de `index.html` :

```js
window.AGENCE = {
  nom: "Envergure",
  courriel: "bonjour@envergureagence.com",
  lienRendezVous: "https://calendly.com/VOTRE-LIEN/appel-20-min",
  marquePilote: "Spoon"
};
```

Changez ces valeurs et la page se met à jour. Pour que le nom soit aussi dans le HTML
brut (aperçus de liens, moteurs de recherche), remplacez aussi `Envergure` partout
dans le fichier.

## Offre

- Diagnostic de croissance : 600 $
- Programme : 2 900 $/mois
- Garantie : 50 % du mois remboursé si on rate une date de livraison

## À faire avant de mettre en ligne

- Acheter envergureagence.com.
- Remplacer `lienRendezVous` par un vrai lien Calendly (ou Cal.com) et le courriel.
- Confirmer avec Spoon qu'on peut citer leur nom sur la page.
- Héberger : GitHub Pages, Netlify ou Cloudflare Pages servent `index.html` tel quel.
