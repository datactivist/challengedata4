# Carnet de bord de l'ouverture des données de Marseille

par B.N, FENIGER	Claire, F.C, L.J, M.Pierre, S.Lyna, W-B.Paul-Emile

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/Marseille.jpg)


**Introduction - “Des bateaux j’en ai pris beaucoup…”**


Au moment de quitter le port, nous partons avec un équipage soudé. Nous nous connaissons déjà très bien et l’état d’esprit est bon. Le ton est malicieux, des blagues fusent. Nous sommes 7, venant en majorité de la spécialité droit et action publique (N.B, J.L, Paul-Emile, Pierre et C.F). Lyna et Claire, respectivement en spécialité Économie-Finance et Culture-Communication, apportent un regard différent qui rend notre approche pluridisciplinaire. Quant au Challenge, entre les retours contrastés des anciens élèves et le flou sur le contenu pratique, nous sommes dans l'expectative. Malgré tout, nous sommes contents d’aider une collectivité plutôt qu’une entreprise privée et de nous lancer dans un travail bien plus concret que nos cours classiques. 


A l’annonce de notre ville partenaire, nous sommes étonnés. C’est la deuxième ville de France et sa réputation la précède. Nous sommes étonnés d’aider une collectivité si importante qui devrait avoir les capacités d’exploiter elle-même ses données. Mais, il est de notoriété publique que la ville des Bouches-du-Rhône souffre dans de nombreux domaines d’un manque de moyens, comme en témoigne le plan d’aide spéciale débloqué récemment par le gouvernement. De plus, la récente bascule politique de l'exécutif Marseillais, nous apparaît comme une potentielle opportunité. En effet, le Printemps Marseillais semble vouloir prioriser la transparence, l’écologie et le social: de nombreux domaines dans lequel l’open data peut être utile.

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille1.png)     


## JOUR 1 – DIAGNOSTIC - Larguer les amarres



La ville de Marseille est une très grande ville et lorsque nous nous attelons au diagnostic vers 9h30, après la réunion, nous avons un peu peur de la quantité de données qui risque de se trouver face à nous. Après un bref temps de prise en main de Gather, du Canva ainsi que des différentes bases de données sur la ville de Marseille, N.B. contacte par téléphone notre interlocutrice, chef du projet data de Marseille afin de prévoir un rendez vous l’après-midi à 15h. La prise de contact dès le premier appel est plutôt facile notamment grâce  à l’attention de notre interlocutrice, ce qui nous rassure un peu sur la semaine à venir!


Jusqu’à la fin de la matinée nous cherchons à nous approprier les outils à notre disposition tels que le Canva de présentation, les données de data.gouv, celles de la ville de Marseille, les différentes manières dont les données sont traitées en général afin de mieux comprendre ce en quoi peut de consister notre semaine. La très faible quantité de ces données est frappante. Pour en prendre la mesure nous comparons avec d’autres villes : Paris met à disposition 315 jeux de données, la métropole de Lille 496 quand la ville de Marseille n’en propose que 41. Ce ratio d’un facteur 10 est vraiment conséquent, d’autant plus que nous remarquons que certains de ces 41 jeux de données semblent lacunaires ou du moins gagneraient à être plus complets (nous reviendrons dessus). 


L’intervention de notre référent Allyson en début d’après midi confirme les grandes idées que nous avions dégagées le matin : le retard de la ville de Marseille dans l’ouverture de ces données est conséquent, tant quantitativement (le nombre de base de données ouvertes) que qualitativement (le contenu de certaines de ces bases de données). Il nous a aussi aiguillés sur les bases de données qui pourraient attirer notre attention. En attendant le rendez vous avec notre interlocutrice nous nous sommes répartis le travail de “défrichage” de celles-ci :

* J.L. et P.M. se penchent sur les bases de données sur les bases nautiques et les plages : celles-ci étaient accessibles sur data.gouv mais aussi sur le site de Marseille. 
* CF1 se charge des données relatives aux espaces sportifs en accès libre. 
* L.S et P-E.W-B étudient les données relatives aux marchés de la ville. Des anomalies sont remarquées. Une possible ouverture de ces données est envisagée. 
* CF2 rédige l’introduction de notre carnet de bord
* N.B. prépare l’appel prévu avec notre interlocutrice et essaye de comprendre les questions 

Nous nous sommes rendu compte que dans certains cas, les données sur un même sujet étaient disponibles sur plusieurs plateformes mais en ne contenant pas exactement les mêmes catégories de données, il y a un manque d’harmonisation.


A 15h nous avons (non sans mal) pu commencer notre réunion avec nos interlocutrices. N.B. leur présente le questionnaire, P.M. remplit les réponses et le reste du groupe intervient selon les besoins (et ce qu’ils avaient vu précédemment). Le questionnaire place Marseille au palier 4 en terme de maturité open data. C’est un niveau assez élevé, mais le questionnaire est prévu pour des collectivités de toute taille : le niveau est élevé, mais pas autant que nous pourrions l’attendre de la deuxième ville du pays. 


