# Aléa

- Partenaire: Justori
- Etudiants: Brugiès Mélodie, Jéhanno Guillaume, Lozé Paul, Picosson Alexandre
- Technologie d'entrée: Capteurs mobiles
- Technologie de sortie: Sortie 2D vidéo projetée

# Le Fabularium

## Description

Le Fabularium est un endroit où l'on raconte des histoires. En lançant cette application vous serez plongé dans une histoire de Bali.

## Dépendances logicielles

* [Processing 3](https://processing.org/)
* [oscHook](https://play.google.com/store/apps/details?id=com.hollyhook.oscHook) : Application Android permettant de diffuser les informations obtenus par les capteurs du téléphone via le protocole OSC.

### Librairies

* [Processing Video](https://processing.org:8443/reference/libraries/video/index.html) : Permet la gestion des vidéos
* [Minim](http://code.compartmental.net/tools/minim/) : Gestion du son
* [Keystone](http://www.deadpixel.ca/keystone/) : Mapping des surfaces
* [oscP5](http://www.sojamo.de/libraries/oscP5/) : Traitement du protocole OSC.


## Instructions de génération de l'application

1.Executer le programme avec processing.

## Instructions d'exécution

1. Charger la configuration avec la touche 'L'.
  - On peut recalibrer les paneaux avec la touche 'C'
2. Lancer l'application Android.
  1. Regler l'IP de l'application sur l'IP et le port de l'ordinateur executant le programme.
  2. Activer la transmission des données de la boussole.
3. Fixer le téléphone Android.
4. Faite bouger le téléphone pour lancer l'histoire.

## Note

L'histoire raconté se reset automatiquement au bout de plusieurs secondes d'inactivité.
*Certains fichiers ressources n'ont pas été inclu pour des raisons de taille.*
Il est en effet nécessaire d'inclure des vidéo au format mp4, les vidéo en question doivent avoir une taille de 600/600px.
Il est possible de modifier les noms de fichiers vidéo ou des images au sein du fichier sketch_alea.pde
