# Formel 1

Formel 1 set ovenfra i TV-stil – til mobil og browser.

**Spil:** https://seranodk.github.io/Formel1/

Kør **Hurtig løb** mod de 21 andre kørere, **Træning** alene mod din egen spøgelsesbil, eller en hel **Sæson** med point og VM-stilling gennem alle 23 baner i 2026-kalenderens rækkefølge med alle 22 kørere fra de 11 hold. Banerne er bygget ud fra de rigtige layouts: gadebaner med mure tæt på asfalten og natløb under projektører.

## Sådan spiller du
- **◀ ▶** nederst til venstre drejer bilen.
- **GAS** sidder til højre. Slip gassen for at bremse før svingene.
- Kameraet følger bilen. Der er ingen styrehjælp – du styrer selv.
- Sidder bilen fast mod en mur, bakker den selv lidt.
- Tastatur: piletaster / WASD, ↓ = bak, P = pause.

Under **Indstillinger** vælger du antal omgange og lyd.

## Baner
| Bane | Land | Type |
|---|---|---|
| Red Bull Ring | Østrig | Park |
| Monaco | Monaco | Gadebane |
| Silverstone | Storbritannien | Park |
| Spa-Francorchamps | Belgien | Skov |
| Monza | Italien | Skov |
| Suzuka | Japan | Park (otte-tal med bro) |
| Marina Bay | Singapore | Gadebane, natløb |
| Las Vegas | USA | Gadebane, natløb |
| Interlagos | Brasilien | Park |
| Yas Marina | Abu Dhabi | Ørken, natløb |

## Tidsgrafik
Sektortider vises i TV-farverne: **lilla** er ny banerekord, **grøn** er personlig bedste i løbet, og **gul** er langsommere. Rekorderne gemmes på enheden for hver bane.

## Filer
- `index.html` – nyeste version (det er den, der spilles)
- `versioner/` – alle tidligere versioner som selvstændige HTML-filer