Nos interlocutrices de la ville de Marseille nous donnent deux domaines dans lesquels elles nous attendent : 

* Le premier est celui de l'État Civil : ce qui touche aux naissances, mariages et décès. Une attention particulière est demandée quant aux prénoms des nouveaux nés chaque année. 
* Le second porte sur les bibliothèques : les types d’abonnements, le nombre d’emprunts ou encore les titres les plus empruntés par exemple. 

D’un côté nous nous concentrons donc sur les deux directions données par nos interlocutrices. Principalement, De l’autre, nous nous gardons en fonction de critères comme la quantité, l’accessibilité ou la facilité de traitement des données sur ces domaines la possibilité de proposer à notre interlocutrice de traiter certains des cas que nous avons vus plus tôt dans la journée. 


Avec l’appel et la demande relativement précise de la ville de Marseille la wishlist est relativement simple à formuler :

1. Traiter les bases de données État Civil avec les naissances, mariages, décès et prénoms. Pour cela nous identifions un enjeu majeur qui est de trouver un bon schéma pour exploiter ces (nombreuses) données.
2. Traiter la base de données de la (des) bibliothèque(s) minicipale(s). Nous faisons face à des données parfois un peu âgées, et pas uniformisées. L’enjeu majeur identifié est alors le formatage de ces données. 

**Résumé :**


<table>
  <tr>
   <td>Réussite ou casse-tête ?
   </td>
   <td>Explication / Citation
   </td>
  </tr>
  <tr>
   <td>taille de la ville
   </td>
   <td>On s’attendait pas forcément à une aussi grosse ville
   </td>
  </tr>
  <tr>
   <td>prise de contact
   </td>
   <td>Super facile, ça met en confiance et nous motive ! 
   </td>
  </tr>
  <tr>
   <td>quantité de données
   </td>
   <td>Peu de publications et de valorisation des données de Marseille, or il y a un grand stock de données inexploité  => besoin d’effectuer un tri de sorte à les rendre utilisables ! 
   </td>
  </tr>
  <tr>
   <td>Coup de main de Alysson
   </td>
   <td>Nous a proposé des sujets sur lesquels on pouvait se renseigner, rassembler des données de plusieurs types de sourc
   </td>
  </tr>
  <tr>
   <td>diagnostic du level de maturité de la collectivité 
   </td>
   <td>La ville de Marseille a un degré de maturité de<strong> niveau 4</strong>. 
   </td>
  </tr>
  <tr>
   <td>objectifs de la collectivité
   </td>
   <td>La collectivité souhaiterait que l’on établisse une base de données pour les actes d’état civil ainsi que les emprunts des bibliothèques; emprunts, abonnements et livres les plus empruntés. 
   </td>
  </tr>
  <tr>
   <td>motivation de la collectivité
   </td>
   <td>La collectivité est motivée par des logiques de transparence impulsées par la nouvelle administration municipale. 
   </td>
  </tr>
</table>



**Wishlist**


Nos interlocuteurs à la Mairie de Marseille nous ont exposé leurs objectifs nous concernant:



* Traiter la base de données état civil (mariages, naissances, décès, prénoms). Enjeu de trouver un bon schéma d’exploitation. 
* Traiter la base de données de la bibliothèque municipale. Les données sont anciennes, mais ne sont pas uniformisées. Un fort travail de formatage est à effectuer. 




## JOUR 2 – IDENTIFICATION - La partie immergée de l’iceberg

Après le brief de ce matin nous avons eu un moment de creux pendant lequel nous avons dû attendre que la Mairie de Marseille nous envoie leurs jeux de données. En attendant, nous nous sommes familiarisés avec les étapes du jour. Nous avons voulu prendre de l’avance pour faire les organigrammes des données traitées, mais aucun organigramme de la Mairie de Marseille n’est disponible en ligne. Nous avons donc demandé à nos interlocutrices de nous les transmettre. 


Plus tard dans la matinée nous avons reçu les trois premiers jeux de données, ceux concernant les bibliothèques. Nous avons commencé par évaluer le travail à fournir sur le premier jeu concernant les livres les plus empruntés. En comparant avec le template, il nous semble que nous allons devoir faire un gros effort de nettoyage et de formatage des données. Aussi, il manque les données pour l’année 2018. Il faut donc compléter le jeu de données. Les deux autres jeux de données traitent des nombres d’abonnements et des prêts par catégories d’abonnement. À première vue, nous n’avons pas compris comment traiter ces jeux de données, surtout qu’aucun template n’existe. En fait, il apparaît qu’ils ne correspondent pas à un format Open Data. Nous allons donc devoir nettoyer, compiler et standardiser les deux documents pour valoriser au mieux les données et ensuite les publier. 


En début d’après-midi, nous avons reçu les jeux de données d’États civils entre 2010 et 2020. Il y a trois documents: le premier contient les nombres d’actes d'État civils (mariage, PACS, naissance, décès) par année, les deux autres contiennent les 99 prénoms les plus donnés aux garçons et aux filles par année. Il semble que peu de travail est à fournir sur ces jeux de données, puisque leur format ressemble déjà largement aux templates. Certains membres du groupe (P.M, P-E.W-B, CF2) ont d’ailleurs pris de l’avance sur la mise en qualité de ces données et ont réalisé le travail de formatage des jeux de données d’État civil. Ils ont entre autres compilé les deux documents sur les prénoms en un seul. 


