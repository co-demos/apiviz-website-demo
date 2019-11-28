Déploiement du site : [![Netlify Status](https://api.netlify.com/api/v1/badges/f5ff305b-52c1-4fb1-be79-17a7494705ac/deploy-status)](https://app.netlify.com/sites/apiviz-preprod-apcis-url-migration/deploys)


## INFORMATIONS / METHODOLOGIE
Ce repo contiendra l'ensemble des éléments "custom" propres au site de démo Apiviz, indépendamment du code source d'Apiviz. Ceci permettra une meilleure flexibilité et coordination : 
- le chantier purement technique s'effectuera sur le repo ApiViz, dans le but d'en améliorer la généricité
- les contenus et documents de cadrage (maquette, charte graphique...) produits par chacun.e seront mis à jour sur ce repo
- les issues propres au contenus du site de démo Apiviz seront associées à [ce repo](https://github.com/co-demos/apiviz-website-demo/issues)
- les issues propres au développement d'ApiViz seront associées au [repo ApiViz](https://github.com/co-demos/ApiViz/issues)
- la vision générale de l'avancée du projet (gestion des sprints) sera visible et modifiable sur [le(s) projet(s) du repo](https://github.com/co-demos/apiviz-website-demo/projects)

## ORGANISATION DES DOSSIERS
Les dossiers sont organisés de la manière suivante : 

### contenus du site
- `/data`: fichiers CSV, XLS, liens vers points d'API (dans un fichier .MD ou .TXT)
- `/textes`: fichiers textes (édito, mot ministre, ...) au format .TXT ou .MD
- `/logos` : fichiers (images) des logos au format .PNG, .JPG, .SVG
- `/illustrations` : fichiers des illustrations/images (background ou foreground) au format .PNG, .JPG, .SVG
- `/photos` : fichiers des photos/images au format .PNG, .JPG, .SVG
- `/pages-html`: fichiers HTML qui seront pointés par l'instance d'Apiviz 

### éléments de cadrage et de synthèse
- `/graphisme` : fichiers des différents éléments constituant la charte graphique (maquette, charte graphique, ...)
- `/documentation` : fichiers de synthèse et de documentation (liste livrables, recommandations UI-UX, recommandations tech, médiation...) au format .PDF, .DOC, .TXT, .MD ...


## NOTE METHODOLOGIQUE
Merci de donner des noms explicites aux fichiers que vous modifierez/ajouterez, ainsi que bien les ajouter dans le dossier qui leur correspond le mieux
