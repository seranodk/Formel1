# Formel 1

Formel 1 set ovenfra i TV-stil – til mobil og browser.

**Spil:** https://seranodk.github.io/Formel1/

Kør **Hurtig løb** (vælg kører og bane) eller en hel **Sæson** gennem de 10 baner i 2026-kalenderens rækkefølge med alle 22 kørere fra de 11 hold. Banerne er bygget ud fra de rigtige layouts: gadebaner med mure tæt på asfalten og natløb under projektører.

## Sådan spiller du
- **Peg-og-kør** (standard): sæt fingeren på venstre side af skærmen og træk i den retning, bilen skal køre.
- **Knapper**: ◀ ▶ drejer bilen.
- **GAS** sidder til højre. Slip gassen for at bremse før svingene.
- Peg bagud for at bakke. Med knapper bakker bilen selv, hvis den sidder fast.
- Tastatur: piletaster / WASD, ↓ = bak, P = pause.

Under **Indstillinger** vælger du kamera (fast eller følger bilen), styring, styrehjælp, antal omgange og lyd.

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
