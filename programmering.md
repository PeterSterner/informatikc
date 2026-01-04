# Programmering


## Skift skærm

a) Tilføj to skærme  til din app (Screen1 og Screen2).
b) Tilføj en knap på hver skærm.
c) Når knappen på Screen1 trykkes skift til Screen2. Vink: Benyt `setScreen()`.
d) Når knappen på Screen2 trykkes skift tilbage til Screen1. Vink: Benyt `setScreen()`.

## Beregn sum af to tal (uden variabler)

a) Tilføj to tekstinputfelter og en knap. Vink: Brug `TextInput` komponenten.
b) Tilføj en etiket til at vise resultatet. Vink: Brug `Label` komponenten.
c) Tilføj en hændelsesbehandler til knappen. Vink: Brug `onEvent()`.
d) Når knappen trykkes skal summen af de to tal vises i etiketten. Vink: Brug `setText()` til at opdatere etiketten.

## Beregn sum af to tal (med variabler)

a) Tilføj to tekstinputfelter og en knap. Vink: Brug `TextInput` komponenten.
b) Tilføj en etiket til at vise resultatet. Vink: Brug `Label` komponenten.
c) Opret to variabler til at gemme de to tal. Vink: Brug `let tal1 = 0;` og `let tal2 = 0;` øverst i din kode.
d) Opret en variabel til at gemme summen. Vink: Brug `let sum = 0;` øverst i din kode.
e) Tilføj en hændelsesbehandler til knappen. Vink: Brug `onEvent()`.
f) Når knappen trykkes skal de to tal hentes fra tekstinputfelterne, gemmes i variablerne, og summen beregnes og vises i etiketten. Vink: Brug `setText()` til at opdatere etiketten. Konverter tekst til tal ved at bruge `parseInt()` eller `Number()`.


## Vis en besked

a) Tilføje en knap og en etiket.
b) Tilføj en hændelsesbehandler til knappen. Vink: Brug `onEvent()`.
c) Når knappen trykkes skal der vises en besked i etiketten (f.eks. "Hej Verden!"). Vink: Brug `setText()` til at opdatere etiketten.

## Vis en besked baseret på brugerinput

a) Tilføj et tekstinputfelt, en knap og en etiket. Vink: Brug `TextInput`, `Button` og `Label` komponenterne.
b) Tilføj en hændelsesbehandler til knappen. Vink: Brug `onEvent()`.
c) Når knappen trykkes skal teksten fra tekstinputfeltet hentes og vises i etiketten. Vink: Brug `getText()` til at hente teksten og `setText()` til at opdatere etiketten.

## Skift baggrundsfarve

a) Tilføj tre knapper: Rød, Grøn, Blå. Vink: Brug `Button` komponenten. 
b) Tilføj en hændelsesbehandler til hver knap. Vink: Brug `onEvent()`.
c) Når en knap trykkes skal baggrundsfarven ændres til den valgte farve. Vink: Brug `setProperty()` til at ændre baggrundsfarven.

## Tæl klik

a) Tilføj en knap og en etiket.
b) Opret en variabel `antalKlik`, som starter på 0. Vink: Brug `let antalKlik = 0;` øverst i din kode
c) Hver gang knappen trykkes skal `antalKlik` øges med 1, og den nye værdi skal vises i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Tilføj `antalKlik = antalKlik + 1;` inde i hændelsesbehandleren.

## Rabatberegner

a) Tilføj to tekstinputfelter til pris og rabatprocent. Vink: Brug `TextInput` komponenten.
b) Tilføj to variabler til at gemme pris og rabatprocent. Vink: Brug `let pris = 0;` og `let rabatProcent = 0;` øverst i din kode.
c) Tilføj en variabel til at gemme den endelige pris. Vink: Brug `let endeligPris = 0;` øverst i din kode.
d) Beregn den endelige pris med formlen: `endeligPris = pris - (pris * (rabatProcent / 100));`
e) Tilføj en knap og en etiket til at vise den endelige pris. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten.
f) Når knappen trykkes skal den endelige pris beregnes og vises i etiketten.

