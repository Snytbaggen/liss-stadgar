# Hur vi arbetar

GitHub (och Git) är ett kraftfullt system med många finesser och funktioner, och kan lätt bli komplicerat. Målet är att få en bra balans mellan användbarhet och säkerhet, men det kommer ändå vara en tröskel att ta sig över. 

Grundidén är att man gör alla sina ändringar på en kopia av stadgarna, och sedan måste ändringarna granskas och godkännas innan de förs in i det skarpa dokumentet. Vi behöver även hålla koll på vad som behöver göras, och vem som arbetar på vad, och vi använder GitHubs interna issue-system för att hålla koll på det, samt för diskutera de enskilda uppgifterna.

Arbetsflödet kan förenklas till följande:

1) Skapa ett issue som beskriver det du vill diskutera eller arbeta på
2) Vi diskuterar issuet tills vi kommit överens om vad som ska göras
3) Börja arbeta med issuet på en separat kopia av stadgarna (en så kallad "branch")
4) Lägg upp ditt arbete för granskning när det är klart
5) Lägg till ditt arbete i stadgarna efter godkänd granskning

## GitHub for Dummies (och spexare)

För att underlätta de tekniska delarna så har jag (Häggmyr) försökt göra en så [användarvänlig guide som möjligt](https://docs.google.com/document/d/1AJucn3syRdK1GsDzpT_zzZFb5dVSZBni4vVxg6WR4u8/edit?usp=sharing), med bilder för varje steg i processen. 

Dokumentet ser nog mastigare ut än det egentligen är, och efter att man gjort sakerna en gång eller två borde man ha ganska bra koll på hur man bör göra. Om det är något som är oklart eller saknas så hör av er till mig, jag använder GitHub dagligen så det är väldigt lätt att bli hemmablind.

## Skapa och diskutera issues

Genom att klicka på [Issues](https://github.com/Snytbaggen/liss-stadgar/issues) kommer man till en lista med de saker som behöver diskuteras och/eller fixas.

De som är markerade med taggen "diskussion" är tänkta att diskuteras, antingen på ett möte eller direkt i kommentarerna på issuet. När konsensus har uppnåtts om vad som behövs göras kan taggen tas bort, och issuet antingen börja arbetas på eller stängas beroende på vad diskussionen landade i.

## Börja arbeta på ett issue (Issue board)

Genom att gå till "Projects" och klicka på "Stadgerevidering" ([direktlänk här](https://github.com/Snytbaggen/liss-stadgar/projects/1)) kan man se vilken status olika issues har.

De som ligger i "To do"-kolumnen och inte har en "diskussion"-flagga är redo att börja arbetas på. Ta tag i issuet du vill arbeta med och dra över det till "In progress"-kolumnen, så vi vet att någon arbetar på det. Du kan gärna markera dig själv som assigned på issuet också, och sedan kan du börja arbeta (se guiden för hur man gör dessa två saker).

När du arbetat färdigt ska du göra en "pull request" för att få in dina ändringar, se guiden för hur man gör det.

## Granskning av arbete (Pull requests)

Genom att klicka på [Pull requests](https://github.com/Snytbaggen/liss-stadgar/pulls) kommer du till en lista med de ändringar folk anser sig vara klara med och vill ha in i stadgarna.

Varje pull request behöver granskas och godkännas av två personer för att få föras in, så om du ser någon som behöver fler granskare är du fri att ta en närmare titt på den (se guiden för en mer detaljerad guide i hur granskningen går till).

Det går att kommentera på pull requesten även om man inte är granskare, så man behöver inte känna sig låst till att bara kommentera på de som man granskar.

Om du själv har lagt upp en pull request som sedan blivit godkänd är du fri att föra in den. Exakt hur du gör det står i guiden.

# Om projektet

Det här är ett pågående projekt att se över och redigera stadgarna. Stadgarna har blivit omskrivna till
LaTeX, och Git används för att enklare ha uppsikt över vad som sker och i vilken ordning.

Grovt uppdelat sker revideringen i tre steg:

**1. Upprensning och formatering**

Syftet med det här steget är att få stadgarna till en mer homogen och lättläst form, men utan någon
skillnad i innehållet. Förlegade saker tas bort, strukturer ändras och vissa uttryck byts ut och/eller
standardiseras i dokumentet.

**2. Omskrivning av nuvarande stadgar**

Det nuvarande språket kan vara ganska tungt och svårläst ("Av föreningsmötet valda funktionärers arbete 
skall granskas [...]"), och steg 2 kommer vara att skriva om dem till en mer lättläst form utan att
göra några stora förändringar i hur de fungerar

**3. Stadgeändringar och nya stadgar**

Här skrivs stadgarna om, hål täpps till och nya saker tillkommer. Punkt 1 och 2 handlar egentligen om att
komma till det här stadiet, där det riktiga arbetet börjar.

Ambitionen är att hålla det så uppdelat som möjligt, men framför allt del 1 och 2 kommer ske med ett
visst överlapp.

## Hur man visar stadgarna
Stadgarna är omskrivna till LaTeX, och behöver kompileras till en PDF för att se snygga ut. Det ska finnas
en fil som heter `stadgar.pdf` som är den senaste versionen av dem, och `stadgar.tex` innehåller all
källkod. Vill man bygga en pdf själv kan man kopiera allt text i den till en LaTeX-redigerare, t ex TeXworks
för Windows och Overleaf.com om man vill använda webben.

För att se historiken bakom alla ändringar kan man klicka uppe till höger vid alla filer där det står
"XX commits". Då får man upp en lista med rubriker på alla ändringar, klickar man på dem får man upp en
längre beskrivning samt exakt vad det är som ändrats sedan förra ändringen.

Om man vill se de oförändrade stadgarna så finns de som `stadgar_original.pdf`
