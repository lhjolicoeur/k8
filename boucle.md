# boucle avancer-arreter

## Étape 1

Ajoute l'extension k8.

## Étape 2

Supprime le bloc ``||basic:toujours||``.

## Étape 3

Ajoute le bloc ``||loops:répéter||`` dans le bloc ``||basic:au démarrage||``.

Ajuste le nombre de répétitions à 5. 

## Étape 3

Ajoute le bloc ``||basic:montrer LEDs||`` dans le bloc ``||loops:répéter||``.

Dessine une flèche vers le bas dans le bloc ``||basic:montrer LEDs||``.

## Étape 4

Ajoute le bloc ``||motion:conduire tout droit vitesse : 0||`` sous le bloc ``||loops:répéter||``.

Ajuster la vitesse à 50. 

## Étape 5

Ajoute le bloc ``||basic:montrer LEDs||``" sous le bloc ``||motion:conduire tout droit vitesse : 0||``.

Dessine un "X" dans le bloc ``||basic:montrer LEDs||``. 

## Étape 6

Ajoute le bloc ``||motion:arrêter les moteurs||`` après le bloc ``||basic:montrer LEDs||``. 

## Étape 7

Télécharge le programme dans le micro:bit et teste le programme!