## BMI-beregner

a) Tilføj to tekstinputfelter til vægt (i kg) og højde (i meter). Vink: Brug `TextInput` komponenten.
b) Tilføj to variabler til at gemme vægt og højde. Vink: Brug `let vaegt = 0;` og `let hoejde = 0;` øverst i din kode.
c) Tilføj en variabel til at gemme BMI. Vink: Brug `let bmi = 0;` øverst i din kode.
d) Beregn BMI med formlen: `bmi = vaegt / (hoejde * hoejde);`
e) Tilføj en knap og en etiket til at vise BMI.
f) Når knappen trykkes skal BMI beregnes og vises i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten.

## Antal kalorier

a) Tilføj tre tekstinputfelter til fedt, kulhydrater og protein (i gram) og tre variabler til at gemme disse værdier. Vink: Brug `let fedtGram = 0;`, `let kulhydratGram = 0;`, `let proteinGram = 0;` øverst i din kode.
b) Tilføj tre variabler til at gemme kalorier pr. gram for hver makronæringsstof. Vink: Brug `let fedtKalorierPrGram = 9;`, `let kulhydratKalorierPrGram = 4;`, `let proteinKalorierPrGram = 4;` øverst i din kode.
c) Tilføj en knap og en etiket til at vise det samlede antal kalorier.
d) Når knappen trykkes skal det samlede antal kalorier beregnes og vises i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Beregn kalorier med formlen: `let samletKalorier = (fedtGram * fedtKalorierPrGram) + (kulhydratGram * kulhydratKalorierPrGram) + (proteinGram * proteinKalorierPrGram);`

## Gæt et tal

a) Opret en variabel `hemmeligtTal`, der indeholder et tilfældigt tal mellem 1 og 100. Vink: Brug `let hemmeligtTal = randomNumber(1, 100);` øverst i din kode.
b) Tilføj et tekstinputfelt til brugerens gæt og en variabel til at gemme dette gæt. Vink: Brug `let brugerGaet = 0;` øverst i din kode.
c) Tilføj en knap og en etiket til at vise beskeder til brugeren.
d) Når knappen trykkes → skal programmet kontrollere brugerens gæt mod `hemmeligtTal` og vise passende beskeder i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug betingede udførsler til at give feedback:

- Hvis brugerGaet er mindre end hemmeligtTal → vis "For lavt! Prøv igen."
- Hvis brugerGaet er større end hemmeligtTal → vis "For højt! Prøv igen."
- Hvis brugerGaet er lig med hemmeligtTal → vis "Tillykke! Du gættede rigtigt!".

Man kan tilføje en betinget udførsel i App Lab ved at bruge `if`, `else if` og `else` blokke i kodeeditoren.


## Rabat hvis beløbet er over 500

a) Tilføj et tekstinputfelt til beløb og en variabel til at gemme dette beløb. Vink: Brug `let beloeb = 0;` øverst i din kode.
b) Tilføj en variabel til at gemme den endelige pris. Vink: Brug `let endeligPris = 0;` øverst i din kode.
c) Tilføj en variabel til at gemme rabatprocenten (10%). Vink: Brug `let rabatProcent = 0.10;` øverst i din kode.
d) Tilføj en knap og en etiket til at vise den endelige pris.
e) Når knappen trykkes → skal programmet kontrollere beløbet og anvende en rabat på 10%, hvis beløbet er over 500. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug betingede udførsler (benyt `if/else`) til at beregne den endelige pris:
- Hvis beloeb er større end 500 → beregn endeligPris som beloeb - (beloeb * 0.10).
- Ellers → endeligPris er lig med beloeb.

Man kan tilføje en betinget udførsel i App Lab ved at bruge `if`, `else if` og `else` blokke i kodeeditoren.

