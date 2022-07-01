# ROS_NOTE_TP1

## Instruction

Pour installer le répertoire il suffit de cloner le projet sur Linux en faisant un :

```sh
git clone (lien du projet)
```

Le chemin du package marker_visualizer est dans le dossier source du dossier catkin_ws

- Pour y acceder il suffit de faire faire la commmande suivante dans un terminal:
```sh
cd catkin_ws/src/
```

Les trois noeud publish_marker.py, publish_marker_array.py et random_walk.py  sont dans le dossier srv du package marker_visualizer

- Pour y acceder il suffit de faire la commmande suivante dans un terminal:
```sh
cd catkin_ws/src/marker_visualizer/src
```

## Afficher un Sphere

En assumant qu'on est dans le répertoire catkin_ws, on fait la commande suivante pour source le fichier publish_marker.py
```sh
source devel/setup.bash
```

Puis on fait la commande suivante
```sh
rviz
```
#### Sur rviz 

- On appuie sur le bouton Add qui il se trouve au bas de l'écran

- On choisit by_topic

- Ensuite on choisit notre script python publish_marker.py

- Et le sphere apparaît

## Afficher un carré

En assumant qu'on est dans le répertoire catkin_ws, on fait la commande suivante pour source le fichier publish_marker_array.py
```sh
source devel/setup.bash
```

Puis on fait la commande suivante
```sh
rviz
```
#### Sur rviz 

- On appuie sur le bouton Add qui il se trouve au bas de l'écran

- On choisit by_topic

- Ensuite on choisit notre script python publish_marker_marker.py

- Et le carré apparaît

## Random walk

En assumant qu'on est dans le répertoire catkin_ws, on fait la commande suivante pour source le fichier random_walk.py
```sh
source devel/setup.bash
```

Puis on fait la commande suivante
```sh
rviz
```
#### Sur rviz 

- On appuie sur le bouton Add qui il se trouve au bas de l'écran

- On choisit by_topic

- Ensuite on choisit notre script python random_walk.py



