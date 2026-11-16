# Agence de croissance pour marques de vêtements canadiennes

Page d'atterrissage statique (un seul fichier, `index.html`, aucune dépendance).

## Nom provisoire : Cadence Drop

Le nom n'est pas choisi. Tout ce qui dépend de lui est dans le bloc `window.AGENCE`
en haut du `<body>` de `index.html` :

```js
window.AGENCE = {
  nom: "Cadence Drop",
  courriel: "bonjour@cadencedrop.ca",
  lienRendezVous: "https://calendly.com/VOTRE-LIEN/appel-20-min",
  marquePilote: "Spoon"
};
```

Changez ces valeurs et la page se met à jour. Pour que le nom soit aussi dans le HTML
brut (aperçus de liens, moteurs de recherche), remplacez aussi `Cadence Drop` partout
dans le fichier.

## Noms proposés (domaines vérifiés le 16 novembre 2026)

| Nom | .ca | .com |
|---|---|---|
| Restock (proposé au fil Fondations) | restockagency.ca et agencerestock.ca disponibles | restockagency.com et agencerestock.com disponibles |
| Cadence Drop | cadencedrop.ca disponible | cadencedrop.com disponible |
| Boréal Drop | borealdrop.ca disponible | borealdrop.com disponible |
| Studio Relance | studiorelance.ca disponible | pris |
| Signal Nord | signalnord.ca disponible | pris |
| Maison Drop | maisondrop.ca disponible | non confirmé |

La disponibilité est un instantané, pas une réservation.

## Positionnement

> Cadence Drop fait vendre plus chaque drop aux marques de vêtements canadiennes,
> et entre les drops, avec un système email + SMS bilingue qu'on construit et qu'on opère.

## À faire avant de mettre en ligne

- Remplacer `lienRendezVous` par un vrai lien Calendly (ou Cal.com).
- Confirmer avec Spoon qu'on peut citer leur nom sur la page.
- Valider la garantie « mois offert si on manque une date ».
- Héberger : GitHub Pages, Netlify ou Cloudflare Pages servent `index.html` tel quel.
