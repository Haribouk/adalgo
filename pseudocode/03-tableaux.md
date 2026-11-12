EXOS TABLEAUX :

EXO 1 :
Variables : tab:ENTIER[]

DEBUT
    max <- tab[0]
    Pour i <- 1 à taille.tab - 1
        Si tab[i] > max alors
            max <- tab[i]
        Fin Si
    Fin Pour
    RETOURNER max
FIN

EXO 2 : 
Variables : tab:ENTIER[]

DEBUT
    min <- tab[0]
    Pour i <- 1 à taille.tab - 1
        Si tab[i] < min alors
            min <- tab[i]
        Fin Si
    Fin Pour
    RETOURNER min
FIN

EXO 3 : 
Variables : tab:ENTIER[]

DEBUT
    total <- 0
    moyenne <- 0
    Pour i <- 0 à taille.tab - 1
        total += tab[i]
    Fin Pour
    moyenne <- total / taille.tab
    RETOURNER moyenne
FIN

EXO 4 :
Variables : tab:ENTIER[], valeur:ENTIER

DEBUT
    Pour i <- 0 à taille.tab - 1
        Si tab[i] = valeur alors
            RETOURNER true
        Fin Si
    Fin Pour
    RETOURNER false
FIN

EXO 5 :
Variables : tab:ENTIER[], valeur:ENTIER

DEBUT
    compteur <- 0
    Pour i <- 0 à taille.tab - 1
        Si tab[i] = valeur alors
            compteur <- compteur + 1
        Fin Si
    Fin Pour
    RETOURNER compteur
FIN