## Temperaturkonvertering

a) Tilføj et tekstinputfelt til temperatur i Celsius og en variabel til at gemme denne temperatur. Vink: Brug `let celsius = 0;` øverst i din kode.
b) Tilføj en variabel til at gemme temperaturen i Fahrenheit. Vink: Brug `let fahrenheit = 0;` øverst i din kode.
c) Tilføj en knap og en etiket til at vise temperaturen i Fahrenheit.
d) Når knappen trykkes → skal programmet konvertere temperaturen fra Celsius til Fahrenheit og vise resultatet i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug formlen: `fahrenheit = (celsius * 9/5) + 32;`

## Harris-Benedict-ligningen for mænd/kvinder 

a) Tilføj tre tekstinputfelter til vægt (i kg), højde (i cm) og alder (i år) samt en dropdown-menu til at vælge køn (mand/kvinde). Vink: Brug `TextInput` og `Dropdown` komponenterne.
b) Tilføj fire variabler til at gemme vægt, højde, alder og køn. Vink: Brug `let vaegt = 0;`, `let hoejde = 0;`, `let alder = 0;` og `let koen = "";` øverst i din kode.
c) Tilføj en variabel til at gemme det daglige kaloriebehov. Vink: Brug `let kaloriebehov = 0;` øverst i din kode.
d) Tilføj en knap og en etiket til at vise det daglige kaloriebehov.
e) Når knappen trykkes skal programmet beregne det daglige kaloriebehov baseret på Harris-Benedict-ligningen og vise resultatet i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug betingede udførsler (benyt `if/else`) til at anvende den korrekte formel:
- Hvis køn er "mand" → brug formlen: `kaloriebehov = 88.362 + (13.397 * vaegt) + (4.799 * hoejde) - (5.677 * alder);`
- Ellers hvis køn er "kvinde" → brug formlen: `kaloriebehov = 447.593 + (9.247 * vaegt) + (3.098 * hoejde) - (4.330 * alder);`

## Find største tal

a) Tilføj to tekstinputfelter til tal og to variabler til at gemme disse tal. Vink: Brug `let tal1 = 0;` og `let tal2 = 0;` øverst i din kode.
b) Tilføj en knap og en etiket til at vise det største tal.
c) Når knappen trykkes → skal programmet sammenligne de to tal og vise det største i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug betingede udførsler (benyt `if/else`) til at finde det største tal:
- Hvis tal1 er større end tal2 → vis tal1.
- Ellers hvis tal2 er større end tal1 → vis tal2.

## Multiplikationstabel

a) Tilføj et tekstinputfelt til et tal og en variabel til at gemme dette tal. Vink: Brug `let tal = 0;` øverst i din kode.
b) Tilføj en knap og en etiket til at vise multiplikationstabellen.
c) Når knappen trykkes → skal programmet generere og vise multiplikationstabellen for det indtastede tal (fra 1 til 10) i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug en løkke (for-løkke) til at generere tabellen og opbygge en tekststreng, der indeholder resultaterne.

## Udskriv liste af byer

a) Opret en liste (array) med mindst fem bynavne. Vink: Brug `let byer = ["København", "Aarhus", "Odense", "Aalborg", "Esbjerg"];` øverst i din kode.
b) Tilføj en knap og en etiket til at vise byerne.
c) Når knappen trykkes skal programmet gennemgå listen og vise alle byer i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug en løkke (for-løkke) til at gennemgå listen og opbygge en tekststreng med bynavnene.


## Lommeregner

