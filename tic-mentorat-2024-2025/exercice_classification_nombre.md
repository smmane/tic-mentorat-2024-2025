🧪 Défi #2 – Classification d’un nombre
🎯 Objectif :
Écrire un algorithme qui :

Demande un nombre entier

Indique si ce nombre est :

.positif pair

.positif impair

.négatif pair

.négatif impair

.ou zéro


📝 Énoncé en pseudocode :
Début
    afficher("Entrer un nombre entier :")
    lire n

    si n = 0 alors
        afficher("C'est zéro.")
    sinon
        si n > 0 alors
            si n % 2 = 0 alors
                afficher("Nombre positif pair")
            sinon
                afficher("Nombre positif impair")
        sinon
            si n % 2 = 0 alors
                afficher("Nombre négatif pair")
            sinon
                afficher("Nombre négatif impair")
Fin
