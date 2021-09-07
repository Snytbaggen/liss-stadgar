# Stadgerevidering

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
källkod. Vill man bygga en pdf själv kan man kopiera allt text i den till en LaTeX-redigerare, t ex MikTex
för Windows och Overleaf.com om man vill använda webben.

För att se historiken bakom alla ändringar kan man klicka uppe till höger vid alla filer där det står
"XX commits". Då får man upp en lista med rubriker på alla ändringar, klickar man på dem får man upp en
längre beskrivning samt exakt vad det är som ändrats sedan förra ändringen.

Om man vill se de oförändrade stadgarna så finns de som `stadgar_original.pdf`

## Saker att se över
Här kommer det skrivas saker som antagligen behöver ses över, med både mer och mindre utförliga beskrivningar.
Listan kommer kontinuerligt ses över och revideras under arbetets gång.

### Medlemskap
- Enl. nuvarande stadgar: "Medlem i Spexet är den som ansluter sig till Spexets syfte [...]"
  Exakt vad innebär det? Dvs, vad räknas som att ansluta sig? Det står ingenting om att man behöver bli
  invald eller godkänd någonstans, bara att man ska ha "anslutit sig till syftet", betalat medlemsavgift
  samt ha "varit medlem eller arbetar i en spexdirections organisation". Menar de då medlem i föreningen
  eller i en spexdirection? Som det är formulerat kan man dock inte ha blivit det förra utan att ha varit det
  senare, och det innebär även att om vi rekryterar nya folk utanför uppsättningen (t ex styrelsen) kan de
  inte bli medlemmar i föreningen.

- Vi har även medlemskap i uppsättningen utöver medlemskap i föreningen. Med tanke på att det innebär ganska 
  mycket att vara uppsättningsmedlem utöver föreningsmedlem är det något vi borde definiera någonsta i 
  stadgarna, förslagsvis under paragrafen om uppsättningar.
  
- Det finns ingen information om hur medlemmar kan begära utträde ut föreningen, bara att "funktionärer"
  (vilket jag antar är synonymt med förtroendevalda) kan bli entledigade av föreningsmötet. Standardformuleringen
  verkar vara "Medlem som önskar utträda ur föreningen ska skriftligen anmäla detta till styrelsen och anses 
  därmed omedelbart ha lämnat föreningen."
  
- Det står inget om att minst 51% av föreningens aktiva medlemmar behöver vara studenter, det är ett krav
  för att vara LUST-godkända.
  
- Uteslutning av medlemmar är något som också bör stå med. Förhoppningsvis är det något man aldrig behöver
  använda, men ifall situationen uppstår är det bra om det finns med i stadgarna.
  
### Styrelsen
- Just nu är det ett hårt krav på 4 ledamöter för att vara beslutsmässiga. Under normala år fungerar det bra,
  men ifall vi får ett år utan alla styrelseposter kan det bli ett problem. Ett förslag är att istället ha
  en formulering i stil med "Styrelsen är beslutsmässig om mer än hälften av styrelseledamöterna är
  närvarande". Vid en fullsatt styrelse gör det ingen skillnad, men om man får ett dåligt år kan det underlätta
  något enormt.
  
- Som det är skrivet __ska__ styrelsen bestå av alla sex poster, vilket också ställer till med problem ifall
  ett dåligt år skulle uppstå. En lösning kan vara att lägga till "i den mån posterna är tillsatta" för
  att gardera sig mot stadgeproblem i framtiden.
  
- Om styrelsen saknar poster kan det bli ett problem att fyllnadsvälja, eftersom stadgarna kräver ett
  medlemsmöte för att välja in styrelsemedlemmar. Ifall hela styrelsen inte kan tillsättas på ett
  föreningsmöte är (enligt min erfarenhet) att ge styrelsen rätt att fyllnadsvälja de vakanta posterna.
  Detta går att göras genom att man på föreningsmötet ger styrelsen rätt att göra det, men jag vill även
  ta upp att det är möjligt att skriva in det i stadgarna.
  