À 15h nous avons appelé nos interlocutrices marseillaises pour notre point quotidien. Dans l’ensemble, cet appel confirme notre travail d’évaluation. Il nous a permis d’affiner leurs demandes sur les formats de jeux de données. Elles souhaitent une sous-division de chaque jeu de données par année et en précisant les coordonnées géographiques des bibliothèques. En ce qui concerne les données manquantes de l’année 2018 pour les livres les plus empruntés, nos interlocutrices nous ont répondus que ces données n’existaient pas. 


Cependant, il est apparu que nous avions négligé un document concernant les bibliothèques. En effet, la mairie de Marseille souhaite également que nous traitions les archives 2005-2015 sur les bibliothèques. Ces jeux avaient déjà été publiés mais ont été retirés. La collectivité attend de nous un reformatage de ces données et notamment une cohérence avec les données à partir de 2016: la partie immergée de l’iceberg en somme. Un problème se pose puisque ces données ne correspondent pas forcément. Par exemple, les archives ne proposent que 3 catégories d’abonnement alors que les données récentes en proposent une dizaine. Nous avons donc demandé à nos interlocutrices si nous devions prioriser la cohérence des données de 2005 à 2020 ou alors la nuance des catégories d’abonnement. De la même façon, les archives traitent aussi d’autres jeux de données (concernant la localisation des prêts dans les bibliothèques et les supports empruntés). Nous avons donc demandé si Marseille voulait que l’on traite également ces jeux de données. 


Un autre sujet a été abordé pendant l’appel, celui d’ouvrir plus de jeux de données, notamment celui concernant les équipements sportifs de la ville. Allyson nous en avait en effet parlé du fait que les données publiées sur le site de la ville ne correspondaient pas du tout à celles publiées par le Ministère de l’éducation, de la jeunesse et des sports. Nous voulions ainsi pouvoir mettre à jour les données de la ville en publiant l’ensemble des données du Ministère. Nous nous sommes heurtés à une très forte réticence de la part de nos interlocutrices de nous laisser traiter ces données. Pour justifier ce refus, elles ont avancés les difficultés de la Mairie centrale de Marseille à gérer les équipements qui sont sous la main mise des mairies d’arrondissement. N’étant pas sûres d’obtenir les autorisations de publication de la part de chaque mairie d’arrondissement, elles nous ont fortement déconseillé de traiter le jeu de données des équipements sportifs malgré le fait qu’ils soient déjà ouverts. - « Actibus immensis urbs fulget Massiliensis » ( « La ville de **Marseille** resplendit par ses hauts faits »). 


Après l’appel, nous sommes retournés regarder les documents des archives de bibliothèques et avons formulé un compte-rendu ainsi que des questions. 


Concernant l’organigramme, une partie a été rédigée après avoir obtenu les informations de nos interlocutrices. Celles concernant l’État civil étant manquantes, nous attendons les informations.

**Wanted data-list :**


Etat civil



* **Actes d'État civil:** Le jeu de données étant très complet et quasiment identique au Template, le travail de formatage sera très léger.
* **Prénoms des nouveaux nés:** De la même façon les données correspondent déjà au Template, nous allons seulement compiler les deux jeux (prénoms féminins et masculins).

Bibliothèque

* **Documents les plus empruntés 2016-2020 :** Le jeu de données demande un gros effort de nettoyage et de standardisation pour correspondre au template. Il sera impossible de compléter les données manquantes de l’année 2018 puisque ces dernières n’existent pas. 
* **Nombre de prêts par bibliothèque par catégorie d'abonnement 2016-2020 :** Le jeu de données demande surtout un travail de compilation et de standardisation. Le problème étant qu’aucun template n’existe et que nous devons réfléchir au meilleur format pour traiter les données. 
* **Nombre d'abonnement par bibliothèque au 31 déc (2016-2020) :** Meme enjeu qu’au-dessus. Le travail de nettoyage est cependant moins important simplement car il y a moins de données à traiter. 
* **Archives des bibliothèques 2005-2016:** Ce jeu de donnée est celui qui va nous demander le plus de travail notamment car nous voulons etre cohérent dans notre traitement de ces données et des plus récentes. Ainsi, un gros travail de nettoyage, de compilation et de standardisation sera à fournir. Il est probable que nous divisions ce jeu de donnée en plusieurs jeux pour s’approcher le plus possible des formats de données plus récentes.

**Organigramme :**

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille2.png)     


## JOUR 3 – MISE EN QUALITE: “Data, data everywhere, nor any drop to drink”

Contrairement aux journées précédentes, la journée a été marquée par un travail soutenu du matin au soir. Nous avions déjà commencé la mise en qualité la veille permettant une mise  au travail dès notre arrivée. 


