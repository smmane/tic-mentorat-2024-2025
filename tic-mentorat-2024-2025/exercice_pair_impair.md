🧪 Défi #1 – Pair ou Impair ?
🎯 Objectif :
Écrire un algorithme qui :

1 Demande à l'utilisateur d'entrer un nombre entier

2 Affiche si ce nombre est pair ou impair
📝 Énoncé en pseudocode :
Début
    afficher("Entrer un nombre entier :")
    lire nombre

    si (nombre modulo 2 = 0) alors
        afficher("Ce nombre est pair.")
    sinon
        afficher("Ce nombre est impair.")
Fin

💡 Astuce :
L’opérateur modulo (% ou mod) donne le reste d’une division.
Un nombre est pair si nombre % 2 == 0.