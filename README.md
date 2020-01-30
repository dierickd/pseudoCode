# pseudoCode

debut achatBonbon (nombre argent, nombre prix)
    quantite = 0

    si argent < 0 OU prix < 0 
        retourne quantite

    Tant que argent - prix >= prix
        quantite = quantite + 1
        argent = argent - prix
    Fin Tant que

    retourne quantite

fin achatBonbon
