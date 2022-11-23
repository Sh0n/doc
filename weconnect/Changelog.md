## 23/11/2022

- Modification du process de génération du fichier NETRC
- Ajout de complément d'information dans la configuration du plugin

## 20/11/2022

- Rework complet du plugin pour se baser sur la nouvelle librairie weconnect-cli

## 13/11/2020

- Correction d'une erreur javascript dans le template image (provoquait une erreur sur le dashboard surtout visible en V4, désactiver/réactiverle plugin pour une prise en compte de la correction)

## 04/05/2020

- Suppression du daemon automatique au profit des crons. Il est désormais possible de choisir le délai de rafraichissement des données entre 1, 5, 10, 15 et 30 minutes ou 1 heure (à paramétrer dans la configuration du plugin)
- Ajout d'une nouvelle action rafraishissement pour faire un refresh manuel des données (dans un scénario par exemple)

### ATTENTION : dans certains cas, le passage à cette nouvelle version nécessite la désinstallation du plugin puis réinstallation (désolé pour le désagrément)

## 03/05/2020

- Ajout des informations concernant les vitres, coffre et toit ouvrant
- Ajout des informations concernant le verrouillage des portes
- Ajout de l'affichage de la photo du véhicule (commande info Image URL)
- Ajout de la possibilité d'afficher sur une carte Google Maps la localisation du véhicule. Attention, pour cette commande, il faut que votre véhicule soit compatible et que vous ayez renseigné une Clé Google Maps API dans la configuration du plugin
- Passage des informations de type binaire en template par défaut line (core)
- Correction de la gestion de l'information concernant la climatisation

## 23/01/2020

- Correction des images pour le market
- Correction de l'affichage du formulaire de saisie des identifiants We-Connect

## 01/01/2020

- Première version stable
