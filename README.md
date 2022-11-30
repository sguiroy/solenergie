# Solenergie

Solenergie est un projet de plateforme de pilotage et d'aide à la décision en matière de transition énergétique, plus particuliérement la transition vers l'énergie solaire.

Il n'aura échappé à personne que la France vit des jours sombres sur plusieurs plans, et pas seulement parce que l'hiver vient et les nuits se rallongent. Sur le plan énergétique tout particulièrement, alors que le parc nucléaire tricolore est en cette fin d'année 2022 plus au ralenti que jamais (plus d'une vingtaine de réacteurs à l'arrêt fin octobre), l'inflation record est aussi venue contribuer à l'alourdissement significatif de la facture énergétique des français.

Face aux défis posés dans le présent et à l'éventualité que la situation continue de s'empirer (températures continuant à diminuer, coupures électriques de délestage probables au plus fort de  l'hiver, disparition prochaine du bouclier tarifaire sur l'énergie mis en place par le gouvernement, comme la ristourne à la pompe), il ne reste alors plus guerre que peu d'options : se résigner et la jouer aussi 'sobre' que possible dans sa consommation, ou bien trouver des sources d'énergie alternatives. 

Seulement voilà, une fois la résolution prise d'étudier des sources alternatives d'énergie, reste encore la tâche difficiel de choisir la bonne : c'est là que Solenergie entre en jeu

## Descriptif de l'outil

Dans un premier temps, je prévois de munir l'outil d'une sorte de 'calculette', similaire en son fonctionnment à la page https://www.salaire-brut-en-net.fr, mais qui serve cette fois à déterminer l'horizon de rentabilité le plus fiable possible selon les caractéristiques de l'installation photovoltaïque souhaitée.
Cet outil présenterait donc un intérêt a la fois pour les consommateurs, qui pourront y trouver une information objective, non-biaisée par les intérêts de commerciaux qui chercheraient à vendre des panneaux à tout prix; mais aussi pour d'autres acteurs du secteur tels aue les commerciaux pour leur permettre d'appuyer leur argumentaire de vente dans les régions les plus rentables, par exemple, ou alors suggérer d'autres choix de substitut lorsque la solution photovoltaïque ne convient pas aux besoins de l'utilisateur.

Dans le cadre du Yday, je souhaiterais développer l'outil rudimentaire de la 'calculatrice', puis incorporer des visuels pertinents pour illutrer la donnée purement numérique. Les langages utilisés dans ce cadre seraietn, notamment, Python pour la aprtie de traitement de données, HTML, CSS pour l'interface utilisateur sur une page web, la bibliothèque Flask pour connecter le tout, et enfin le langage d3.js pour générer les graphes.

Dans un second temps, je souhaiterais travailler sur ce projet dans le cadre du projet de fin d'année, et peut-etre tenter d'heberger le site et/ou une appli pour permettre l'utilisation par le plus grand nombre, l'amelioration des visuels web et graphes et, si tout va pour le mieux, l'integration de nouveau(x) volet(s) pour de nouveaux types d'energie (chauffage au bois, hydroelectricite, eolien, chauffage au bois, centrale a charbon ...)

## Donnees a utiliser pour constituer l'outil

 - Dans un premier temps, les donnees meteofrance, qui ne sont pas vraiment de l'opendata (les axes d'interet avec une granularite sur l'ensemble du territoire suffisante sur plusieurs annees sont disponibles sur le site, mais contre retribution genereuse, sauf en cas de signature de licence.
 - Dans un second temps, les donnees Enedis fournissant de maniere totalement ouverte, pour chaque adresse de France, la consommation annuelle en energie de ladite adresse.
 - Potentiellement d'autres donnees d'interet ... 
