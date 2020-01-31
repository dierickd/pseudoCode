debut achatBonbon (reel argent, reel prix)

    quantite = 0

    Si argent > 0 ET prix > 0 
        Tant que argent >= prix
            quantite = quantite + 1
            argent = argent - prix
        Fin Tant que
    Fin Si

    retourne quantite

fin achatBonbon

achatBonbon(12.45, 1.14)
