# Portfolio — Serigne Bamba SAMB

Site vitrine statique en une page (`index.html`), interactif, sans dépendance à installer.

## Structure à uploader sur GitHub

```
index.html
assets/
  photo.jpg
README.md
```

L'image de profil doit rester dans `assets/photo.jpg` — le site y fait référence en chemin relatif.

## À vérifier avant de publier

- La section "Disponible pour un stage" mentionne un stage "de 2 à 3 mois en économie ou finance" sans date fixe : tes différents CV donnaient des fenêtres (mai-août 2026, 3 à 8 semaines) qui sont soit contradictoires soit déjà passées. Mets à jour cette phrase avec tes dates de disponibilité actuelles.
- Vérifie le niveau de français indiqué (C1 vs langue maternelle selon tes CV) — actuellement affiché sans niveau précis.

## Interactions incluses

- Bascule thème clair/sombre (mémorisée d'une visite à l'autre)
- Barre de progression de lecture
- Navigation qui surligne la section active au scroll
- Apparition progressive des sections au scroll
- Formation en accordéon (cliquer pour déplier le détail)
- Onglets dans Compétences
- Email et téléphone copiables en un clic

## Publier avec GitHub Pages

Voir les étapes détaillées données dans la conversation. En résumé : crée un dépôt public nommé `ton-nom-utilisateur.github.io`, uploade `index.html`, le dossier `assets/` et `README.md` à sa racine, puis active GitHub Pages dans Settings → Pages (branche `main`, dossier `/root`).
