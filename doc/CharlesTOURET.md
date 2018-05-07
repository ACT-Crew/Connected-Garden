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




