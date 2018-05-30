# SEANCE 1 (20 D2CEMBRE): Membres du groupe: Athias Benoit, Coromines Damien et moi-même.
Durant la première séance, nous avons définit notre projet qui consiste à innover un jardin connecté avec 2 ou 3 plantes 
qui sera automatisé et que l'on pourra controler à distance.
Nous avons déja choisi quelques pistes de développement.

# SEANCE 2 (12 JANVIER 2018): 
Nous avons commencé la réalisation de la boite avec Damien en PVC. Il nous reste à élaborer notre planning

# SEANCE 3 (19 JANVIER 2018): 
Découpe du PVC avec Damien, Assemblage de toutes les plaques en les collant, commencement du planning et création du compte GitHub.

# SEANCE 4 (23 JANVIER 2018): 
1ere présentation de notre projet puis directement après cette présentation, nous avons testé le fonctionnement des pompes avec quelques codes Arduino élaborés auparavant.

# SEANCE 5 (6 FEVRIER): 
Nous avons développé un code pour le fonctionnement des capteurs puis apres nous avons testé avec Benoit ces capteurs d'humidité ( de la terre ) dehors, ce qui a été un succès. Ensuite, M.Masson nous a donné une puce ULN2803 constituée de plusieurs transistors et LED qui se bloquent dans un seul sens pour empêcher l'Arduino de "cramer" car il est alimenté en 5V mais les moteurs des pompes en 12V.

# SEANCE 6 (22 FEVRIER): 
La pompe fonctionne très bien grâce à un montage (et l'aide de M. Jacquemod) qui contient entre autre un GBF de 12V et un autre de 5V qui imite l'alimentation de l'arduino. Il nous faut donc maintenant remplaçer le 5V par la carte arduino elle-même avec le code adéquat pour contrôler la vitesse et l'arret des pompes et de déterminer la bonne tension (comprise entre 5 et 12V pour gérer les moteurs).

# SEANCE 7 (15 MARS):
D'abord nous nous sommes documentés sur la "datasheet" de l'ULN2803 pour étudier comment la câbler. Puis nous avons fait le montage avec cette puce mais nous avons rencontrés de nombreuses difficultés (mauvais câblage, fil deffectueux) nous avons perdu pas mal de temps.

# SEANCE 8 (27 MARS):
Nous avons réussi à faire foncionner les pompes à une faible vitesse. M.Masson nous a donné un adaptateur 12V à brancher directement sur secteur 230V, c'est un moyen simple et efficace pour le bon fonctionnement des pompes. Puis nous avons regardé les présentations des autres groupes et avons commencé la nôtre.

# SEANCE 9 (4 Avril):
Nous avons inclu des trous dans les parois internes de la boîte
J'ai soudé les fils de connexion pour la rampe de LED ( masse GND et lumièer blanche (RGB)).

# SEANCE 10 (17 Avril):
J'ai soudé la rampe de LED (un câble est relé au 12V et l'autre pour la masse qui lie 3 couleurs RVB (Rouges Vertes Bleues), 
Nous avons récupéré le module Bluetooth HC06 et début de son initialisation qui va commander les paramètres via l'android.

# SEANCE 11 (2 MAI):
Etude des capteurs d'humidité avec la création d'un tableau en fonction du temps de mise en marche avec l'application Electronics Bluetooth.

# SEANCE SUPPLEMENTAIRE (4 MAI):
Nous sommes allé au FABLAB avec Damien pour la conception de la boîte. J'ai conceptionné la boite avec un logiciel CAO et ensuite utilisé la découpe laser afin d'obtenir toutes nos pièces de la boite. Puis on les a collés entre elles. Cette séance fût particulièrement interressante d'un point de vue informatique et mecanique.

# SEANCE 12 (7 Mai):
Durant cette séance, nous nous sommes rendu compte que l'ULN2803 avait un problème, il était tout simplement grillé. Nous en avons donc pris un nouveau.

# Depuis
Finalisation du montage et des codes

# Dernière Séance supplémentaire (30 Mai):
Finalisation de notre présentation orale. Nous avons testé en entier notre système: nous avons mis la terre et les plantes, pris une vidéo montrant tout le processus de notre projet. Egalement, nous avons fait en sorte de bien répartir notre circuit éléctronique dans nos différents compartiments.




