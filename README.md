# Thermocouple_aquisition_sans_fil
Le but du projet est de créer un thermocouple ayant un moyen d’acquisition sans fil. Les données seront envoyées par protocole WIFI afin d'être affichées et enregistrées sur un ordinateur.

La structure de l'archive du projet est la suivante :

-Banque_images :
	Dossier comprenant des photos, captures d'écran... du produit et des tests

-Circuit_imprime :
	Dossier qui contient les fichiers EAGLE du circuit électronique et du routage du PCB,
	ainsi que les fichiers PDF associés

-Datasheets :
	Dossier contenant les datasheets de chaque composant utilisé : 
	ESP8266 (nodeMCU), MCP3301, MCP6002 et LM335Z

-Documents_produits :
	Vous trouverez dans ce dossier le document de cadrage, l'énoncé du projet,
	les diapositives des 2 jalons, le rapport du projet ainsi qu'un manuel d'utilisation pour le thermocouple

-Programmes :
	Ce dossier contient un sous dossier contenant le programme entré dans le microcontroleur ESP8266
	(serveur TCP) écrit en cpp dans l'IDE ARDUINO, un second sous dossier contenant un programme principal écrit en Python
	(script client TCP lancé sur un ordinateur) faisant appel à un second programme contenant certaines fonctions pour alléger
	le code et enfin un manuel d'utilisation en pdf appelé par le code. Un code C émulant la conversion de tension en température, 	prenant en compte la compensation de la soudure froide est également contenu dans ce dossier

-Modelisation_CAO_boitier :
	Dossier comprenant les conceptions 3D sur FUSION 360 de chacun des composants du boitier,
	ainsi que la modélisation du produit


JAOUANNE Lilian & GARCON Bastian
