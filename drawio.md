# Opgave 1: Beregn rabat

Tegn et flowchart i draw.io, der beregner en pris med rabat:

- Hvis prisen er over 500 kr, gives 10% rabat.
- Ellers gives ingen rabat.
- Programmet skal outputte den endelige pris.

## Pseudokode

```
INPUT pris
IF pris > 500 THEN
    rabat = pris * 0.10
    endeligPris = pris - rabat
ELSE
    endeligPris = pris
END IF
OUTPUT endeligPris
```

# Opgave 2: Gæt et tal

Tegn et flowchart, der beskriver et gættespil:

- Computeren har tallet 7
- Brugeren indtaster et tal
- Programmet siger om gættet er:
    - korrekt
    - for højt
    - for lavt

## Pseudokode

```
SET hemmeligtTal = 7
INPUT gæt
IF gæt == hemmeligtTal THEN
    OUTPUT "Korrekt!"
ELSE IF gæt > hemmeligtTal THEN
    OUTPUT "For højt!"
ELSE
    OUTPUT "For lavt!"
END IF
```

# Opgave 3: Beregn gennemsnit af tre tal

Tegn et flowchart, der:

- Modtager tre tal
- Beregner gennemsnittet
- Outputter resultatet

## Pseudokode

```
INPUT tal1
INPUT tal2
INPUT tal3

sum = tal1 + tal2 + tal3
gennemsnit = sum / 3
OUTPUT gennemsnit
```

## Opgave 4: Hverdagssituation

Vælg en situation fra din hverdag. Tegn et flowchart i draw.io.

Flowchartet skal indeholde:
- Sekvens af handlinger
- Mindst én beslutning
- Evt. en løkke (hvis situationen passer)

Mulige situationer:
- Lave morgenmad
- Tage bussen til skole
- Lave en kop te
- Handle i supermarkedet
- Vælge tøj

Tilføj pseudokode, der beskriver flowchartet.

### Eksempel på pseudokode: Lave Morgenmad

```
START
TAKE brød
IF brød er frisk THEN
    TOAST brød
ELSE
    GET nyt brød
END IF
SPREAD smør på brød
ADD pålæg
SERVE morgenmad
END
```

### Eksempel på pseudokode: Tage bussen til skole

```
START
CHECK busplan
IF bus kommer snart THEN
    WAIT ved busstoppested
ELSE
    DO noget andet indtil bussen kommer
END IF
WHEN bus arrives THEN
    BOARD bus
    PAY fare
    RIDE to school
    GET off bus
END
```


# Opgave 5: BMI-beregner

Tegn et flowchart i draw.io, der beregner Body Mass Index (BMI):
- Modtag vægt (i kg) og højde (i meter)
- Beregn BMI ved hjælp af formlen: BMI = vægt / (højde * højde)
- Output BMI-værdien
- Tilføj pseudokode, der beskriver flowchartet.


# Opgave 6: Grundlæggende regnemaskine

Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager to tal fra brugeren
- Beregner summen, forskellen, produktet og kvotienten af de to tal
- Outputter resultaterne.

# Opgave 7: Temperaturkonvertering

Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager en temperatur i Celsius fra brugeren
- Konverterer temperaturen til Fahrenheit ved hjælp af formlen: F = C * 9/5 + 32
- Outputter den konverterede temperatur.

# Opgave 8: Simpel login-validering
Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager et brugernavn og en adgangskode fra brugeren
- Tjekker om brugernavnet er "admin" og adgangskoden er "password123"
- Hvis begge er korrekte, outputter "Login successful"
- Ellers outputter "Login failed".

# Opgave 9: Harris-Benedict formel for basalstofskifte
Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager vægt (i kg), højde (i cm), alder (i år) og køn (mand/kvinde) fra brugeren
- Beregner basalstofskiftet (BMR) ved hjælp af Harris-Benedict formlen:
  - For mænd: BMR = 88.362 + (13.397 * vægt) + (4.799 * højde) - (5.677 * alder)
  - For kvinder: BMR = 447.593 + (9.247 * vægt) + (3.098 * højde) - (4.330 * alder)
- Outputter BMR-værdien.

# Opgave 10: Afsætning efter rabat og moms
Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager en oprindelig pris fra brugeren
- Anvender en rabat på 15% på prisen
- Beregner moms på 25% af den rabatterede pris
- Outputter den endelige pris efter rabat og moms.

# Opgave 11: Afsætning og lagerstyring
Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager antallet af varer på lager og antallet af solgte varer fra brugeren
- Opdaterer lagerbeholdningen ved at trække de solgte varer fra lagerbeholdningen
- Hvis lagerbeholdningen er under 10, outputter "Bestil flere varer"
- Ellers outputter den opdaterede lagerbeholdning.

# Opgave 12: Karaktergennemsnit
Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager karakterer for fem fag fra brugeren
- Beregner gennemsnittet af karaktererne
- Hvis gennemsnittet er over 2, outputter "Bestået"
- Ellers outputter "Ikke bestået"

# Opgave 13: Tælle antal elever i en klasse

Tegn et flowchart i draw.io og skriv pseudokode for et program, der:

- Modtager et sluttal (N) fra brugeren.
- Bruger en løkke til at tælle fra 1 op til dette sluttal.
- Outputter hvert tal undervejs i tællingen.
- Outputter en afsluttende besked ("Optælling fuldført!"), når sluttallet er nået.


