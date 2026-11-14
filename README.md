# Opération Siège : une journée à New York

Jeu pédagogique de géographie (Terminale, thème « New York, ville mondiale »), environ 50 minutes.

Une PDG fictive, Jeanne Oliot, veut transférer le siège de son groupe de Dubaï à New York. L'élève, recruté·e dans le service d'intelligence économique, parcourt la ville et rassemble les preuves que New York est une **ville mondiale**, c'est-à-dire un **centre de commandement**.

## Déroulé

1. **Identité** : l'élève découvre son personnage, diplômé·e de l'Université de Rennes, et tape son prénom.
2. **Bureau de la présidente** : Mme Oliot, qui hésite entre Pékin et New York, lui confie la mission dans des bulles qui s'écrivent au fur et à mesure.
3. **Vol Dubaï → New York** : une carte animée montre le trajet, puis zoome sur les États-Unis et sur New York pour la localiser. Le chronomètre démarre au décollage (45 minutes pour rendre le rapport).
4. **Plan** : une vue **3D** de New York (ou un plan 2D) avec 11 lieux à visiter dans l'ordre de son choix. On y voit les cinq arrondissements (Manhattan, Bronx, Queens, Brooklyn, Staten Island), les grands ponts et les tunnels vers le New Jersey.
5. **Lieux** : pour chacun, un document chiffré à lire, une question de compréhension, puis le classement du lieu dans le schéma « ville mondiale » (population, transports, centre financier et tertiaire).
6. **Jeu du taxi** : pause jeu en bonus.
7. **Rapport** : l'élève construit une note argumentée pour la PDG en suivant le plan du schéma, avec une limite.

## Utiliser le jeu

C'est un site statique : il suffit d'ouvrir `index.html` dans un navigateur, ou de publier le dépôt avec GitHub Pages (Settings → Pages → branche `main`, dossier racine).

La vue 3D utilise [Three.js](https://threejs.org/) (r128) et la carte du vol [D3](https://d3js.org/), chargés depuis un CDN : une connexion Internet est nécessaire. Si la 3D n'est pas disponible sur l'appareil, le plan 2D s'affiche automatiquement.

La progression de l'élève est enregistrée dans le navigateur (localStorage).

## Fichiers

- `index.html` : tout le jeu (HTML, CSS, JavaScript)
- `img/` : photos des lieux et schéma de la classe
- `data/geo.js` : fonds de carte du monde et des États-Unis ([Natural Earth](https://www.naturalearthdata.com/) via world-atlas et us-atlas)

## Crédits

- Documents recomposés à partir de sources publiques (2024-2026), citées sous chaque document dans le jeu.
- Photos : Wikimedia Commons, auteurs et licences indiqués sous chaque photo dans le jeu.
- Personnage et entreprise fictifs, créés pour le jeu.
- Plan schématique : JFK et Newark sont figurés hors échelle.
