<h1>Cahier de suivi du projet de Benoit ATHIAS</h1>


Trio formé avec Coromines Damien et Touret Charles pour le projet Arduino portant sur le thème d'un jardin connecté.

-------------------------------------------------------------------------------------------
<ul>
<li> Séance du 20 Décembre 2017 </li>
</ul>
Création du groupe et confrontation d'idées autour du projet.


-------------------------------------------------------------------------------------------
<ul>
<li> Séance du 12 Janvier 2018 </li>
</ul>
Listage du matériel nécessaire et de leur utilité dans le projet.
<br>
Dessin papier réalisé pour la structure de la boite contenant tout notre matériel.
<br>
Début de la formation de la boite de manière "réelle" grâce à la future découpe et au future collage d'une planche en PVC.
<br>
Début présentation Powerpoint


-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 19 Janvier 2018 </li>

</ul>
Assemblage et collage de planche PVC donnant une idée de la structure de la boite.
<br>
Continuation de la présentation Powerpoint.


-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 23 Janvier 2018 </li>
</ul>
Présentation orale de notre projet.
<br>
Codage de la pompe.

-------------------------------------------------------------------------------------------

<ul>
<li> Sénce du 6 Février 2018 </li>
</ul>
Compréhension et codage du capteur d'humidité.

-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 22 Février 2018 </li>
</ul>
Complémentation du code des capteurs d'humidités.
<br>
Réception de la puce UNL2803 TOSHIBA permettant de protéger l'arduino lors de la connexion entre cette dernière et les pompes.
<br>

-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 15 Mars 2018 </li>
</ul>
Tentative de compréhension de l'UNL2803 TOSHIBA via datasheet et cablage de cette dernière.
<br>
Toutefois, de grandes difficultés ont été rencontrées durant cette séance.
<br>
En effet, bien qu'on ait compris que l'ULN soit constitué d'une série de LED qui se bloquent dans un sens, protégeant l'arduino dans notre cas, des difficultés pour cabler ce dernier ont été rencontrés.


-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 27 Mars 2018 </li>
</ul>
Utilisation de l'UNL2803 enfin comprise.
<br>
Début présentation Powerpoint.
<br>

-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 4 Avril 2018 </li>
/</ul>
Reliage du montage de l'UNL2803 avec l'arduino et mise en place puis téléversement du code pour gérer les pompes avec l'UNL2803.
<br>

-------------------------------------------------------------------------------------------


<ul>
<li> Séance du 17 Avril 2018 </li>
</ul>
Soudage de la rampe de l'aide de telle sorte à avoir un câble relier à la borne d'alimentation 12V et un autre câble relié aux trois autres bornes, caractérisant la masse, pour obtenir une lumière blanche par additivité des ondes lumineuses rouges, vertes et bleues.
<br>
Obtention du module Bluetooth HC06 et début de son initialisation. Ce module permettra de commander certains paramètres via notre smartphone android.
<br>

-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 2 Mai 2018 </li>
</ul>
Récupération des valeurs (entre 0 et 1023) d'un des capteurs d'humidité sous forme d'un tableau en fonction du temps de mise en marche grâce à l'application Electronics Bluetooth.
<br>
Sur cet même application, création d'un panel permettant d'afficher le taux d'humidité (entre 0 et 100%) de ce même capteur.

-------------------------------------------------------------------------------------------

<ul>
<li> Hors Séance : 4 Mai 2018 </li>
</ul>
J'ai essayé de commander une des pompes via bluetooth mais sans succès.
<br>
J'ai donc pensé que l'utilisation du bluetooth de ma part n'était pas bonne pour ce cas, je l'ai donc arrêté pour essayer maintenant de commander la pompe avec l'arduino uniquement comme auparavant. Toutefois, après des montages et des remontages je n'ai pas réussi à la commander. En effet, la pompe marchait tout le temps, quel que soit l'état envoyé par l'arduino...
<br>
Comme mes montages étaient correct et que cela n'a pas fonctionné, Damien a émis l'hypothèse que notre ULN2803 était grillé. Ainsi lors de la prochaine séance je le vérifierai.

-------------------------------------------------------------------------------------------

<ul>
<li> Séance du 7 Mai 2018 </li>
</ul>
A travers cette séance nous avons émis l'hypothèse que notre ULN2803 ne marchait pas bien, dû aux résultats obtenu lors des câblages du 4 Mai.
<br>
Après avoir passé notre ULN à l'oscilloscope et au voltmètre nous en avons déduit qu'il était grillé. Nous avons donc fait l'acquisition d'un nouveau.
<br>
Cet ULN marche correctement, nous pouvons ainsi commander les pompes avec l'arduino par bluetooth.
  
-------------------------------------------------------------------------------------------



<ul>
<li> Hors Séance : 18 Mai 2018 </li>
</ul>
Mise en commun des composants électroniques sur une carte arduino et en utilisant une breadboard.
<br>
Début de l'édition de l'application bluetooth. Cette dernière permettra à distance de commander les pompes, les LED et de voir le pourcentage d'humidité.
<br>
Nous avons rencontré un problème à travers cette séance, nous n'avons pas réussi à contrôler les deux pompes et la rampe de LED simultanément. En effet, une fois une pompe mise sous tension, la deuxième pompe n'arrivait pas à s'allumer et les LED s'affichaient rouge, couleur nécessitant le moins d'énergie. Ce problème n'a pas pu être réglé durant cette séance.
  
-------------------------------------------------------------------------------------------



<ul>
<li> Hors Séance : 25 Mai 2018 </li>
</ul>
Problème rencontré lors de la séance précédente résolu ! Il semblerait que c'était une erreur dans notre code. Après avoir séparé les deux pompes et la rampe de LED dans un fichier vierge Arduino pour quelles soient traitées indépendemment des autres composants électroniques, ces dernières se sont finalement mis sous tension.
<br>
Mise en commun des codes (capteur d'humidité, module RCT, bluetooth, pompe, LED).
<br>
Finalisation de l'édition de l'application. Nous avons ainsi 3 pages permettant à distance de commander les pompes, les LED et de voir le pourcentage d'humidité.
  
-------------------------------------------------------------------------------------------


<ul>
<li> Hors Séance : 30 Mai 2018 </li>
</ul>
Mise en place de terre et plantes dans notre boite.
<br>
Rassemblement des composants électronique dans la boite.
<br>
La boite n'étant pas étanche, nous avons du placer un sachet congélation dans le compartiment de l'eau pour ne pas qu'elle s'y répandre en dehors.
<br>
Test de notre projet qui fut un succes.
<br>
Prise d'une vidéo du fonctionnement de notre projet, si jamais il ne marchait pas le jour de l'oral et pour souvenir.

-------------------------------------------------------------------------------------------

<ul>
<li> Séance : 31 Mai 2018 </li>
</ul>
Vérification de la validité et du bon fonctionnement de notre projet.
<br>
Présentation orale de notre projet.

-------------------------------------------------------------------------------------------

-------------------------------------------------------------------------------------------

<h2>Conclusion</h2>
<p>Ce projet fut très enrichissant tant d'un point de vu électronique en étant confronté à de nouveaux composants électroniques, qu'informatique par le fait de coder sur un systeme embarqué. 
  <br> De plus, le fait d'être en autonomie est un vrai plus. En effet, cela  a permis de façonner notre projet tout en travaillant en équipe. *
<br>Concernant les problèmes rencontrés, certains ont été dur à résoudre car nous n'avons pas forcément le recul nécessaire pour savoir comment les aborder directement.</p>


-------------------------------------------------------------------------------------------