Ainsi, la veille avait été conclue la mise en qualité des données d’état civil. La mise en qualité des données relatives aux bibliothèques avait également débuté ayant permis d’établir le programme du jour 3. 


Nous sommes répartis le travail en 2 groupes: 

* J.L/ L.S/ C.F./P-E.W-B. ont mis en qualité le nombre d’abonnement par bibliothèque de 2005 à 2020. Cette étape a essentiellement consisté en de la standardisation. Les jeux de données livrés par la ville de marseille étaient composés pour chaque année de trois feuillets précisant le nombre d’abonnés chaque mois selon 3 catégories (adultes, jeunes et collectivités). Ceux allant de 2016 à 2020 avaient plus de 3 catégories. Nous avons donc converti les catégories des données de 2016 à 2020 afin qu’elles soient similaires à celles de 2005 à 2015. C.F2 a inséré les données de localisation des bibliothèques sur les tableaux. Il a trouvé les adresses sur internet puis a cherché les coordonnées de localisation sur open map. En dessous, un exemple d’avant-après la mise en qualité  pour l’année 2020. 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille3.png)     


* P.M. et N.B ont mis en qualité le nombre de prêts par catégorie d’abonnement et par bibliothèque. Pour cela, il a fallu trier les données en fonction des mois, vu qu’elles n’étaient pas dans l’ordre habituel. Après avoir fait cela, ils ont additionné les données en fonction des catégories préalablement définies : adulte, jeunesse, et collectivités. Ensuite, ils ont redressé les données afin de les faire correspondre aux normes du template et les ont ajouté au Google Sheet de l’année qu’ils faisaient. Ci-dessous un exemple avant-après pour l’année 2017. 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille4.png)     

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille5.png)     


Les difficultés du jour ont essentiellement été d’ordre technique. Les fichiers en format odp ont posé des difficultés aux possesseurs de Mac qui n’ont pas pu ouvrir ces documents. Certains ordinateurs ont surchauffé, ralentissant l'avancée du travail. La standardisation des données postérieures à 2016 dans un format similaire aux archives 2005 à 2015 a également représenté un défi important. Ces désagréments ont pu perturber l’esprit d’équipe en provoquant des incompréhensions mutuelles.


La réunion avec la collectivité en milieu d’après-midi a permis d’avoir un retour direct sur le travail de la journée. Le retour est plutôt bon. Certains détails ont cependant dû être remaniés tels que l’intégration du code commune de l’insee dans chaque jeu de donné ou l’intégration du code unique des livres pour le jeu de donnés des livres les plus empruntés. Durant cette réunion, la question de la publication a également été abordée. Nous ne publierons pas nous même les données, mais nous serons associés à la publication via une réunion. Cet élément vient renforcer notre sentiment d’une mairie “cadenassée” dans laquelle aucune initiative de notre part n’est possible.  


La journée se termine vers 17h30 avec pour conclusion la validation de chacun de nos jeux de données. La validation a été effectuée manuellement en raison de l’absence de validateur. 

**Résumé :**


<table>
  <tr>
   <td>Réussite ou casse-tête ? 
   </td>
   <td>Explication / Citation
   </td>
  </tr>
  <tr>
   <td>Casse tête 
   </td>
   <td>Problèmes techniques: “ordinateur en surchauffe”
   </td>
  </tr>
  <tr>
   <td>Réussite
   </td>
   <td>Mise en qualité des données réussie!
   </td>
  </tr>
  <tr>
   <td>Réussite 
   </td>
   <td>Validation terminée 
   </td>
  </tr>
  <tr>
   <td>Réussite
   </td>
   <td>Exposé de notre travail à la ville plutôt positif 
   </td>
  </tr>
  <tr>
   <td>Casse tête
   </td>
   <td>standardisation des données 
   </td>
  </tr>
</table>



Script :

* **Pour tous les jeux bibliothèques:**

Ajout des données de localisation des bibliothèques: recherche, vérification et compilation des adresses à partir du site officiel des bibliothèques; même processus pour les coordonnées GPS à partir de Google maps en séparant longitude et latitude. 

* **Fichier du nombre d’abonnement par bibliothèque :**

Report des données issues des fichiers archives et du fichier “Abonnés par Bib et catégorie et au 31-12  2016 à 2020”. Choix de compiler les catégories d’abonnement depuis 2016 selon le format 2005-2015 (adultes, jeunes et collectivités):

* Les chiffres des catégories “adultes gratuits”, “adultes payants”, “étudiants”, “personnel”, “pré-inscrit en ligne”, “public consultant” sont compilés sous “adultes”. 
* Les chiffres des catégories “enfants” et “jeunes” sont regroupés dans “jeunes”. 
* Les chiffres des collectivités “mères”, “-40”, “40 &lt; 300”, “40 &lt; 1500”, “service interne”, “centre social”, “maison de retraite”, “service animation collectivité”, “service interne collectivité”  sont compilés dans “collectivités” 

