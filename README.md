## Soronként cserélő kódolás és dekódolás
A kódoláshoz a szóvéget sorfolytonosan adott számú oszlopba írjuk, majd az oszlopokat a kulcs´által megadott sorrendben átrendezve az eredményt sorfolytonosan olvassuk ki. A dekódolás hasonló, csak a kulcs alapján vissza kell rendezni az oszlopokat. Például 7 oszloppal, 3 4 2 1 5 6 7 kulccsal és „eztaszovegetkelltitkositanod” szöveggel a táblázat csere előtt es után:  

A titkosított szöveg: ”tazeszogeevtketilltkotaisnod”.  

Bemenet  
A bemenet 
- kódolásról vagy dekódolásról van szó.
- oszlopok száma
- a kulcsot, vagyis hogy milyen sorrendben kell összekavarni az oszlopokat ahhoz, hogy a kódolt szóvéget megkapjuk, 
- illetve dekódolás eseten milyen sorrendben kell feltölteni a táblázat oszlopait ahhoz, hogy a sorfolytonos olvasással visszakapjuk az eredeti szöveget.
- a szöveg, ami nem tartalmaz szóközt és egyéb írásjeleket.


Példák  
1. példa  
Input  
3 4 2 1 5 6 7  
eztaszovegetkelltitkositanod  
Output  
tazeszogeevtketilltkotaisnod  


2. példa  
Input  
3 4 2 1 5 6 7  
Output  
eztaszovegetkelltitkositanod  
