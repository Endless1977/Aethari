# AETHARI — De Terugkeer

Co-op top-down sci-fi shooter voor 1–3 spelers (HTML, één bestand). Een spel van **ENDLESS**.

Een vergeten zaadschip wordt gevonden door de Aethari. Met hun hulp herrijst de mensheid tussen de sterren — tot een artefact onthult dat de Aarde nog bestaat, verborgen achter een ondoordringbaar schild.

**Speel:** https://endless1977.github.io/Aethari/

## Hoofdstukken
1. **Kepler-Poort** — verover het bewaakte ruimtestation (baas: Commandant Vael)
2. **De Tether** — daal af met de ruimtelift, ontmantel de bommen van De Schaduw
3. **Het Stille Toevluchtsoord** — 4 puzzelkamers: drukplaten, lichtreeks, tegels, gekoppelde draaischijven
4. **Arcadia** — corrupte militairen (baas: Generaal Kragg)
5. **Het Congresgebouw** — breek de schildpylonen en werp Kanselier Morrow omver
6. **De Diepte** — haal de AI-module NEXUS terug voor de Aethari

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
Geoptimaliseerd met gltf-transform (WebP-textures, meshopt) — van ~118 MB naar ~14 MB.
- `zaadschip.glb` — het zaadschip (proloog)
- `kolonieschip.glb` — kolonieschip (menu, aarde-scène)
- `aethari_schip.glb` — Aethari-schip (menu, Aethari-scènes, finale)
- `aethari.glb` — Aethari op zwevende rots (tussenfilmpjes)
- `aarde.glb` — de Aarde (menu, tussenfilmpjes)
- `schild.glb` — het ondoordringbare schild (Dyson-bol, gloeiend blauw energiemateriaal + energieveld) met de Aarde erin
- `tank_rood.glb`, `tank_vege.glb` — tanks in Arcadia en het Congresgebouw (sprites in 32 richtingen)
- `kragg.glb` — Generaal Kragg (geanimeerd, sprites in 32 richtingen × 6 frames)

De game werkt ook zonder modellen (valt terug op getekende vormen).
