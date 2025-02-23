# rubikscube-SAT-solver

Projet de résolution de Rubik's Cube en utilisant un solveur SAT.

Le but du projet est de modéliser la résolution rubikscube sous forme de logique propositionnelle, de réduire l'expression sous forme CNF et de résoudre le problème avec le solveur SAT Gophersat.

## Installation

Pour installer le projet, il suffit de cloner le dépôt git et d'installer les dépendances.

```bash
git clone
cd rubikscube-SAT-solver
pip install -r requirements.txt
```

Dé-commenter le chemin du solveur correspondant à votre OS dans la première cellule du notebook et commenter les autres. Cela permettra d'utiliser le bon solveur SAT Gophersat.

Lien vers gopherSAT github : <https://github.com/crillab/gophersat>

## Utilisation

Le projet est divisé en 2 parties, une première partie pour résoudre le rubikscube 2x2x2 pour commencer méthodiquement à petite échelle. On y retrouvera la méthode de réduction en problème SAT expliquée dans les markdowns du notebook.

fichier `rubikscube_2x2.ipynb`:

Et une 2ème partie de mise à l'échelle pour le rubikscube 3x3x3. On retrouvera des explications plus succinctes (renvoyant au notebook 2x2 pour les détails) et des fonctions pour résoudre le rubikscube 3x3x3.

fichier `rubikscube_3x3.ipynb`:
