# Programmering

## Opgaver i App Lab

### 1. Skift skærm

Lav to skærme.
Opgave: Når man trykker på en knap på skærm 1 → skal appen skifte til skærm 2.


### 2. Vis en besked

Lav en knap og et tekstfelt.
Opgave: Når man trykker på knappen → skal teksten ændres til “Hej verden!”


### 3. Klik-tæller (uden variabler)

Lav tre etiketter med tallene 1, 2, 3.
Opgave: Hver knap viser en bestemt label, som om appen “tæller”.


### 4. Mini-farveskifter

Lav 3 knapper: Rød, Grøn, Blå.
Opgave: Når man trykker på en af knapperne → ændres baggrundsfarven til netop den farve.


### 5. Emoji-vælger

Lav 3 knapper og et tekstfelt.
Opgave:

    Tryk på “glad” → vis 😀

    Tryk på “sur” → vis 😠

    Tryk på “træt” → vis 😴


### 6. Funktionen "Blinkende Knap" (Funktioner & betingede udførsler)

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

 
### 7. Score-Tæller med Grænse (Variabler & Betingede Udførsler)

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

 
### 8. Gentagen Tegning (Løkker & Funktioner)

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

 
### 9. Timer med Betingelser (Variabler, Løkker/Tidsstyring & Betingede Udførsler)

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

 
### 10. Beregning med Funktioner og Brugerinput (Funktioner & Variabler)

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


