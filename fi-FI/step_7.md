## Ajastimen lisääminen

+ Luo uusi muuttuja nimeltä "aika".

+ Voitteko lisätä ajastimen vaiheesi antamaan soittimesi vain 10 sekuntia, jotta saataisiin mahdollisimman monta haamua?
    
    Ajastimesi pitäisi:
    
    + Aloita 10 sekunnissa
    + Laske alas joka sekunti
    
    Pelin pitäisi pysähtyä, kun ajastin siirtyy 0: ksi.

\--- vinkit \--- \--- vinkki \--- `Kun vihreä lippu napsautetaan`, `-ajan` muuttuja on `asetettu arvoon 10`. Tämän jälkeen `muutetaan -1` : lla joka toinen `, kunnes se saavuttaa 0`. \--- / hint \--- \--- vinkki \--- Tässä on koodilohkot, joita sinun tulee käyttää: ![screenshot](images/ghost-timer-blocks.png) \--- / hint \--- \--- vinkki \--- Näin voit lisätä ajastimen peli: ![kuvakaappaus](images/ghost-timer-code.png)

Ja näin luodaan `time = 0` block: ![screenshot](images/ghost-timer-help.png) \--- / hint \--- \--- / vinkkejä \---

+ Pyydä kaveri testata peliäsi. Kuinka monta pistettä he voisivat panostaa?
    
    Jos peli on liian helppoa, voit:
    
    + Anna soittimelle vähemmän aikaa
    + Tee kummit näyttävät harvemmin
    + Tee kummitukset pienemmiksi
    
    Muuta ja testata peliä muutaman kerran, kunnes olet tyytyväinen siihen, että se on oikea vaikeustaso.