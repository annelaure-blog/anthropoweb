---
layout: post
title:  "Les data-objets : des matrices de Bertin aux sculptures de Loren Madsen"
date:   2020-01-19 08:00:00
categories: blog_post
future: true
author : Anne-Laure
---

## La grammaire graphique

N'étant ni designeuse ni statisticienne, mais géographe de formation, j'ai appris à représenter la donnée sous forme de cartographies d'après **"la graphique"** de Jacques Bertin, reprise dans le sacro-saint manuel **"La représentation des données géographiques"** de Béguin et Pumain, mes professeurs à Paris 1. Le lien entre les travaux de Bertin, précurseur en matière de représentation visuelle de l'information statistique, et mon enseignement universitaire très scolaire (suivi dans les années 2000) n'était pourtant pas évident. J'ai attendu 2020 pour découvrir **les matrices de Bertin** et son travail au Laboratoire de graphique de l'EHESS (1954-2000), à l'heure où la *dataviz* émerge dans toutes les pratiques professionnelles, sortant du champ de la recherche et des sciences sociales et gagnant le grand public.

![la graphique de Jacques Bertin]({{"/assets/graphique.jpg"|absolute_url}})

>"Une fois diplômé, Bertin travaille un temps pour l’édition, puis entre après la 2e guerre mondiale au Centre National de la Recherche Scientifique. Il participe à un travail sur l’espace social parisien, au sein d’une équipe dirigée par le sociologue Paul-Henry Chombart de Lauwe (1913-1998). Ce travail aboutit à la publication en deux volumes de Paris et l’agglomération parisienne (1952). Dans le premier tome, L’espace social d’une grande cité, Bertin rédige un chapitre intitulé "Recherche graphique", dans lequel il livre ses premières réflexions théoriques sur le langage cartographique. Il y esquisse notamment les notions de variables visuelles et de propriétés de ces variables. **Il estime que le cartographe doit tendre vers une "unité visuelle", c’est-à-dire une image efficace et susceptible d’une lecture globale.** Bertin réalise pour l’ouvrage des illustrations innovantes, en s’orientant vers une cartographie thématique univariée. Ce choix tranche nettement avec les pratiques cartographiques traditionnelles de la géographie française, notamment le croquis de synthèse régionale, en vogue jusqu’aux années 1970, surchargé de données et souvent illisible." (Palsky, 2015)