a) Tilføj to tekstinputfelter til tal og en variabel til at gemme hvert tal. Vink: Brug `let tal1 = 0;` og `let tal2 = 0;` øverst i din kode.
b) Tilføj fire knapper til de grundlæggende operationer: Addition, Subtraktion, Multiplikation og Division.
c) Tilføj en etiket til at vise resultatet.
d) Opret fire funktioner: addere(), subtrahere(), multiplicere() og dividere(). Hver funktion skal tage to parametre og returnere resultatet af den tilsvarende operation. Vink: Tilføj funktionerne øverst i din kode. Definér dem som f.eks. `function addere(a, b) { return a + b; }`, `function subtrahere(a, b) { return a - b; }` osv.
e) Når en af knapperne trykkes → skal funktionen kaldes med de to tal og resultatet vises i etiketten. Vink: Brug `onEvent()` til hver knap og `setText()` til etiketten.

## Tælle til 10

a) Tilføj en knap og en etiket.
b) Når knappen trykkes skal en løkke tælle fra 1 til 10, og hvert tal skal vises i etiketten med et mellemrum imellem. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug en for-løkke til at tælle og opbygge en tekststreng med tallene.

## Udskrive alle varer fra en indkøbskurv

a) Opret en liste (array) med mindst fem vare-navne. Vink: Brug `let varer = ["Æbler", "Bananer", "Appelsiner", "Druer", "Jordbær"];` øverst i din kode.
b) Tilføj en knap og en etiket til at vise varerne.
c) Når knappen trykkes skal programmet gennemgå listen og vise alle varer i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug en løkke (for-løkke) til at gennemgå listen og opbygge en tekststreng med varenavnene.
d) Udvidelse: Tilføj en tekstinputfelt, hvor brugeren kan indtaste et nyt varenavn, og en knap til at tilføje dette varenavn til listen. Når denne knap trykkes, skal det nye varenavn tilføjes til listen, og den opdaterede liste skal vises i etiketten. Vink: Brug `push()` metoden til at tilføje det nye varenavn til listen.
e) Udvidelse: Tilføj en knap til at rydde listen. Når denne knap trykkes, skal listen tømmes, og etiketten skal opdateres til at vise en tom liste. Vink: Sæt listen til en tom liste ved at bruge `varer = [];`.

## Udskrive varer og deres priser

a) Opret et objekt med mindst fem nøgle-værdi par (f.eks. frugt og deres pris). Vink: Brug `let frugtPriser = { "Æbler": 3, "Bananer": 2, "Appelsiner": 4, "Druer": 5, "Jordbær": 6 };` øverst i din kode.
b) Tilføj en knap og en etiket til at vise nøgle-værdi parrene.
c) Når knappen trykkes skal programmet gennemgå objektet og vise alle nøgle-værdi par i etiketten. Vink: Brug `onEvent()` til knappen og `setText()` til etiketten. Brug en for-in løkke til at gennemgå objektet og opbygge en tekststreng med nøgle-værdi parrene.





<!--

## 5. Emoji-vælger

Lav 3 knapper og et tekstfelt.
Opgave:

    Tryk på “glad” → vis 😀

    Tryk på “sur” → vis 😠

    Tryk på “træt” → vis 😴


## 6. Funktionen "Blinkende Knap" (Funktioner & betingede udførsler)

Mål: Opret en funktion, der ændrer en knaps farve baseret på dens nuværende farve, når den klikkes.

    Opsætning:

        Opret en knap (Button) med ID'et blinkKnap.

        Opret en tekstboks (Label) med ID'et statusBoks.

    Funktion:

        Definér en funktion kaldet toggleColor() uden parametre.

        Inden i funktionen skal du bruge getComputedStyle() eller en variabel til at kontrollere knappens nuværende baggrundsfarve.

        Brug en betinget udførsel (if/else) til at skifte farve:

            HVIS farven er "rød", sæt den til "blå" og opdater statusBoks til "Blå er valgt".

            ELLERS (hvis farven ikke er "rød"), sæt den til "rød" og opdater statusBoks til "Rød er valgt".

    Hændelsesstyring:

        Brug onEvent til at kalde toggleColor()-funktionen, når der klikkes på blinkKnap.

 
## 7. Score-Tæller med Grænse (Variabler & Betingede Udførsler)

