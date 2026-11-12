EXOS BOUCLES : 

EXO 1 :
Variables : n:ENTIER
DEBUT 
    Pour i <- 1 à n
        AFFICHER i
    Fin Pour
FIN

EXO 2 :
Variables : n:ENTIER
DEBUT
    Pour i <- 1 à n
        Si i % 2 = 0 alors
            AFFICHER i
        Fin Si
    Fin Pour
FIN

EXO 3 :
Variables : n:ENTIER
DEBUT
    Pour i <- 1 à n
        somme <- somme + i
    Fin Pour
    RETOURNER somme
FIN

EXO 4 :
Variables : n:ENTIER
DEBUT
    resultat <- 1
    Si n = 0 alors
        RETOURNER resultat
    Fin Si
    Pour i <- 1 à n
        resultat <- resultat * i
    Fin Pour
    RETOURNER resultat
FIN

EXO 5 :
Variables : n:ENTIER
DEBUT
    compteur <- 0
    Pour i <- 1 à n
        Si i % 2 = 0 alors
            compteur <- compteur + 1
        Fin Si
    Fin Pour
    RETOURNER compteur
FIN

EXO 6 :
Variables : n:ENTIER
DEBUT
    tab <- []
    j <- 0
    Pour i <- 1 à n
        Si i % n = 0 alors
            tab[j] <- i
            j = j + 1
        Fin Si
    Fin Pour
    RETOURNER tab[]
FIN

EXO 7 :
Variables : n:ENTIER, limite:ENTIER
DEBUT
    tab <- []
    j <- 0
    Pour i <- 1 à limite
        Si i % n = 0 && i <= limite alors
            tab[j] <- i
            j = j + 1
        Fin Si
    Fin Pour
    RETOURNER tab[]
FIN