Cette réflexion sur la construction d'une **grammaire graphique** est plus que jamais d'actualité, même si l'avènement de l'informatique a bouleversé les règles du jeu depuis Bertin. Un certain **Hadley Wickham**, développeur statisticien, bien connu des data-scientists, a publié en 2010 un papier de référence : *"A Layered Grammar of graphics"* qui détaille la structure du package *ggplot2* (utilisé dans le logiciel et language de programmation R, aujourd'hui leader de la data science dans le monde avec le language Python). Ggplot2 permet de visualiser la donnée analysée et traitée au préalable dans R (voir exemple ci-dessous).

![les scatterplots dans R avec ggplot2]({{"/assets/scatterplot.png"|absolute_url}})

La **grammaire graphique** est aujourd'hui encore un **language visuel à l'intersection de la linguistique, du design, de la programmation informatique, de la statistique, de l'art, de la pédagogie, de la communication, des médias et des sciences** en perpétuelle évolution. Bertin disait qu'un choix était à faire entre *"voir ou lire"*(Gimeno, 2018) : il était pour lui nécessaire d'uniformiser la sémiologie graphique afin de rendre les images simples et donc rapide à comprendre, plutôt que de privilégier l'esthétique au détriment de la donnée représentée. 


## Les data-objets : du prototype à l'oeuvre d'art

**Les matrices de Bertin relèvent davantage du prototype que de l'objet**. Il s'agissait, dans le cadre des recherches du laboratoire de Graphique de l'EHESS, de produire un système interactif et dynamique de représentation de l'information qui simplifie la traitement de la donnée sans occasionner de perte de l'information. Ce système de découpage de l'information en lignes et en colonnes, où la donnée est représentée par un symbole et/ou une couleur, permettait de classer les matrices en groupes similaires. Pour les enfants au CP, le principe fonctionnait tout aussi bien avec des bandes de papier que l'on déplaçait à la main pour classer l'information et construire sa réflexion.

![les matrices domino de Jacques Bertin]({{"/assets/matricephoto.jpg"|absolute_url}})

>"La méthode proposée par Bertin était d’ordre scientifique : on se posait des questions, on formulait des hypothèses, on délimitait un domaine de recherche et des objets d’étude. On disposait d’un **outil visuel et manuel, la matrice permutable**, qui permettait d’effectuer un traitement, de découvrir des classes d’objets, d’obtenir des typologies et donc de construire des concepts. Et l’outil même constituait un support excellent pour interpréter les résultats et construire un discours ou un texte. Cet apprentissage de la rigueur fonctionnait depuis le CP et à tous les niveaux. Pour répondre à votre remarque, avec l’appui de chercheurs, les enseignants n’avaient aucune difficulté à s’approprier la méthode. Mais, laissés seuls, des problèmes se présentaient pour amener les enfants à construire eux-mêmes les connaissances." (Gimeno, 2018)

Preuve de l'intérêt que suscite aujourd'hui la question de la grammaire graphique et du traitement de la donnée "low tech", qui privilégie le design d'interactions, des chercheurs de l'INRIA ont reproduit **une version web des matrices de Bertin** et construit le "Bertifier" (Perin et al, 2014). Il s'agit d'une application web qui permet de reproduire le raisonnement développé par Bertin en créant ses propres matrices : [https://aviz.fr/bertifier_app/](https://aviz.fr/bertifier_app/). On y apprend assez intuitivement le principe de classement par similarité visuelle des variables en regardant [le tutoriel](https://aviz.fr/wiki/uploads/Bertifier/bertifier-tutorial.mp4).

![Exemple de matrice de Bertin]({{"/assets/matrice.jpg"|absolute_url}})

Le chercheur en *computer science* Mathieu le Goc, qui s'intéresse aux **interactions tangibles** et aux **interfaces physiques**, a recréé une version contemporaine des dominos de Bertin via l'équipement d'un Fablab : [https://www.mathieulegoc.me/diy-bertin](https://www.mathieulegoc.me/diy-bertin).   

La profusion technologique contemporaine n'a donc pas éludé la réflexion sur la grammaire graphique ou le design d'interactions entre le lecteur de la donnée et celui ou celle qui la représente. Les mêmes questions éthiques et idéologiques se posent quant à ce qu'on donne à voir, à qui, comment et pourquoi. Sur ces questions les artistes bouleversent les perspectives de la recherche traditionnelle en jouant sur un autre registre de perception et de lecture visuelle.  


## Les data-sculptures : une approche artistique de la donnée

L'artiste Loren Madsen est une pionnière du "data art" qu'il pratique depuis les années 1970. Centrées sur des thèmes de société, basées sur des statistiques officielles, ses oeuvres mettent en volume et en objet des données sur la criminalité, la population humaine ou encore le terrorisme.

![Data Art sur la population humaine de Loren Madsen]({{"/assets/loren_data.jpg"|absolute_url}})

L'oeuvre *"6 000 000 000 of Monkeys"* (ci-dessus) de 1999 représente l'évolution de la population humaine depuis 10 000 avant JC jusqu'en l'an 2000. La représentation en trois dimensions d'un cône métallique permet aisément, par sa forme spectaculaire mais simple, de saisir l'information représentée : "la moitié des Sapiens ayant existé sont en vie aujourd'hui".

![Data Art sur le terrorisme par Loren Madsen]({{"/assets/loren_terror.jpg"|absolute_url}})

L'oeuvre ci-dessus exploite les données de la *Global Terrorism Database* et les retranscrit dans une installation nommée "Worry Beads" ("les perles de l'inquiétude") où chaque perle représente le nombre de morts dû à des attentats terroristes entre 1945 et 2017 (à l'échelle mondiale pour le long chapelet de grosses sphères, à l'échelle des Etats-Unis le court chapelet de petites perles). La différence d'échelle spectaculaire entre ces deux séries de données mets immédiatement en lumière la relative faiblesse du risque terroriste aux USA par rapport à d'autres régions du monde.

Deux chercheurs, Pierre Dragicevic de l'INRIA (aussi derrière le Bertifier) et Yvonne Jansen (CNRS, ISIR – Institut des Systèmes Intelligents et de Robotique) ont compilé une liste de "Data physical Visualizations" où l'on trouve plus de **350 data objects**. A retrouver sur : [http://dataphys.org/list/](http://dataphys.org/list/).   


Des propositions qui font **relativiser la toute puissance de l'informatique dans la visualisation de la donnée** : si aujourd'hui tout semble vouloir nous emmener vers une montée en compétence (sans doute utopique) de tout citoyen en data scientist, la **data literacy** demeure autant une affaire de raisonnement et de connaissance de règles fondamentales simples qui ont été inventées il y a plus de cinquante ans.

En s'appuyant sur les règles fondamentales de *la graphique* et en privilégiant toujours la clarté et la simplicité du message (la fonction détermine la forme), chacun pourra s'emparer du medium de son choix pour imaginer des représentations tant *lowtech* qu'efficaces.  




*Sources*

BEGUIN, M. & PUMAIN, D.(2000). "La représentation des données géographiques, statistique et cartographie", Armand Colin, Cursus Géographie, 189p.  
BERTIN J.(1973). "Sémiologie graphique. Les diagrammes, les réseaux, les cartes", Paris/La Haye, Mouton, Paris, Gauthier-Villars.  
BERTIN J.(1977). "La graphique et le traitement graphique de l’information", Paris, Flammarion.   
COPLAND, E. (2019). "An art and a science: Artists use data from the Global Terrorism Database (GTD) in works of data visualization art", [https://start.umd.edu/news/art-and-science-artists-use-data-global-terrorism-database-gtd-works-data-visualization-art](https://start.umd.edu/news/art-and-science-artists-use-data-global-terrorism-database-gtd-works-data-visualization-art)  
DRAGICEVIC, P. & JANSEN, Y. "List of Physical Visualizations and Related Artifacts", [http://dataphys.org/list/](http://dataphys.org/list/), consulté le 18/01/2020  
GIMENO, R. (2018), "Voir ou lire", interview BACK OFFICE (revue), *Penser, classer, représenter*, no 2, [http://www.revue-backoffice.com/numeros/02-penser-classer-representer/entretien-gimeno-buellet-renon-voir-lire](http://www.revue-backoffice.com/numeros/02-penser-classer-representer/entretien-gimeno-buellet-renon-voir-lire)      
PALSKY, G. (2015). "Jacques Bertin", *Hypergeo*, [http://www.hypergeo.eu/spip.php?article630](http://www.hypergeo.eu/spip.php?article630)  
PALSKY, G. (2017). "La Sémiologie graphique de Jacques Bertin a cinquante ans !", Visioncarto, [https://visionscarto.net/la-semiologie-graphique-a-50-ans](https://visionscarto.net/la-semiologie-graphique-a-50-ans)  
PERIN, C. & Al. (2014). "Revisiting Bertin Matricies : New Interactions for Crafting Tabular Visualisations", *IEEE Transactions on Visualization and Computer Graphics*, Vol 20, no 12, p.2082-2091, [https://aviz.fr/wiki/uploads/Bertifier/bertifier-authorversion.pdf](https://aviz.fr/wiki/uploads/Bertifier/bertifier-authorversion.pdf)  
WICKHAM, H. (2010). "A Layered Grammar of Graphics", *American Statistical Association, Institute of Mathematical Statistics and Interface Foundation of North America, Journal of Computational and Graphical Statistics*, Vol. 19, no 1, p. 3-28.  