Mål: Lav en simpel score-tæller, der stopper ved en bestemt grænse.

    Opsætning:

        Opret en tekstboks (Label) med ID'et scoreLabel til at vise scoren.

        Opret en knap (Button) med ID'et plusEtKnap.

    Variabler:

        Initialisér en global variabel kaldet score til 0.

        Initialisér en global variabel kaldet maxScore til 10.

    Hændelsesstyring:

        Brug onEvent til at lytte efter klik på plusEtKnap.

        Inden i hændelsesbehandleren:

            Brug en betinget udførsel (if):

                HVIS score er mindre end maxScore, så forøg score med 1 og opdater scoreLabel.

                ELLERS (else), sæt teksten på scoreLabel til "Spillet er slut!" eller "Max score nået!".

 
## 8. Gentagen Tegning (Løkker & Funktioner)

Mål: Opret en funktion, der bruger en løkke til at tegne et gentaget mønster (f.eks. kvadrater eller cirkler) på skærmen.

    Opsætning:

        Skift til Canvas-visning (setScreen("screen1") og setCanvas("myCanvas")).

    Funktion:

        Definér en funktion kaldet drawPattern(numItems).

    Løkke:

        Inden i funktionen skal du bruge en for-løkke (for) til at gentage en tegnehandling numItems gange.

        I hver iteration af løkken:

            Vælg en tilfældig farve (randomNumber(0, 255) for RGB-komponenter).

            Tegn en form (f.eks. et kvadrat ved hjælp af rect() eller en cirkel ved hjælp af circle()). Sørg for at ændre formens position i hver iteration, f.eks. ved at multiplicere løkkevariablen (i) med en afstand.

    Udførsel:

        Kald funktionen drawPattern(10) for at tegne 10 elementer.

 
## 9. Timer med Betingelser (Variabler, Løkker/Tidsstyring & Betingede Udførsler)

Mål: Lav en nedtællingstimer, der udfører forskellige handlinger, når tiden er under et bestemt niveau.

    Opsætning:

        Opret en tekstboks (Label) med ID'et timerLabel til at vise den resterende tid.

        Initialisér en global variabel kaldet nedtaelling til 60.

    Tidsstyring/Løkke:

        Brug timedLoop(1000, function() { ... }) til at køre en funktion hvert sekund.

    Logik:

        Inden i timedLoop-funktionen:

            Formindsk nedtaelling med 1.

            Opdater timerLabel med den nye værdi.

            Brug betingede udførsler (if/else if/else):

                HVIS nedtaelling er lig med 0, stop løkken (stopTimedLoop()) og vis "Tiden er gået!".

                ELLERS HVIS nedtaelling er mindre end 10, skift baggrundsfarven til "rød" for at signalere, at tiden er ved at løbe ud.

                ELLERS (hvis tiden er over 10), skift baggrundsfarven tilbage til "blå" eller en anden standardfarve.

 
## 10. Beregning med Funktioner og Brugerinput (Funktioner & Variabler)

Mål: Opret en app, hvor brugeren indtaster to tal, og en funktion beregner resultatet.

    Opsætning:

        Opret to tekstinputfelter (TextInput) med ID'erne tal1Input og tal2Input.

        Opret en knap (Button) med ID'et beregnKnap.

        Opret en tekstboks (Label) med ID'et resultatLabel til at vise resultatet.

    Funktion:

        Definér en funktion kaldet calculateSum(a, b) der tager to parametre.

        Funktionen skal returnere summen af de to parametre.

    Hændelsesstyring:

        Brug onEvent til at lytte efter klik på beregnKnap.

        Inden i hændelsesbehandleren:

            Hent værdierne fra tal1Input og tal2Input ved hjælp af getText(). Husk at konvertere strengværdierne til tal ved hjælp af parseInt() eller Number(). Gem disse i lokale variabler.

            Kald funktionen calculateSum() med de hentede tal.

            Vis resultatet i resultatLabel ved hjælp af setText().

-->