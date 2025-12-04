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

