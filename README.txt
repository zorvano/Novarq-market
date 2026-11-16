NOVARQ MARKET — VERSION DE PRESENTATION PRE-LANCEMENT

Fichiers:
- index.html : site web autonome (HTML, CSS et JavaScript intégrés).

IDENTITE
- Couleurs: bleu royal et argent.
- Langues: français, anglais et arabe.
- Contact affiché: novarqmarket@gmail.com.

DEPLOIEMENT
GitHub:
1. Créez un dépôt nommé novarq-market.
2. Ouvrez le dépôt puis Add file > Upload files.
3. Décompressez cette archive et téléversez index.html à la racine du dépôt.
4. Validez avec Commit changes.

Cloudflare Pages:
1. Dans Cloudflare, ouvrez Workers & Pages > Create > Pages.
2. Connectez le dépôt GitHub novarq-market.
3. Pour un site HTML statique sans build: Framework preset = None.
4. Build command: laisser vide.
5. Build output directory: / (racine du dépôt).
6. Lancez le déploiement.

LIMITES IMPORTANTES
Cette version est une vitrine pré-lancement, pas encore une marketplace transactionnelle:
- pas de comptes vendeurs/clients;
- pas de panier ni paiement;
- pas de gestion des commandes ou des stocks;
- le formulaire prépare un e-mail dans l'application de messagerie du visiteur; il ne stocke pas les demandes sur un serveur.

Avant d'accepter des commandes ou paiements, il faudra ajouter un backend sécurisé, une base de données, des conditions de vente, la politique de confidentialité, les règles vendeurs, et intégrer des prestataires de paiement et livraison adaptés aux pays desservis.