Une fois ce choix fait nous avons simplement reporté les données pour chaque abonnement de chaque bibliothèque dans les catégories correspondantes. Pour les documents entre 2005 et 2015, nous avons seulement utilisé les données correspondant à l’année complète.  

* **Répartition des prénoms chez les nouveaux nés**

Création des 6 colonnes suivantes : “COMMUNE_NOM” ; “CODE_INSEE” ; “ENFANT_SEXE” ; “ENFANT_PRENOM” ;  “NOMBRE_OCCURENCES” et “ANNEE”. Écrire “MARSEILLE” dans “COMMUNE_NOM” et “13055” dans “CODE_INSEE”. Copier les données “Prénom”, “Nbre” et “Année” du document source “prenom_masculin_2010_2020” d’une année donnée dans les colonnes “ENFANT_PRENOM”, “NOMBRE_OCCURENCE” et “ANNEE”. Pour chaque ligne avec un prénom masculin, écrire un “M” dans “ENFANT_SEXE”. Répéter l’opération à la suite avec les données de la même année de “prenom_féminin_2010_2020” en inscrivant “F” dans “ENFANT_SEXE”. Enfin, classer toutes ces données en fonction de leur nombre d’occurrence, dans l’ordre décroissant.


Cette méthode permet d’avoir les 198 prénoms masculins et féminins (99 pour chaque sexe) les plus donnés aux nouveaux-nés sur une année donnée, classés du plus courant au moins courant.

* **Actes d'état civil par année**

Trier les données selon l’année. Créer une fiche pour une année donnée. Y recopier les entrées du tableau du document source. Ne rentrer dans le tableau recopié que les données propres à l’année choisie. 

* **500 livres les plus empruntés :**
- **<span style="text-decoration:underline;">Création des diverses colonnes : </span>**

- <span style="text-decoration:underline;">Pour remplacer la colonne avec les « catégories documents » L1 / L2 / C1 / DT </span>

· Secteur : Distinction entre Jeunesse / Adulte / Tous publics

· Support : DVD, livre, CD.   