- En bra-att-ha-grej är möjligheten att ha slutna möten i samråd med revisorer, där bara styrelsen och
  revisorerna har närvarorätt. Protokollen från dessa möten hålls slutna i upp till ett år, men revisorerna
  kan rekommendera till föreningsmötet att de hålls slutna längre. Det ska bara användas i väldigt speciella
  och allvarliga fall, t ex vid brott som leder till polisanmälan. Det är också något som man förhoppningsvis
  aldrig behöver använda.
  
### Föreningsmöten
- Höstmötet är definierat som "det första föreningsmötet på andra kalenderhalvåret". Detta innebär att det
  inte finns någon möjlighet att ha extrainsatta föreningsmöten innan höstmötet, och eftersom det brukar hållas
  i början av oktober är det i princip tre månader där man inte kan ha extrainsatta föreningsmöten. Det borde
  formuleras om till typ "Höstmötet ska hållas under det andra kalenderhalvåret, före den 15e oktober".

### Firmatecknare
- Under "Styrelsen" står det att ordföranden och kassören är firmatecknare. Under "Directionen" står det även
  att directeuren och ekonomichefen har rätt att göra det. Det här borde läggas under samma punkt.
  
- Om vi något år skulle stå utan ordförande eller kassör så har vi inget stadgemässigt utrymme att utse andra
  firmatecknare. Ett förslag är att låta medlemsmötet utse två myndiga styrelseledamöter som firmatecknare,
  så går det att anpassa efter situationen om så krävs.

### Synopsisgruppen
- I nuläget är det formulerat att förslag ska "hemlighållas för andra än föreningens medlemmar". Det känns som 
  att det borde ändras, eftersom alla förslag brukar vara hemliga tills ett synopsis blivit valt och presenterat
  (antar jag)

### Valberedningen
- Valberedningens uppgifter är vagt beskrivna, och borde definieras lite bättre. Det står bara att valberedningen
  ska ta fram poster till föreningsmötet, men det borde klargöras om det innebär alla föreningsmöten eller
  bara vissa.

- Det vore bra med rutiner för vad som händer om någon ur valberedningen blir entledigad, eller väljer att
  gå ur föreningen. Vilka letar efter en ny kandidat, hur blir hen invald (fyllnadsval av styrelsen eller
  kallelse till nytt föreningsmöte), och så vidare.

- Eftersom valberedningen ska ta fram kandidater till föreningsmötet så innebär det att de inte ska hjälpa
  styrelsen med kandidater ifall styrelsen får rätt att fyllnadsvälja till poster. Personligen anser jag inte
  att det borde vara ett krav att ta fram kandidater i sådana lägen, eftersom ett sådant arbete ofta pågår
  under betydligt längre tid än ordinarie valberedningsarbete. Oavsett så bör det nog stå i stadgarna vad som
  gäller i sådana fall, om valberedningen ska ta fram kandidater, vara styrelsen till hjälp eller inte ha
  några förpliktelser.
  
### Revisorer
- Det borde vara tydligare att det finns föreningsrevisorer och uppsättningsrevisorer. Det är just nu väldigt
  otydligt och förvirrande skrivet ("Av föreningsmötet valda funktionärers arbete skall granskas av två 
  revisorer"). 
  
### Detaljstyrning av poster
- Något jag lagt märke till är att stadgarna har en del detaljstyre om vissa saker (t ex ska styrelsen "den 
  28 november varje år arrangera Spexets födelsedagskalas"). Vissa saker som berör styrelsen borde lika gärna
  kunna ligga i verksamhetsplanen, och postbeskrivningarna behöver nog ses över rent allmänt. I stadgarna
  borde det bara stå generella saker på en hög nivå, det är ett väldigt trögt dokument att ändra och skall
  vara den grund varpå spexet vilar. Det kan dock vara lite problematiskt att lösa eftersom informationen
  behöver finnas dokumenterad någonstans där det är bindande. I Holger har de löst det genom policydokument
  som refereras till i stadgarna och som är mycket enklare att ändra, men det är nog inte en lösning vi kan
  kopiera eftersom det skulle vara en väldigt stor omställning.