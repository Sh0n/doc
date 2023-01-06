# Changelog WeConnect

_Si aucune information n'est affichée ici alors qu'une nouvelle mise à jour est disponible, cela signifit qu'aucune modification notable n'a été apportée sur le plugin_

## 06/01/2023
- Ajout configuration pour l'Arteon (merci Skot2512)

## 21/12/2022
- Ajout configuration pour la Passat GTE (merci guigeek)
- Correction de l'autonomie max par défaut pour la e-Golf (modifiable si besoin dans les options de la commande)

## 20/12/2022
- Ajout configuration pour la e-up! (merci enfrafer)

## 19/12/2022
- Ajout configuration pour la e-Golf (merci pplotton)
- Ajout d'une nouvelle commande info "Localisation" (latitude,longitude) pour faciliter l'utilisation dans d'autres plugins comme geotrav par exemple. Attention, il s'agit d'une simple concaténation des commandes latitude et longitude. Elles doivent donc être activées et actualisées pour que celle-ci fonctionne.

## 25/11/2022
- Ajout configuration pour Passat Variant GTE (merci à ChristopheHD)
- Ajout configuration pour L'ID.3 (copie configuration de l'ID.4)
- Ajout configuration pour le Transporter (merci pilou226)
- Ajout configuration pour le Tiguan (merci stefan62231)
- Ajout configuration pour la Polo (merci pesupiot)
 
- Ajout de l'état des phares (droite & gauche) pour Golf GTE, ID.3 et ID.4
- Ajout de la captation du modèle de véhicule dans le nom de celui-ci lorsque la commande /model n'est pas disponible (cas du transporter, voir doc)

## 24/11/2022

- Correction d'une anomalie qui entrainait la non prise en compte de la couleur de la catégorie sur la barre de titre de la tuile sur le dashboard. La suppression puis recréation des équipements concernés semble obligatoire pour régler définitivement le problème

## 23/11/2022

- Modification du process de génération du fichier NETRC
- Ajout de complément d'information dans la configuration du plugin
- Autres corrections mineures

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