- <span style="text-decoration:underline;">Pour nettoyer les titres à partir des caractères spéciaux « / » ou «  [ « .</span>


· nous avons scindé le titre à l’aide cette manipulation :  

DONNÉES > « SCINDER LE TEXTE EN COLONNES » > Séparateur « PERSONNALISER à partir de « / » ou «  [ « . Ensuite, suppression de la colonne à droite des titres. 

· Déplacement de la colonne « Auteur » à droite des titres des livres. 

- <span style="text-decoration:underline;">Compléter la base de données : </span>

· Ajout de deux colonnes pour « CODE INSEE » et « NOM COMMUNE »

· Ajout d’une colonne « ANNÉE » . 


· Ajout d’une colonne « rang » qui énumère le rang des livres les plus empruntés dans un ordre croissant. 


- **<span style="text-decoration:underline;">Nettoyage des lettres</span>** : quelques malformations des accents se traduisent par des caractères similaires à celui-là : Ã© (trad : É). Pour cela : ctrl+ F => remplir « Ã© » dans la barre de recherche puis cliquer sur les 3 points à droite de la loupe. Remplacer «  Ã© » par ça «  É » et cliquer sur « Remplacer tout ». 


* **Prêts par bibliothèque et par catégorie**

Pour chaque bibliothèque, le nombre de prêts est divisé en 3 catégories : “Adulte”, “Enfant-jeune” et “Collectivités”, répartis en fonction des mois de l’année en question. Afin de les rendre lisibles par les machines, nous avons créé 3 colonnes correspondant aux 3 catégories en fonction des mois de l’année. Pour obtenir une présentation en colonne à partir d’une présentation en colonne nous avons utilisé la fonction “Transposer”. 


Nous avons ensuite ajouté les colonnes “COMMUNE_NOM” ; “CODE_INSEE”; “Mois”	“Bibliothèque”; “Adresse Bibliothèque”; “Latitude” et “Longitude”. 


## JOUR 4 – PUBLICATION: “Dans l’open data, personne ne vous entendra crier...”



Le travail du jour se constitue de la manière suivante : la restitution des jeux de données à la Collectivité de Marseille et à nos référentes. Dès le matin, nous regardons le mail que nous avons reçu et nous ajustons nos travaux. 


Ainsi, L.S. supprime les années 2015 des jeux de données concernés par les doublons car nous remarquons un pic anormal. Elle accompagne cette suppression d’une description explicative de ce phénomène. P.M., C.F.1 & J.L. s’occupent de faire passer les jeux de données du format “xls” en format "csv", comme demandée par la ville de Marseille. C.F.2, P-E.W.-B. et N.B. s’occupent de récolter les données dans le cadre des Fiches jeu de données, pour les métadonnées. Nous nous organisons comme cela jusqu’à 10h30, l’heure de l’appel. Tous les fichiers ont été renommés selon la nomenclature choisie par la ville de Marseille : MARSEILLE_TOP_PRENOMS_2010.csv. 


L’appel en question s’est bien passé. Des précisions ont été apportées et nous leur transmettons un jeu de données car elles feront elles-mêmes la publication sur datasud, puis sur le site de la ville de Marseille. Premier problème : nous avons des points-virgules à la place de simple virgule. P.M. trouve une solution et lui renvoie le jeu de données modifié. Malheureusement, cela ne marche toujours pas. Une erreur interne se lit sur son écran. Malgré tout, elle nous montre comment elles vont effectuer la transposition du jeu de données sur le portail prévu à cet effet.


Réunion finie. Nous nous répartissons les tâches à faire. J.L., C.F.2, L.S., P.-E.W.-B. travaillent sur les fiches de jeu de données en concert, pour que cela aille vite. P.M. et C.F.1 s’occupent de transcrire tous les fichiers erronés dans le bon format “csv” en UHT-8, à travers une manipulation donnée par notre interlocutrice. 


![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille6.png)     

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/RS3.png)     

**Résumé :**


<table>
  <tr>
   <td>Réussite ou casse-tête ? 
   </td>
   <td>Explication / Citation
   </td>
  </tr>
  <tr>
   <td>Les Formats
   </td>
   <td>Les conversions des formats “xls” au format "csv" sont longues et fastidieuses. Les jeux de données ont besoin d’être traités année après année, pour mettre au bon format.
   </td>
  </tr>
  <tr>
   <td>Les Fiches descriptives
   </td>
   <td>Nous ne savions pas si nous devions suivre le modèle de datactivists ou le modèle prescrit par Marseille.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



P-E.W-B et C.F.2 ont pris en charge la partie communication du groupe. Ils ont rédigé un article pour l’intranet de la ville de Marseille (voir annexe n°1). Pour se faire, ils ont écrit un article retraçant les jeux de données traités ainsi que leur utilité dans la vie de chaque Marseillais. Le but est de présenter le travail que nous avons fait aux fonctionnaires de Marseille. P.M. et C.F.2 ont continué à peaufiner les données afin qu’elles correspondent aux critères de Marseille. J.L. s’occupe de chercher les images dans une banque d’image gratuite. 


![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille7.png)     


Un mail électronique avec les informations nécessaires pour Marseille a été envoyé pour qu’ils puissent publier de leur côté les données, et de préparer la communication autour.


La journée se termine assez tôt. Nos interlocuteurs de la ville de Marseille ne répondent plus à nos mails. Ce silence est accueilli avec fébrilité par le groupe. 



## JOUR 5 – VALORISATION: “Terre en vue!”


Le bateau du groupe 13 s’approche fébrilement de la terre promise. Hier, nous avions envoyé un mail à notre interlocutrice, avec tous nos jeux de données finalisés.  Puisque nous ne pouvions pas les publier nous-mêmes sur DataSud, elle devait s’en charger. Cependant, au matin du jour 5, nous n’avions toujours pas de réponse à notre mail. Cela ne nous a pas empêchés d’avancer sur notre projet, et d’amorcer la phase de valorisation de notre challenge. Ainsi, ce jour-là, toute l’équipe s’est attelée à créer des visuels à partir des jeux de données sur lesquels elle a travaillé pendant toute la semaine de Data Challenge. Les débuts de l’équipe sont hésitants, chacun essayant un site conseillé par l’équipe de Datactivist et d’autres sites trouvés sur Internet. **Canva** nous étant très familier, il a rapidement démontré ses limites en matière d’originalité et de fonctionnalités disponibles…Dans la foulée,  Allyson nous a présenté des modèles de graphiques dynamiques et bien plus attrayants, créés grâce à l’application **Flourish Studio.io** ! 

À partir de 11h, sans aucun signal de sa part, nous décidons de contacter notre interlocutrice pour savoir où en sont nos données. Elle nous informe qu’elle a dû effectuer quelques modifications avant de publier nos jeux de données, dans la mesure où nous avions omis les années dans quelques jeux de données. Les jeux de données sont à retrouver sur ces pages : 

[https://trouver.datasud.fr/dataset/marseille-palmares-des-prenoms](https://trouver.datasud.fr/dataset/marseille-palmares-des-prenoms)

[https://trouver.datasud.fr/dataset/marseille-bibliotheque-prets](https://trouver.datasud.fr/dataset/marseille-bibliotheque-prets)

[https://trouver.datasud.fr/dataset/marseille-bibliotheques-abonnements](https://trouver.datasud.fr/dataset/marseille-bibliotheques-abonnements)

[https://trouver.datasud.fr/dataset/marseille-bibliotheques-palmares-des-prets](https://trouver.datasud.fr/dataset/marseille-bibliotheques-palmares-des-prets)

[https://trouver.datasud.fr/dataset/marseille-actes-detat-civil](https://trouver.datasud.fr/dataset/marseille-actes-detat-civil)

La frustration envahit le groupe, dans la mesure où nous aurions pu effectuer ces modifications nous-mêmes si elle nous avait tenu au courant et si nous avions publié les données nous-même. À ce moment-là, le bateau est proche du naufrage, la fatigue n'aide pas... Mais l’équipage garde la tête hors de l’eau, et la remercie pour le temps consacré à cette tâche. Dans la foulée, nous lui envoyons les scripts ainsi qu’un article sur la publication des données pour l’intranet de la mairie de Marseille. 



* P.M, en collaboration avec J.L, et N.B ont réalisé leurs graphiques sur le site  **Google Sheet,** site utilisé durant tout le challenge pour évaluer, trier et organiser nos données. Ils ont respectivement cherché à créer des visualisations pour les jeux de données “500_DOCUMENTS_LES_PLUS_EMPRUNTÉS_” et “ACTES_D_ETAT_CIVIL” . Le graphique des actes d’état civil est un diagramme de bâtons empilés, 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille8.png)     


https://public.flourish.studio/visualisation/7942600/



* P.M s’est occupé à créer des visualisations en fonction des “secteurs” des documents les plus empruntés et J.L en fonction des “supports” des documents les plus empruntés. Pour cela, ils ont dû créer des tableaux Excel en fonction des années. Les graphiques finaux sont des courbes, qui permettent de montrer au mieux l’évolution des emprunts en fonction des secteurs ou des supports. 
* Voici un extrait de l’ensemble des visualisations réalisées pour chaque année ; 

=> Graphique sur les <span style="text-decoration:underline;">secteurs des 500 documents les plus empruntés</span>, de 2016 à 2020, créé grâce à Flourish Studio par P.M : 


![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille9.png)     


 Graphique sur l<span style="text-decoration:underline;">es supports des 500 documents les plus empruntés</span>, de 2016 à 2020, créé grâce à Flourish Studio par J.L. 


![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille10.png)     


* P-E.WB et L.S. ont réalisé la même démarche pour le jeu de données “ PRÉNOMS”.  La tâche s’est avérée plus laborieuse et rigoureuse que prévu puisqu’ils ont dû traiter chaque prénom un par un, afin de pouvoir établir un graphique qui rend compte de l’évolution de l’utilisation des prénoms au fil des années. Cela prend finalement la forme d’un diagramme à bâtons (bar charts) dynamiques.  Autrement dit, le graphique évolue comme une vidéo en fonction des années. 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille11.png)     


Lien pour graphique dynamique: [ https://public.flourish.studio/visualisation/7943089/](https://public.flourish.studio/visualisation/7943089/)


Graphique animé: “L’évolution des 10 prénoms masculins donnés à Marseille entre 2015 et 2020”

* C.F1 et L.S se sont attelées à trouver les visuels adéquats au jeu de données “ PRÊTS_PAR_CATÉGORIE_D_ABONNEMENT” sur le site Google Sheet. La tâche s’est révélée fastidieuse, notamment pour choisir le type de graphique. Elles ont finalement choisi de représenter les variables “bibliothèque” et “nombre d’abonnements” sous la forme d’un (1) diagramme à bâtons empilés pour établir la répartition des abonnements en fonction des bibliothèques, combiné à (2) un diagramme à bâtons, représentant le nombre d'abonnement par catégorie, par bibliothèque. Elles ont dû répéter ce processus pour toutes les années du jeu de données. 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille12.png)     

Pour bien visualiser le jeu de donnée “EVOLUTION_DES_ABONNEMENTS”, C.F2 a choisi de sélectionner trois bibliothèques représentatives en terme de taille et de localisation des bibliothèques de la ville de Marseille (Alcazar, la Grognarde et Saint-André) et d’en réaliser trois graphiques en courbes pour montrer l’évolution de leur nombres d’abonnements. Ceux-ci ne montrant aucune tendance commune claire et d’importantes différences entre les bibliothèques.

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille13.png)     

Ensuite, il nous fallait rédiger les fiches de contextualisation des visualisations réalisées. Dans le fil de ces fiches, nous avons dû expliquer nos choix de types de graphiques (diagramme en bâtons, diagramme en bâtons empilés, courbes…), développer sur les variables représentées et l’interprétation à faire des visualisations. Finalement, nous devions déduire les usages potentiels de ces visualisations (repères pour des futurs investissements de la bibliothèque,....). 

**Résumé :**


<table>
  <tr>
   <td>Réussite ou casse-tête ? 
   </td>
   <td>Explication / Citation
   </td>
  </tr>
  <tr>
   <td>Casse-tête : Trouver les visualisations adéquates
   </td>
   <td>Étant peu habitués à créer des graphiques, les débuts sont un poil complexes.
   </td>
  </tr>
  <tr>
   <td>Réussite
   </td>
   <td>Découverte de nouveaux sites de création de graphiques. Nous sommes certains que nous allons réutiliser ces compétences pour rendre nos présentations orales plus dynamiques  ! 
   </td>
  </tr>
  <tr>
   <td>Casse-tête 
   </td>
   <td>Retour de notre interlocutrice : nous avons commis quelques impairs dans la réalisation de nos jeux de données. Cela provoque un peu de frustration au sein du groupe, parce que nous sommes conscients du temps que l’équipe de Marseille a passé à modifier ces documents. Cependant nous sommes aussi conscients que c’est un vrai métier, et que des choses pouvaient nous échapper malgré notre meilleure volonté! 
   </td>
  </tr>
  <tr>
   <td>Casse-tête 
   </td>
   <td>Le groupe est fatigué par cette semaine .
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>
    


## CONCLUSION

Cette longue traversée fut périlleuse mais nous en sortons grandis et enrichis par cette expérience : nous avons compris les mécanismes et les enjeux de l’open Data avec la ville de Marseille. Nos interlocutrices nous ont guidés et orientés toute la semaine. 

Après avoir évalué le niveau de maturité de la ville et ses besoins avec elles, nous avons travaillé sur 5 jeux de données : « Répartition des prénoms chez les nouveaux nés », « Actes d'état civil par année », « 500 livres les plus empruntés », « Prêts par bibliothèque et par catégorie » et « Nombre d’abonnement par catégorie ». Nous avons proposé d’autres jeux de données mais ce n'était pas possible. 

Notre navigation nous a conduits sur les terres nouvelles des données. Nous avons ainsi nettoyé, formaté, compilé et  standardisé ces données afin qu’elles puissent être ajoutées sur le portail open data. Nous sommes fiers. Ce fut un travail minutieux et de longue haleine au travers duquel nous avons appris à utiliser de nouveaux outils et compris le fonctionnement global de l’open data. Sur notre route nous avons rencontré des obstacles techniques tels que la conversion des fichiers (incompatibles avec nos ordinateurs), la recherche de certaines données manquantes ou encore la longueur des fichiers. Il a fallu utiliser de nouvelles fonctions notamment sur Excel. Nous avons pu compter sur Allyson qui a été une véritable bouée de sauvetage dans cet océan de données. 

En outre, nous sommes confrontés à plusieurs problématiques. Afin de standardiser les données, il a fallu faire des choix. Par exemple, les « Prêts par bibliothèque et par catégorie » s'étendait sur plusieurs années. Avant l’année 2016, les prêts étaient divisés en 12 catégories. Avec l’accord de nos collaboratrices, nous les avons réduits à 3, afin de s’aligner sur les données récoltées après 2016. L’open data peut résulter de choix. Aussi, il peut y avoir des données manquantes : le « Nombre de prêts par catégorie » pour l’année 2015 n’était pas disponible. 

Enfin, il a fallu valoriser les données afin de les rendre plus lisibles. Nous avons donc choisi de faire différents graphiques. Allyson nous a recommandé des outils, ce qui a été très formateur. 

Notre équipe était soudée et assez autonome. A part un ou deux couacs, les tâches ont été réparties de manière équitable et nous communiquions régulièrement afin de se coordonner. Nous avons beaucoup aimé travailler ensemble, il y avait une ambiance très chaleureuse à l’image de la ville.

En tant qu’étudiant à Sciences Po, le Data Challenge est totalement légitime dans le cadre de notre formation. En effet, l’open data répond principalement à un impératif de transparence pour les collectivités mais les données peuvent s'avérer très utiles. Elles peuvent rendre compte des habitudes des citoyens comme par exemple pour les prêts et le nombre d’abonnement. Par conséquent, les actions de la ville peuvent être plus efficaces. A contrario, certaines données peuvent être récupérées à des fins politiques telles que  la « Répartition des prénoms chez les nouveaux nés ». 

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille14.png)     

“Data cowboy”

<span style="text-decoration:underline;">Annexe n°1 </span>

Article rédigé par le groupe destiné à l’intranet de la ville de Marseille 

**Les étudiants de Sciences Po Saint-Germain-en-Laye ouvrent les données de la ville de Marseille**

Dans le cadre de la 4ème édition du Challenge Data, les étudiants de _Sciences Po Saint-Germain-en-Laye_ et le collectif _Datactivist_, ont assisté des collectivités dans l’ouverture de leurs données au public. La ville de Marseille s’est prêtée à l’exercice pour publier 5 jeux de données sur datasud.fr.

Les étudiants de l’institut d’études politiques ont pu se former aux enjeux de l’open data: des données numériques disponibles publiquement, gratuitement et libres de droits. Suite à la loi pour la République numérique promulguée en 2016, les collectivités locales doivent obligatoirement publier leurs principales données. Un groupe de 7 étudiants a ainsi pu aider la Direction de l'Architecture du Système Informatique et de la Donnée dans leur travail pour une ville plus transparente. 

Les 5 jeux de données ouverts ont deux thématiques: 

* État-civil d’une part, pour les Actes d'État civil et les prénoms les plus donnés à Marseille
* Bibliothèques, pour les 500 documents les plus empruntés, les prêts par catégorie d’usager et le nombre d’abonnement pour chaque bibliothèque de la ville

Les données ainsi publiées sont désormais visibles par le grand public mais elles pourraient surtout être exploitées par les services concernés pour améliorer leur offre et par des développeurs extérieurs pour d’autres applications.

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille15.png)    

![](https://raw.githubusercontent.com/datactivist/challengedata4/main/images_cdb/contenu/Marseille16.png)     

C’EST PAS LA CAPITALE, C’EST MARSEILLE BB 
