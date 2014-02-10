Perceptron-AI-course
====================
Démarche de développement et d'améliorations par rapport à l'idée de base.
==========================================================================
        Pour commencer, nous avons développé notre perceptron de la manière la plus simple possible, avec quelque défaut de calibrage pour différencier, des deux d’un trois ou d’un cinq. Nous avons donc vite compris que pour que chaque nombre soit bien différent les uns des autres, il nous fallait une plus grande résolution.
        On a donc augmenté le nombre de pixels mais aussi, nous avons mis en place un effet de floutage qui ajoute encore plus d’entrés actif permettant d’affiner nos résultats ainsi qu’une modification du taux d'apprentissage suivant la couleur du pixel allumé. Pour la couleur normale nous auront un taux d’apprentissage normale et qui sera dévalué par rapport au niveau de floutage pour les autres couleurs.
        Une implémentassions que nous avons réalisée, et de déplacer les pixels actifs dans un coin de notre canvas, cela pour pouvoir identifier un nombre, où qu'il soit inscrit dans le canvas.
Puis nous avons mis en place une sorte de mémoire des chiffre appris qui nous permet de ré-afficher une forme précédemment apprise.
Idées d'améliorations possibles mais n'ayant pas pu être implémentées.
======================================================================
        Une idée que nous n'avons pas pu réaliser faute de complexité, est d’amener une forme, à une taille choisie (agrandir ou rétrécir). Nous pensions utiliser l’algorithme hqnx pour faire ces modifications. Cela aurait permis que chaque forme est tout le temps la même résolution. Ainsi, quelle que soit la position ainsi que la taille de la forme, notre algorithme aurait pu la reconnaître.
Easter eggs
===========
Nous avons également placé quelques easter eggs, saurez-vous les trouver ?
