# WIP

- Passage de la modal des favoris sur une modal de même type que celles de jeedom (évite les interférences avec les css du core de jeedom)
- Ménage dans la solution (suppression des dossiers inutiles)
- Ajout de la traduction en_US (90%)

# 16/06/2019

- Correction de l'affichage de la modal des favoris lorsque le widget est utilisé dans un design jeedom.
- Ajout de la récupération du modèle dans la configuration de l'équipement
- Prise en compte du modèle pour les deux commandes annexes loudness et luminosité (nécéssite de récupérer à nouveau le PID avec le bouton dédié dans la configuration de l'équipement)
- Divers ajustements graphiques

# 15/06/2019

- Correction pour éviter le lancement en double de la connexion telnet lors du lancement du daemon
- Ajout de la possibilité de renseigner son compte HEOS dans la configuration de l'équipement (login + mot de passe, nécessaire pour l'utilisation de certaines fonctions comme les Favoris HEOS)
- Ajout de la possibilité de consulter et de lancer un favoris Heos (icône étoile en haut à droite du widget)

# 12/06/2019

- Correction du widget pour prise en compte de la couleur de fond en fonction de la catégorie choisie pour l'équipement
- Refresh auto du widget à l'enregistrement de l'équipement

# 11/06/2019

- Ajout de la récupération auto du PID du player à l'adresse IP renseignée
- Définition des valeurs du widget par défaut à l'enregistrement de l'équipement (titre, album, artiste, image)

# 10/06/2019

- Alignement des textes à gauche (titre, album, artiste)
- Ajout de la documentation
- Correction de la gestion de l'allumage ou non de l'afficheur (le toogle était inactif si la valeur choisie par défaut dans la configuration de l'équipement était différente de 100%)
- Ajout d'un toogle pour activation/désactivation du loudness
- Sélection par défaut de l'image blanche et de la luminosité à 25%

# 09/06/2019

- Version initiale
