# registration-solver

### Auteur :

:student: Maël GODARD <mael.godard@ensta-bretagne.org> (FISE 2023)
 
### Description : 

Ce repo traite de la résolution du problème de registration dans le cadre 2D avec rotation connue.

### Git Structure :

* :file_folder: ./imgs : **dossier contenant les images du projet**
* :file_folder: ./src : **dossier contenant les programmes du projet**
* :spiral_notepad: README.md

### Technologies :

* C++
* Ubuntu 20.04 LTS
* Codac
* CMake

### Travail éffectué :

* Création d'un repo Github
* Import manuel de mesures LIDAR
* Projection/déplacement des mesures LIDAR
* Comparaison des mesures pour obtention d'un similitude
* Mise en place d'un algorithme de résolution du problème de registration 
* Test et validation avec un seuil arbitraire

### Travail en cours : 

* Seuil "mobile" i.e. recherche de seuil optimal (type descente de gradient)

### Setup :

Vérifier votre version de CMake


* Installer vibes
```bash
sudo apt-get install qt5-default libqt5svg5-dev qtbase5-dev cmake git
git clone https://github.com/ENSTABretagneRobotics/VIBES
cd VIBES/viewer ; mkdir build ; cd build ; cmake .. ; sudo make install
```

<ins>Installer le viewer vibes :</ins>
* avec le [tutoriel officiel](https://enstabretagnerobotics.github.io/VIBES/sphinx/html/quickstart.html#install)
* à partir de la page *Releases* du [projet Github](https://github.com/ENSTABretagneRobotics/VIBES/releases) (plusieurs plateformes disponible)

* vibes


<ins>Installer codac :</ins>
* avec le [tutoriel officiel](http://codac.io/install/01-installation-full-linux.html)

### Utilisation :


1. Se déplacer dans le dossier
2. Compiler
```bash
mkdir build && cd build && cmake .. && make
```

<ins>Note:</ins></br>
Par la suite, il suffira de make

3. Lancer Vibes

4. Lancer l'executable
```bash
./codac_basics_01
```

