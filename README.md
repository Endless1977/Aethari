# AETHARI — De Terugkeer

Co-op top-down sci-fi shooter voor 1–3 spelers (HTML, één bestand). Een spel van **ENDLESS**.

Een vergeten zaadschip wordt gevonden door de Aethari. Met hun hulp herrijst de mensheid tussen de sterren — tot een artefact onthult dat de Aarde nog bestaat, verborgen achter een ondoordringbaar schild.

**Speel:** https://endless1977.github.io/Aethari/

## Hoofdstukken
1. **De Wekking** — ontwaak in de cryokamer van het zaadschip, stabiliseer je DNA, herstel de stroom en overleef het oude beveiligingssysteem
2. **Kolonie Nieuw-Begin** — co-op RTS (Red Alert 2-stijl): mijnschepen delven erts en Aethari-kristal, bouw Zonnecollectors, Raffinaderij, Hangar, Torens, Aethari-lab en Scheepswerf; verdedig tegen piraten, ontcijfer de gevonden datakern en bouw het transportschip *Terugkeer* (romp, motoren, schildgenerator)
3. **De Reis naar de Aarde** — escorteer als jagers de Terugkeer door de Kuipergordel: asteroïden, piratenhinderlaag, en de Aarde met haar schild komt steeds dichterbij
4. **Kepler-Poort** — verover het bewaakte ruimtestation (baas: Commandant Vael)
5. **De Tether** — daal af met de ruimtelift, ontmantel de bommen van De Schaduw
6. **Het Stille Toevluchtsoord** — 4 puzzelkamers
7. **Arcadia** — corrupte militairen (baas: Generaal Kragg)
8. **Het Congresgebouw** — breek de schildpylonen en werp Kanselier Morrow omver
9. **De Diepte** — haal de AI-module NEXUS terug voor de Aethari

### RTS-besturing (H2)
Sleep een kader om te selecteren (Shift = toevoegen) · rechtsklik: bewegen / mijnen / aanvallen · WASD of schermrand: camera · muiswiel: zoom · H: naar Commandocentrum · bouwmenu rechts (rechtsklik op bouw-icoon = annuleren, Esc = plaatsen annuleren). Alle spelers besturen samen dezelfde kolonie.

## Rollen
- **Elias Voss** (Commandant) — pulsgeweer, Q: Overdrive
- **Mara Lin** (Ingenieur) — scattergun, ontmantelt 2× sneller, Q: geschutstoren
- **Thal'ira** (Aethari-gids) — zoekende lichtbollen, Q: Heelpuls (geneest + reanimeert)

## Besturing
WASD bewegen · muis richten/schieten · Spatie dash · E gebruiken/reanimeren/ontmantelen · Q vaardigheid · Enter doorgaan · M geluid.
Controller: sticks, RT schieten, A dash, X gebruiken, Y vaardigheid, Start doorgaan.

## Multiplayer
Host klikt *Host spel* en deelt de 5-letterige code; vrienden vullen die in bij *Deelnemen* (PeerJS/WebRTC). De host bewaart de verhaalvoortgang; ontgrendelde hoofdstukken zijn in de lobby te kiezen. Gedeelde continues (3 per hoofdstuk) en gedeeld wapenniveau.

## 3D-modellen (`models/`)
- `zaadschip.glb` — het zaadschip (proloog, kolonie, menu)
- `aarde.glb` + `schild.glb` — de Aarde in het gloeiend blauwe Dyson-schild

Alle andere schepen, tanks en eenheden zijn getekende vector-art. De game werkt ook zonder modellen.
