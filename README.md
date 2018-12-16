# Posvetljivanje i kontrast slike
Digitalna slika se može prikazati pomoću matrice, gdje svaki element matrice predstavlja jedan piksel slike.
Svaki element matrice određuje intezitet odgovarajućeg piksela u rasponu od 0 do 255.
Sliku u boji prikazujemo pomoću tri različite matrice.
Primjenom matematičkih transformacija možemo obraditi sliku.

Korak 1: Posvetljivanje slike

Ako posvetljujemo sliku za n% potrebno je da  vrijednost svakog elementa matrice (piksela)  povećamo  za n%.

Korak 2: Kontrast slike

Ako pravimo kontrast slike za n% potrebno je da vrijednost svakog elementa matrice (piksela) umanjimo za n%, da bi se nijansa potamnila ukoliko je početna vrijednoost bila  manja od 128 u suprotnom povećavamo za n%, da bi se nijansa još prosvijetlela.
Na taj način povećavamo kontrast slike.

