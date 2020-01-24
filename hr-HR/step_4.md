\--- challenge \---

## Izazov: Odbrojavanje

Možete li stvoriti **novi** tajmer koji se broji do 0? Evo kako bi trebao raditi vaš novi tajmer:

+ Ako zajedno pritisnete gumbe A i B, resetirajte `timer` na 0
    
    ![screenshot](images/clock-challenge-1.png)

+ Pritiskom na tipku B, treba dodati 1 na tajmer. Pritisnite ga 10 puta da biste stvorili vremenski mjerač od 10 sekundi.
    
    ![screenshot](images/clock-challenge-2.png)

+ Pritiskom na tipku A trebalo bi biti 1 od vaše varijable `time` sve dok ne dođete do 0. To znači da ćete trebati `, dok` petlju da radi sve dok je `puta` je veća od (`>`) 0.
    
    ![screenshot](images/clock-challenge-3.png)

## Točan tajmer

Jeste li primijetili da tajmer nije baš precizan! To je zato što je potrebno vrijeme za prikazivanje i pomicanje brojeva na mikro: bitu.

Pokušajte prilagoditi stanku kako biste poboljšali vrijeme. Možete koristiti blok `if / else` za kraća odlaganja za veće brojeve koji traju dulje za pomicanje.

\--- /challenge \---