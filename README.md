# Algorithmique

Le probl`eme d’allocation Student-Project consiste `a affecter des  ́etudiants `a des projets en fonction des
pr ́ef ́erences des  ́etudiants par rapport aux projets. Parmi un ensemble de projets, chaque  ́etudiant indique
une liste de score(de 1 `a n, o`u n est le nombre total des projets) sur les projets  ́eligibles, 1 est la plus petite
score pour dire que ce projet est le moins aim ́e par ce groupe, n est la plus grande score pour dire que
ce projet est le plus aim ́e par ce groupe tandis qu’on va trouver l’assignation optimale de n  ́etudiants `a n
projets.


Dans ce projet, nous consid ́erons qu’on a le mˆeme nombre des  ́etudiants et des projets, et nous avons
une matrice carr ́ee M qui nous donne une matrice de score de taille n aux deux types(’random’, ’pref’).
Le type ’random’ est de g ́en ́erer une matrice de score al ́eatoirement. Cependant dans le cas g ́en ́eral, les
 ́etudiants peuvent s’int ́eresser sur des mˆeme projets donc le type ’pref’ est de g ́en ́erer une matrice de
score qui combine des grandes valeurs sur les plusieurs colonnes. Dans ce cas, cela va ˆetre plus compliqu ́e
mais plus pratique. Pour r ́esoudre ce probl`eme, nous allons cr ́eer trois algorithmes : l’algorithme na ̈ıf,
l’algorithme r ́ecursive et l’algorithme g ́en ́etique. Et nous allons aussi programmer ces trois algorithmes en
R et en C++ pour  ́evaluer la qualit ́e du r ́esultat et le temps de calcul de ces algorithmes. Finalement, on
va  ́etudier la complexit ́e de ces algorithmes.