## Versionslog
- **v0.23** – Modstanderne kører den ideelle linje og bremser ved at slippe gassen, ligesom man selv gør. Deres fart måles mod en meget god omgang på hver bane eller mod din egen rekord, hvis den er hurtigere. *Normale* er nu omkring 10 % hurtigere end før og ligger på højde med en meget god spiller, mens *Svære* er 3–4 % hurtigere end det. *Lette* er som før.
- **v0.22** – Nye sværhedsgrader: *Lette* er de gamle normale modstandere, *Normale* (standard) er lidt bedre, og *Svære* er markant hurtigere i svingene og ud af dem, så det er svært at vinde.
- **v0.21** – Modstandere: de 21 andre kørere starter fra et grid på 22 biler, kører med deres holds rigtige fart og kan overhale hinanden og dig. Slipstrøm bag en bil på langsiderne. Placering live i infobjælken og et lille tidstårn (bilen foran og bagved). Sværhedsgrad under Indstillinger. Resultatliste med point (25-18-15…), og i sæsonen VM-stilling for kørere og konstruktører med pokal efter sidste løb. Ny **Træning**: kør alene med ubegrænsede omgange mod en spøgelsesbil af din bedste omgang på banen, med tidsforskel live.
- **v0.20** – Alle 23 løb i 2026-kalenderen kan køres. 13 nye baner: Australien, Kina, Miami, Canada, Barcelona, Ungarn, Holland, Spanien (Madring), Aserbajdsjan (Baku), Bahrain (kørt på Sepang), USA (COTA), Mexico og Qatar (natløb). Alle har samme brede bane, så der er plads til at overhale. Sæsonen har nu 23 runder i kalenderens rækkefølge, og en påbegyndt sæson bliver bevaret. Banevalget viser alle 23 baner på én mobilskærm.
- **v0.19** – Valget *V6 hybrid* er fjernet. Motorlyden er nu de rigtige optagelser som standard, og *Blandet* kan stadig vælges under Indstillinger → Motorlyd.
- **v0.18** – Ny motorlyd, der efterligner de nyere V6-turbohybridmotorer (2014–2025): V6-tonen ved op til 12.000 omdr./min, turboens fløjt og elmotorens hyl. Under Indstillinger → Motorlyd kan man vælge *V6 hybrid*, *Blandet* (standard, model + rigtige optagelser) eller *Optagelse* (kun de rigtige 2005–2010-optagelser).
- **v0.17** – Hver bil er lige så hurtig som sin rigtige 2026-bil: holdene følger konstruktørstillingen, og topfarten går fra 350 km/t (Mercedes) til 333 km/t (Cadillac). Ny motorlyd lavet af rigtige F1-optagelser, der skifter tone med gearene, og et rigtigt publikum ved start og mål.
- **v0.16** – Løbene hedder nu landet som i Formel 1-kalenderen (fx Østrig, Storbritannien, Las Vegas), med banens navn som undertekst – i banevalget, sæsonen, startgrafikken og resultatet.
- **v0.15** – Bilen er 10 % hurtigere (også i optrækket), mens speedometeret viser det samme. Svingene kan tages med samme km/t som før. Banevalget er gjort kompakt, så alle 10 baner står på én mobilskærm.
- **v0.14** – Alle baner er 25 % bredere (plads til at overhale) og 12 % større. Monaco og Interlagos er gjort lidt større end de andre, så de tætte afsnit ikke rører hinanden. Svingene er tilpasset den bredere asfalt.
- **v0.13** – Tidtagningen ligger nu i en bjælke øverst med pauseknappen ved siden af. Minikort og beskeder ligger lige under bjælken, og styreknapperne er mindre og sidder helt i bunden.
- **v0.12** – Styrehjælpen er slået fra.
- **v0.11** – Kameraet følger altid bilen, og der styres med knapper (nu større). Indstillingerne for kamera, styring og styrehjælp er fjernet. Mere fartfølelse: kameraet zoomer ikke længere ud ved høj fart, der er fartstriber i kanten af skærmen, en let rumlen nær topfart og bremseskilte (3-2-1) før svingene. Knapstyringen er gjort mere tilgivende.
- **v0.10** – Bløde mure: bilen glider langs muren og mister fart alt efter, hvor stejlt den rammer, men kører videre. Baneafsnit, der ligger tæt (Monaco ved Loews-hårnålen og Mirabeau), overlapper ikke længere. Monaco har lidt smallere gader.
- **v0.9** – Hovedmenu med Hurtig løb og Sæson, og intet er valgt på forhånd. Banerne følger nu de rigtige layouts tæt (Monacos startlinje er rettet, og hårnålene er åbnet op i stedet for skåret af). Kameraet er zoomet længere ud. Spillet går ikke på pause af sig selv, og banen tegnes uden stop.
- **v0.8** – 10 baner fra 2026-kalenderen (gadebaner og natløb med projektører). Info samlet i en bjælke i bunden. Ny menu: vælg kører → vælg bane, og indstillinger på egen side.
- **v0.7** – Alle 11 hold med kørere og numre, holdfarver og hjelm. Forhjul der drejer og dæk der ruller. Gummispor og permanente bremsespor. TV-grafik med sektortider og rekorder.
- **v0.6** – Banen tegnes i færdige felter for jævn ydelse. Bilen ruller roligt videre efter målstregen.
- **v0.5** – Glidende bevægelse mellem fysiktrin, lettere grafik og jævne overgange mellem asfalt og græs. Styrehjælp er nu bare til/fra.
- **v0.4** – Red Bull Ring bygget ud fra den rigtige bane. Fart- og auto-gas-indstillingerne er fjernet.
- **v0.3** – Topfart 300 km/t, ingen bremseknap (slip gassen for at bremse) og langsommere sving.
- **v0.2** – Roligere styring og fart efter test med simulerede spillere. Styrehjælp tilføjet.
- **v0.1** – Første spilbare testbane med fast eller medfølgende kamera.

## Kilder
Motorlyden er rigtige F1-optagelser af Edvvc på Wikimedia Commons, licens CC BY-SA 3.0: [Brawn-Mercedes BGP 001 (2009)](https://commons.wikimedia.org/wiki/File:Brawn-Mercedes_BGP_001_(2009).ogg), [Red Bull-Cosworth RB1 (2005)](https://commons.wikimedia.org/wiki/File:Red_Bull-Cosworth_RB1_(2005).ogg) og [Williams-Cosworth FW32 (2010)](https://commons.wikimedia.org/wiki/File:Williams-Cosworth_FW32_(2010).ogg). Publikum: [F1 Race Crowd](https://commons.wikimedia.org/wiki/File:F1-Race-Crowd-Applause-Air-Horns.wav) af WebbFilmsUK, CC BY 4.0. Klippene er trimmet og lavet til løkker af [lights-out](https://github.com/Dhairya-007/lights-out) og beholder deres licenser.

Banernes forløb bygger på [bacinger/f1-circuits](https://github.com/bacinger/f1-circuits) (MIT-licens). Holdfarverne er forenklede bud på 2026-farverne, uden logoer.
