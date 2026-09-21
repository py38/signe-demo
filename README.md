# SIGNÉ — démo

Démo interactive d'un système de devis pour artisans : l'artisan dicte son
chantier à voix haute, le devis est rédigé par Claude, puis les relances
partent automatiquement jusqu'à ce que le client réponde.

Deux téléphones côte à côte — celui de l'artisan, celui du client — et un
bouton « Avancer le temps » qui permet de montrer en trente secondes ce qui,
dans la vraie vie, prend deux semaines.

## Utilisation

Ouvrir la page, puis **Profil** en haut à droite :

- votre identité (elle signe les devis et les messages) ;
- votre **clé API Anthropic**, pour la génération du devis.

La clé est enregistrée dans le navigateur, sur votre machine uniquement.
Elle n'est pas dans ce dépôt et n'est jamais envoyée ailleurs qu'à
l'API d'Anthropic.

## Ce qui est simulé

Aucun email ni SMS n'est réellement envoyé, et rien n'est stocké côté serveur.
Les textes des relances sont préparés à l'avance ; seule la rédaction du devis
appelle vraiment Claude. Les chiffres du bandeau bas partent d'un historique
d'exemple.

Une page unique, sans dépendance ni build : `index.html`.
