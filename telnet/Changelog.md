# 20/01/2020 

- Passage du délai en seconde (auparavant en milliseconde)
- Valeur par défaut du délai à 3 secondes (si champ vide)
- Modification de la fonction servant à gérer le délai
- Modification du type de lecture du retour des commandes (stop la lecture si fin de ligne \n \r ou \0) 

# 03/07/2019

- Correction du délai (x1000 dans le code car en microsecondes)
- Ajout d'un délai par défaut dès la connexion pour attendre un message d'accueil si présent avant envoi de la commande

# 02/07/2019

- Correction de la validation du champ délai

# 01/07/2019

- Ajout de la prise en charge d'un login/mot de passe et délai

# 30/06/2019

- Ménage dans la solutiton (suppression des fichiers et des lignes de codes inutiles)
- Ajout de la documentation
- Préparation pour traduction
- Passage du plugin de la catégorie Programmation à Communication

# 09/06/2019

- Publication de la 1er version du plugin
- Possibilité de créer un équipement simple avec adresse IP et Port de communication telnet (sans login/mot de passe)
- Possibilité de créer des commandes Telnet
