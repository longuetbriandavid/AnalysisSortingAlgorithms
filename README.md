# AnalysisSortingAlgorithms

Ce projet a été réalisé dans le cadre de la troisième année de licence en informatique.

**Context : **

Le tri de données est une opération fondamentale dans l’informatique, qui consiste à organiser un ensemble de données dans un ordre précis. Il existe de nombreux algorithmes de tri, chacun ayant ses avantages et ses inconvénients. Certains algorithmes sont plus efficaces que d’autres en fonction de la structure des données à trier, et certains peuvent même être optimisés en fonction de la distribution des données en entrée.


L’objectif de ce projet est d’implémenter une collection d’algorithmes de tri et de les visualiser en action. Mais au-delà de cet aspect pratique, nous pouvons également nous intéresser à l’efficacité de ces algorithmes en fonction du niveau de désordre des données en entrée. En effet, le nombre de comparaisons, les accès aux données et le temps d’exécution total d’un algorithme peuvent varier considérablement en fonction de la quantité et de la répartition des données à trier.


Pour répondre à cette question, nous avons dû développer un générateur de
données paramétré par un niveau de désordre, et effectuer des expériences pour
comparer les performances des différents algorithmes de tri en fonction de ce paramètre. En analysant les résultats, nous avons déterminé quels algorithmes sont les plus adaptés à des situations de désordre élevé ou faible.

**Algorithmes implémentés : **

- SelectionSort
- BubbleSort
- InsertionSort
- QuickSort
- MergeSort
- HeapSort
- CountingSort
- ShellSort
- GnomeSort
- PancakeSort
- CombSort
- BogoSort


**Mode d'emploi : **

En raison de contraintes de temps, nous n'avons pas pu intégrer la "Visualisation des algorithmes de tri pas à pas" au reste du projet. Pour l'utiliser, il vous suffit d'exécuter le fichier **main.py** en utilisant la commande **python3 main.py**. Cela affichera l'exécution en temps réel de l'algorithme QuickSort.

Avant de lancer cette commande, dans le fichier **main.py** vous pouvez sélectionner l'algorithme de votre choix en commentant ou décommentant les lignes correspondantes. Vers la fin du fichier, si vous souhaitez exécuter l'algorithme sans affichage, définissez la variable choice à 0. Pour afficher les étapes à l'écran, réglez-la sur 1, et pour lancer les tests sur 2.

Pour découvrir le reste du projet, veuillez lancer la commande **python3 tkMain.py**.

Pour plus d'informations, veuillez consulter le rapport "**Rapport_Projet-3.pdf**" situé dans le dossier rapport.
