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
<h6>Séance dédié au pilotage d'une des pompes via bluetooth</h6>
<br>
A travers cette séance nous avons émis l'hypothèse que notre ULN2803 ne marchait pas bien, dû aux résultats obtenu lors des câblages du 4 Mai.
<br>
Après avoir passé notre ULN à l'oscilloscope et au voltmètre nous en avons déduit qu'il était grillé. Nous avons donc fait l'acquisition d'un nouveau.
<br>
Cet ULN marche correctement, nous pouvons ainsi commander les pompes avec l'arduino par bluetooth.
  
-------------------------------------------------------------------------------------------

