# Landing page - verticale bâtiment

Page de vente autonome pour l'offre PME du bâtiment (OGFactory).
Source des textes : `mon-business/wiki/concepts/landing-batiment.md`.

## Aperçu
Ouvrir `index.html` dans un navigateur (double-clic).

## En ligne
👉 **https://ogfactory.ch/batiment/** (hébergement Hostinger, dossier `public_html/batiment`).

## Redéployer après une modif (SSH/SCP)
Depuis ce dossier :
```bash
scp -P 65002 index.html \
  u414384509@mc-chemisage.ogfactory.ch:/home/u414384509/domains/ogfactory.ch/public_html/batiment/index.html
```
(la clé `~/.ssh/id_ed25519` est autorisée sur le serveur, pas de mot de passe).

## Alternatives
- GitHub Pages (repo `ogfactory-landing-batiment`) reste un miroir/sauvegarde.
- Netlify / Vercel : glisser le dossier si besoin d'un staging.

## À personnaliser ensuite
- Remplacer le lien "Réserver mon appel" par un vrai agenda (Calendly / Google Agenda).
- Ajouter de vrais témoignages clients bâtiment quand ils sont signés.
- Optionnel : intégrer le widget de l'agent vocal "Margot" directement sur la page.

Fichier autonome, sans dépendance externe.
