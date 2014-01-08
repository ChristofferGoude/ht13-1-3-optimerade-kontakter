### Laboration 3 - ASP.net MVC

#### Databasmodellering - Fysisk modell

**Index**

+ Index f�r MEDLEM.Enamn och MEDLEM.Fnamn d� dessa �r vanliga s�ktermer.
+ Index f�r ADRESS.AdressID f�r att optimera vid join med MEDLEM.
+ Index f�r ADRESS.PostnrID f�r att optimera vid join med ADRESS.
+ Index f�r ADRESS.KontaktID f�r att optimera vid join med MEDLEM.

**Optimering**

ADRESS.Gata �r en sammanslagning av gata, gatunr, uppgang och conamn. Denna information hanteras
i princip alltid p� ett och samma f�lt i vanliga fall s� denna sammanslagning passar bra.

**Denormalisering**

