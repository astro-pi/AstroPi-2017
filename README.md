# AstroPi-2017
Detection code, made by MauriacSpaceCoders, AstroPi winners !

Code réalisé par les élèves de l'Enseignement d'Exploration ICN, classe de Seconde 10, Lycée François Mauriac, Bordeaux (France).

Fonctionnalités du code :
- détection de la présence d'un astronaute dans le laboratoire Columbus, par monitoring de l'humidité.
- détection du survol de la France ou de l'Italie.
- animations synchronisées avec l'heure de lever et de coucher du soleil à Rome.
- animations synchronisées avec les jours d'anniversaire de chacun des astronautes de l'ISS présents à bord.



******* PyEphem *************

Le code principal main.py nécessite l'installation de la librairie PyEphem disponible ici :

https://pypi.python.org/pypi/pyephem

Notre code utilisait PyEphem pour Python 2.7 mais devrait aussi fonctionner avec Python 3.


******** Fichiers annexes ********

les fichiers suivants doivent se retrouver dans le même dossier que le code principal main.py :

- animations.py (répertoire de toutes les animations affichées sur l'AstroPi)
- rome.csv (heures des levers/couchers du Soleil à Rome pour l'année 2017


******** Fonctionnement du code principal main.py ******

- le code fonctionne sans interruption pendant 2h (7200 secondes)
- Le fichier de données data_FM.csv se trouve dans le dossier courant à l'issue de l'exécution du programme.
