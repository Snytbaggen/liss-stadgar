# Stadgerevidering

Det h�r �r ett p�g�ende projekt att se �ver och redigera stadgarna. Stadgarna har blivit omskrivna till
LaTeX, och Git anv�nds f�r att enklare ha uppsikt �ver vad som sker och i vilken ordning.

Grovt uppdelat sker revideringen i tre steg:

**1. Upprensning och formatering**

Syftet med det h�r steget �r att f� stadgarna till en mer homogen och l�ttl�st form, men utan n�gon
skillnad i inneh�llet. F�rlegade saker tas bort, strukturer �ndras och vissa uttryck byts ut och/eller
standardiseras i dokumentet.

**2. Omskrivning av nuvarande stadgar**

Det nuvarande spr�ket kan vara ganska tungt och sv�rl�st ("Av f�reningsm�tet valda funktion�rers arbete 
skall granskas [...]"), och steg 2 kommer vara att skriva om dem till en mer l�ttl�st form utan att
g�ra n�gra stora f�r�ndringar i hur de fungerar

**3. Stadge�ndringar och nya stadgar**

H�r skrivs stadgarna om, h�l t�pps till och nya saker tillkommer. Punkt 1 och 2 handlar egentligen om att
komma till det h�r stadiet, d�r det riktiga arbetet b�rjar.

Ambitionen �r att h�lla det s� uppdelat som m�jligt, men framf�r allt del 1 och 2 kommer ske med ett
visst �verlapp.

## Hur man visar stadgarna
Stadgarna �r omskrivna till LaTeX, och beh�ver kompileras till en PDF f�r att se snygga ut. Det ska finnas
en fil som heter `stadgar.pdf` som �r den senaste versionen av dem, och `stadgar.tex` inneh�ller all
k�llkod. Vill man bygga en pdf sj�lv kan man kopiera allt text i den till en LaTeX-redigerare, t ex MikTex
f�r Windows och Overleaf.com om man vill anv�nda webben.

F�r att se historiken bakom alla �ndringar kan man klicka uppe till h�ger vid alla filer d�r det st�r
"XX commits". D� f�r man upp en lista med rubriker p� alla �ndringar, klickar man p� dem f�r man upp en
l�ngre beskrivning samt exakt vad det �r som �ndrats sedan f�rra �ndringen.

Om man vill se de of�r�ndrade stadgarna s� finns de som `stadgar_original.pdf`

## Saker att se �ver
H�r kommer det skrivas saker som antagligen beh�ver ses �ver, med b�de mer och mindre utf�rliga beskrivningar.
Listan kommer kontinuerligt ses �ver och revideras under arbetets g�ng.

### Medlemskap
- Enl. nuvarande stadgar: "Medlem i Spexet �r den som ansluter sig till Spexets syfte [...]"
  Exakt vad inneb�r det? Dvs, vad r�knas som att ansluta sig? Det st�r ingenting om att man beh�ver bli
  invald eller godk�nd n�gonstans, bara att man ska ha "anslutit sig till syftet", betalat medlemsavgift
  samt ha "varit medlem eller arbetar i en spexdirections organisation". Menar de d� medlem i f�reningen
  eller i en spexdirection? Som det �r formulerat kan man dock inte ha blivit det f�rra utan att ha varit det
  senare, och det inneb�r �ven att om vi rekryterar nya folk utanf�r upps�ttningen (t ex styrelsen) kan de
  inte bli medlemmar i f�reningen.

- Vi har �ven medlemskap i upps�ttningen ut�ver medlemskap i f�reningen. Med tanke p� att det inneb�r ganska 
  mycket att vara upps�ttningsmedlem ut�ver f�reningsmedlem �r det n�got vi borde definiera n�gonsta i 
  stadgarna, f�rslagsvis under paragrafen om upps�ttningar.
  
- Det finns ingen information om hur medlemmar kan beg�ra uttr�de ut f�reningen, bara att "funktion�rer"
  (vilket jag antar �r synonymt med f�rtroendevalda) kan bli entledigade av f�reningsm�tet. Standardformuleringen
  verkar vara "Medlem som �nskar uttr�da ur f�reningen ska skriftligen anm�la detta till styrelsen och anses 
  d�rmed omedelbart ha l�mnat f�reningen."
  
- Det st�r inget om att minst 51% av f�reningens aktiva medlemmar beh�ver vara studenter, det �r ett krav
  f�r att vara LUST-godk�nda.
  
- Uteslutning av medlemmar �r n�got som ocks� b�r st� med. F�rhoppningsvis �r det n�got man aldrig beh�ver
  anv�nda, men ifall situationen uppst�r �r det bra om det finns med i stadgarna.
  
### Styrelsen
- Just nu �r det ett h�rt krav p� 4 ledam�ter f�r att vara beslutsm�ssiga. Under normala �r fungerar det bra,
  men ifall vi f�r ett �r utan alla styrelseposter kan det bli ett problem. Ett f�rslag �r att ist�llet ha
  en formulering i stil med "Styrelsen �r beslutsm�ssig om mer �n h�lften av styrelseledam�terna �r
  n�rvarande". Vid en fullsatt styrelse g�r det ingen skillnad, men om man f�r ett d�ligt �r kan det underl�tta
  n�got enormt.
  
- Som det �r skrivet __ska__ styrelsen best� av alla sex poster, vilket ocks� st�ller till med problem ifall
  ett d�ligt �r skulle uppst�. En l�sning kan vara att l�gga till "i den m�n posterna �r tillsatta" f�r
  att gardera sig mot stadgeproblem i framtiden.
  
- Om styrelsen saknar poster kan det bli ett problem att fyllnadsv�lja, eftersom stadgarna kr�ver ett
  medlemsm�te f�r att v�lja in styrelsemedlemmar. Ifall hela styrelsen inte kan tills�ttas p� ett
  f�reningsm�te �r (enligt min erfarenhet) att ge styrelsen r�tt att fyllnadsv�lja de vakanta posterna.
  Detta g�r att g�ras genom att man p� f�reningsm�tet ger styrelsen r�tt att g�ra det, men jag vill �ven
  ta upp att det �r m�jligt att skriva in det i stadgarna.
  
- En bra-att-ha-grej �r m�jligheten att ha slutna m�ten i samr�d med revisorer, d�r bara styrelsen och
  revisorerna har n�rvaror�tt. Protokollen fr�n dessa m�ten h�lls slutna i upp till ett �r, men revisorerna
  kan rekommendera till f�reningsm�tet att de h�lls slutna l�ngre. Det ska bara anv�ndas i v�ldigt speciella
  och allvarliga fall, t ex vid brott som leder till polisanm�lan. Det �r ocks� n�got som man f�rhoppningsvis
  aldrig beh�ver anv�nda.
  
### F�reningsm�ten
- H�stm�tet �r definierat som "det f�rsta f�reningsm�tet p� andra kalenderhalv�ret". Detta inneb�r att det
  inte finns n�gon m�jlighet att ha extrainsatta f�reningsm�ten innan h�stm�tet, och eftersom det brukar h�llas
  i b�rjan av oktober �r det i princip tre m�nader d�r man inte kan ha extrainsatta f�reningsm�ten. Det borde
  formuleras om till typ "H�stm�tet ska h�llas under det andra kalenderhalv�ret, f�re den 15e oktober".

### Firmatecknare
- Under "Styrelsen" st�r det att ordf�randen och kass�ren �r firmatecknare. Under "Directionen" st�r det �ven
  att directeuren och ekonomichefen har r�tt att g�ra det. Det h�r borde l�ggas under samma punkt.
  
- Om vi n�got �r skulle st� utan ordf�rande eller kass�r s� har vi inget stadgem�ssigt utrymme att utse andra
  firmatecknare. Ett f�rslag �r att l�ta medlemsm�tet utse tv� myndiga styrelseledam�ter som firmatecknare,
  s� g�r det att anpassa efter situationen om s� kr�vs.

### Synopsisgruppen
- I nul�get �r det formulerat att f�rslag ska "hemligh�llas f�r andra �n f�reningens medlemmar". Det k�nns som 
  att det borde �ndras, eftersom alla f�rslag brukar vara hemliga tills ett synopsis blivit valt och presenterat
  (antar jag)

### Valberedningen
- Valberedningens uppgifter �r vagt beskrivna, och borde definieras lite b�ttre. Det st�r bara att valberedningen
  ska ta fram poster till f�reningsm�tet, men det borde klarg�ras om det inneb�r alla f�reningsm�ten eller
  bara vissa.

- Det vore bra med rutiner f�r vad som h�nder om n�gon ur valberedningen blir entledigad, eller v�ljer att
  g� ur f�reningen. Vilka letar efter en ny kandidat, hur blir hen invald (fyllnadsval av styrelsen eller
  kallelse till nytt f�reningsm�te), och s� vidare.

- Eftersom valberedningen ska ta fram kandidater till f�reningsm�tet s� inneb�r det att de inte ska hj�lpa
  styrelsen med kandidater ifall styrelsen f�r r�tt att fyllnadsv�lja till poster. Personligen anser jag inte
  att det borde vara ett krav att ta fram kandidater i s�dana l�gen, eftersom ett s�dant arbete ofta p�g�r
  under betydligt l�ngre tid �n ordinarie valberedningsarbete. Oavsett s� b�r det nog st� i stadgarna vad som
  g�ller i s�dana fall, om valberedningen ska ta fram kandidater, vara styrelsen till hj�lp eller inte ha
  n�gra f�rpliktelser.
  
### Revisorer
- Det borde vara tydligare att det finns f�reningsrevisorer och upps�ttningsrevisorer. Det �r just nu v�ldigt
  otydligt och f�rvirrande skrivet ("Av f�reningsm�tet valda funktion�rers arbete skall granskas av tv� 
  revisorer"). 
  
### Detaljstyrning av poster
- N�got jag lagt m�rke till �r att stadgarna har en del detaljstyre om vissa saker (t ex ska styrelsen "den 
  28 november varje �r arrangera Spexets f�delsedagskalas"). Vissa saker som ber�r styrelsen borde lika g�rna
  kunna ligga i verksamhetsplanen, och postbeskrivningarna beh�ver nog ses �ver rent allm�nt. I stadgarna
  borde det bara st� generella saker p� en h�g niv�, det �r ett v�ldigt tr�gt dokument att �ndra och skall
  vara den grund varp� spexet vilar. Det kan dock vara lite problematiskt att l�sa eftersom informationen
  beh�ver finnas dokumenterad n�gonstans d�r det �r bindande. I Holger har de l�st det genom policydokument
  som refereras till i stadgarna och som �r mycket enklare att �ndra, men det �r nog inte en l�sning vi kan
  kopiera eftersom det skulle vara en v�ldigt stor omst�llning.