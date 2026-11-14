# Opération Siège : une journée à New York

Jeu pédagogique de géographie (Terminale, thème « New York, ville mondiale »), environ 50 minutes.

Une PDG fictive, Jeanne Oliot, veut transférer le siège de son groupe de Dubaï à New York. L'élève, recruté·e dans le service d'intelligence économique, parcourt la ville et rassemble les preuves que New York est une **ville mondiale**, c'est-à-dire un **centre de commandement**.

## Déroulé

1. **Accueil** : le mail confidentiel de la PDG pose la mission.
2. **Plan** : une vue **3D** de New York (ou un plan 2D) avec 11 lieux à visiter dans l'ordre de son choix. On y voit les cinq arrondissements (Manhattan, Bronx, Queens, Brooklyn, Staten Island), les grands ponts et les tunnels vers le New Jersey.
3. **Lieux** : pour chacun, un document chiffré à lire, une question de compréhension, puis le classement du lieu dans le schéma « ville mondiale » (population, transports, centre financier et tertiaire).
4. **Jeu du taxi** : pause jeu en bonus.
5. **Rapport** : l'élève construit une note argumentée pour la PDG en suivant le plan du schéma, avec une limite.

Un **espace professeur** (protégé par un code) affiche le déroulé de l'heure, les réponses et les corrigés.

## Utiliser le jeu

C'est un site statique : il suffit d'ouvrir `index.html` dans un navigateur, ou de publier le dépôt avec GitHub Pages (Settings → Pages → branche `main`, dossier racine).

La vue 3D utilise [Three.js](https://threejs.org/) (r128), chargé depuis un CDN : une connexion Internet est nécessaire. Si la 3D n'est pas disponible sur l'appareil, le plan 2D s'affiche automatiquement.

La progression de l'élève est enregistrée dans le navigateur (localStorage).

## Fichiers

- `index.html` : tout le jeu (HTML, CSS, JavaScript)
- `img/` : photos des lieux et schéma de la classe

## Crédits

- Documents recomposés à partir de sources publiques (2024-2026), citées sous chaque document dans le jeu.
- Photos : Wikimedia Commons, auteurs et licences indiqués sous chaque photo dans le jeu.
- Personnage et entreprise fictifs, créés pour le jeu.
- Plan schématique : JFK et Newark sont figurés hors échelle.
