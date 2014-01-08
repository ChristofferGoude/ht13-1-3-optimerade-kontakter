### Laboration 3 - ASP.net MVC

#### Databasmodellering - Fysisk modell

**Index**

+ Index för MEDLEM.Enamn och MEDLEM.Fnamn då dessa är vanliga söktermer.
+ Index för ADRESS.AdressID för att optimera vid join med MEDLEM.
+ Index för ADRESS.PostnrID för att optimera vid join med ADRESS.
+ Index för ADRESS.KontaktID för att optimera vid join med MEDLEM.

**Optimering**

ADRESS.Gata är en sammanslagning av gata, gatunr, uppgang och conamn. Denna information hanteras
i princip alltid på ett och samma fält i vanliga fall så denna sammanslagning passar bra.

**Denormalisering**

