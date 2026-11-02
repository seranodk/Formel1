# Formel 1

Formel 1 set ovenfra i TV-stil – til mobil og browser.

**Spil:** https://seranodk.github.io/Formel1/

Kør **Hurtig løb** (vælg kører og bane) eller en hel **Sæson** gennem de 10 baner i 2026-kalenderens rækkefølge med alle 22 kørere fra de 11 hold. Banerne er bygget ud fra de rigtige layouts: gadebaner med mure tæt på asfalten og natløb under projektører.

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
Banernes forløb bygger på [bacinger/f1-circuits](https://github.com/bacinger/f1-circuits) (MIT-licens). Holdfarverne er forenklede bud på 2026-farverne, uden logoer.
