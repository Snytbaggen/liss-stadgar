# Hur vi arbetar

GitHub (och Git) �r ett kraftfullt system med m�nga finesser och funktioner, och kan l�tt bli komplicerat. M�let �r att f� en bra balans mellan anv�ndbarhet och s�kerhet, men det kommer �nd� vara en tr�skel att ta sig �ver. 

Grundid�n �r att man g�r alla sina �ndringar p� en kopia av stadgarna, och sedan m�ste �ndringarna granskas och godk�nnas innan de f�rs in i det skarpa dokumentet. Vi beh�ver �ven h�lla koll p� vad som beh�ver g�ras, och vem som arbetar p� vad, och vi anv�nder GitHubs interna issue-system f�r att h�lla koll p� det, samt f�r diskutera de enskilda uppgifterna.

Arbetsfl�det kan f�renklas till f�ljande:

1) Skapa ett issue som beskriver det du vill diskutera eller arbeta p�
2) Vi diskuterar issuet tills vi kommit �verens om vad som ska g�ras
3) B�rja arbeta med issuet p� en separat kopia av stadgarna (en s� kallad "branch")
4) L�gg upp ditt arbete f�r granskning n�r det �r klart
5) L�gg till ditt arbete i stadgarna efter godk�nd granskning

## GitHub for Dummies (och spexare)

F�r att underl�tta de tekniska delarna s� har jag (H�ggmyr) f�rs�kt g�ra en s� [anv�ndarv�nlig guide som m�jligt](https://docs.google.com/document/d/1AJucn3syRdK1GsDzpT_zzZFb5dVSZBni4vVxg6WR4u8/edit?usp=sharing), med bilder f�r varje steg i processen. 

Dokumentet ser nog mastigare ut �n det egentligen �r, och efter att man gjort sakerna en g�ng eller tv� borde man ha ganska bra koll p� hur man b�r g�ra. Om det �r n�got som �r oklart eller saknas s� h�r av er till mig, jag anv�nder GitHub dagligen s� det �r v�ldigt l�tt att bli hemmablind.

## Skapa och diskutera issues

Genom att klicka p� [Issues](https://github.com/Snytbaggen/liss-stadgar/issues) kommer man till en lista med de saker som beh�ver diskuteras och/eller fixas.

De som �r markerade med taggen "diskussion" �r t�nkta att diskuteras, antingen p� ett m�te eller direkt i kommentarerna p� issuet. N�r konsensus har uppn�tts om vad som beh�vs g�ras kan taggen tas bort, och issuet antingen b�rja arbetas p� eller st�ngas beroende p� vad diskussionen landade i.

## B�rja arbeta p� ett issue (Issue board)

Genom att g� till "Projects" och klicka p� "Stadgerevidering" ([direktl�nk h�r](https://github.com/Snytbaggen/liss-stadgar/projects/1)) kan man se vilken status olika issues har.

De som ligger i "To do"-kolumnen och inte har en "diskussion"-flagga �r redo att b�rja arbetas p�. Ta tag i issuet du vill arbeta med och dra �ver det till "In progress"-kolumnen, s� vi vet att n�gon arbetar p� det. Du kan g�rna markera dig sj�lv som assigned p� issuet ocks�, och sedan kan du b�rja arbeta (se guiden f�r hur man g�r dessa tv� saker).

N�r du arbetat f�rdigt ska du g�ra en "pull request" f�r att f� in dina �ndringar, se guiden f�r hur man g�r det.

## Granskning av arbete (Pull requests)

Genom att klicka p� [Pull requests](https://github.com/Snytbaggen/liss-stadgar/pulls) kommer du till en lista med de �ndringar folk anser sig vara klara med och vill ha in i stadgarna.

Varje pull request beh�ver granskas och godk�nnas av tv� personer f�r att f� f�ras in, s� om du ser n�gon som beh�ver fler granskare �r du fri att ta en n�rmare titt p� den (se guiden f�r en mer detaljerad guide i hur granskningen g�r till).

Det g�r att kommentera p� pull requesten �ven om man inte �r granskare, s� man beh�ver inte k�nna sig l�st till att bara kommentera p� de som man granskar.

Om du sj�lv har lagt upp en pull request som sedan blivit godk�nd �r du fri att f�ra in den. Exakt hur du g�r det st�r i guiden.