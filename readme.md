# Python script for Metashape pro

This scrpt are supported to be used in Metashape Pro v1.6.x

Automatically load photos by choosen polygon 

**Version 0.0.1**

# Technologies
- python 3.5
# Requirements 

in python folder in metashape install folder install modules :
```bash
python -m pip install pillow
```
pour exécuter le script il faut installer des bibliothèques tiers:
  - Shapely  : utiliser le fichier whl téléchargeable sur https://www.lfd.uci.edu/~gohlke/pythonlibs/#shapely ou whl fourni avec le script pour la x64 python 3.5 / metashape 1.6.x
  - pillow
  - pyshp

Dans la CMD en tant que administrateur: 

 -   cd "C:\Program Files\Agisoft\Metashape Pro\python"
 -   python -m pip install pillow
 -   python -m pip install pyshp
 -   python -m pip install "chemin vers\Shapely-1.6.4.post2-cp35-cp35m-win_amd64.whl"

#utilisation

 - Créer un polygone format un SHP en lambert zone 1 préférable avec un buffer de quelques mètres.
 - Excuser le script.
 - Sélectionner le polygone SHP 
 - Sélectionner le dossier des photos par exemple le dossier "DAR" , le script va chercher aussi les sous dossier.
 # pour 61000 photos va prendre 10 a 12 min de recherche .

 o rad 3liya wach khdam wela la 
  