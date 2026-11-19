# *Vombatus ursinus* (Shaw, 1800) — Bare-Nosed / Common Wombat

**Repository:** `https://github.com/intenteco/vombatus-ursinus`  
**Taxon Locators:** `urn:qualia:taxon:vombatus_ursinus` · `did:q42:taxon:vombatus_ursinus`  
**Work-Packet Status:** `ECO-WP-07A` (Species Ontology & `.q42` Compilation) and `ECO-WP-07B` (3-Layer Zoological CAD, 24-Joint `vombatid_fossorial` PGA Rig, `chiang_hair` BSDF, `.emf`/`.qac`, `.hmc` & Orthographic Previews) complete; `ECO-WP-GATE` human domain/visual/rights review pending (`reported_status: "incomplete"`).

---

## 1. Taxonomic Concept & Verified Identifiers

*Vombatus ursinus* (Shaw, 1800) (originally described as *Didelphis ursina* Shaw, 1800) is an obligate fossorial herbivorous marsupial and the sole extant species in the genus *Vombatus* É. Geoffroy, 1803 (family Vombatidae). Across South-Eastern Australia, mainland populations correspond to *Vombatus ursinus hirsutus* (Perry, 1810), alongside Tasmanian (*V. u. tasmaniensis*) and Bass Strait (*V. u. ursinus*) subspecies.

| Scheme | Identifier / URI | Status | Notes |
|---|---|---|---|
| Qualia Taxon URN | `urn:qualia:taxon:vombatus_ursinus` | Asserted | Primary QualiaDB concept URI |
| Q42 DID Locator | `did:q42:taxon:vombatus_ursinus` | Asserted | Unallocated mathematical locator |
| Australian Faunal Directory (AFD) | `https://biodiversity.org.au/afd/taxa/66d42847-c556-4fa3-902c-a91d9f517286` | Verified | Accepted taxon *Vombatus ursinus* (Shaw, 1800) |
| Atlas of Living Australia (ALA) | `https://bie.ala.org.au/species/https://biodiversity.org.au/afd/taxa/66d42847-c556-4fa3-902c-a91d9f517286` | Verified | Species profile & regional occurrence records |
| GBIF Backbone (Species) | `https://www.gbif.org/species/2440301` (`GBIF:2440301`) | Verified | Accepted species (*Vombatus* genusKey `2440300`, familyKey `9376`) |
| NCBI Taxonomy | `NCBITaxon:29139` | Verified | *Vombatus ursinus* (genus `NCBITaxon:29138`) |
| NSW NPWS Profile | `https://www.nationalparks.nsw.gov.au/plants-and-animals/bare-nosed-wombat` | Verified | Morphometrics, 30 m burrows, diet & NSW distribution |
| Victorian Biodiversity Atlas (DEECA) | `https://vba.biodiversity.vic.gov.au/` | Verified | Victorian distribution & conservation records |

---

## 2. Anatomical Subsystems (`UBERON`) & Fossorial Biomechanics

All anatomical subsystems are keyed to `UBERON` identifiers in [`ontology/taxon.ttl`](ontology/taxon.ttl) and [`ontology/index.ttl`](ontology/index.ttl):

- **Osteology (`UBERON:0001434`, 24-joint fossorial quadruped rig):**
  - Flattened broad cranium (`UBERON:0003129`) with massively flared zygomatic arches (`UBERON:0001682`) creating wide temporal fossae for jaw adductors
  - **Hypselodont continuously growing rootless dentition** (`UBERON:0001759`; `I 1/1, C 0/0, P 1/1, M 4/4 = 24` teeth) — unique among living marsupials, offsetting extreme silica abrasion from native tussock grasses and roots
  - Short braced cervical-thoracic-lumbar spine and fused sacrum (`UBERON:0001130` / `UBERON:0001094`), barrel-shaped ribcage and robust clavicles (`UBERON:0002228` / `UBERON:0001105`)
  - Forelimb skeleton (`UBERON:0002102`) with a **flared deltopectoral humerus crest** (`UBERON:0000976`) and elongated ulnar olecranon lever arm (`olecranonIndex: 0.34`)
  - Plantigrade 5-digit forepaws (`UBERON:0002398`) armed with broad, flattened spade-like digging claws (`UBERON:0001465`)
  - Heavy pelvic girdle (`UBERON:0001271`), marsupial epipubic bones (`UBERON:0003661`), stocky hindlimb (`UBERON:0000981`), plantigrade hind feet (`UBERON:0002387`) with **syndactylous grooming digits II–III** (`UBERON:0001452`), and vestigial caudal tail (`UBERON:0001095`, `0.02–0.035 m`)
- **Myology (`UBERON:0001630`):**
  - Massive fossorial digging musculature: **triceps brachii** (high-torque elbow extension), **pectoralis** (`UBERON:0002356`, humeral adduction), and **latissimus dorsi** (`UBERON:0001498`, humeral retraction/soil clearing)
  - Hypertrophied masticatory masseter/temporalis (`UBERON:0003662`) and epaxial lumbar/gluteal hindquarter bracing musculature (`UBERON:0002255` / `UBERON:0001377`)
- **Integument, Pouch, Rump Shield & Specialized Visceral Biomechanics (`UBERON:0002416`):**
  - Coarse, thick, bristle-like grizzled sandy-brown to charcoal-grey pelage (`UBERON:0002416` / `UBERON:0002099`) lacking soft underfur
  - Bare, dark, granular, leathery rhinarium (`UBERON:0001756`) and small, rounded, furry ears (`UBERON:0001757`)
  - **Backward-opening marsupium/pouch** (`UBERON:0001831`) preventing soil ingress during burrowing
  - **Thickened fibrocartilaginous/dermal rump shield (`pelvic_dermal_shield`, `UBERON:0002097` / `UBERON:0001319`, `10–15 mm`):** Dense collagenous plate fused over the sacrum and iliac crests used for burrow defense by wedging the rump upward against the tunnel roof to crush intruding predators
  - **Specialized distal colon biomechanics (`UBERON:0001155`):** Circumferentially alternating stiffened grooves and compliant zones across the distal `17–25%` of the colon, coupled with `8–14 day` digesta dehydration, producing characteristic **cubic scat** (`~20–30 mm` cubes) that resists rolling off elevated rocks and logs used for territorial scent-marking

---

## 3. Biophysical, Morphometric, Allometric & ROM Parameters

| Parameter | Range / Value | Notes |
|---|---|---|
| Head–body length | `0.85 – 1.15 m` | Compact, low-slung fossorial body plan |
| Shoulder height | `0.35 – 0.45 m` | Low center of gravity for tunnel navigation |
| Adult mass | `22.0 – 38.0 kg` | Females `22.0–34.0 kg`, males `25.0–38.0 kg` |
| Basal Metabolic Rate (BMR) | `32.0 W` | Hypometabolic fossorial marsupial scaling ($\text{BMR}(M) = 2.40 \cdot M^{0.75}\text{ W}$; $T_b \approx 34.8^\circ\text{C}$) |
| Burrow network | `15 – 30 m` tunnels | Up to `3.5 m` depth with sleeping chambers & multiple entrances |
| Locomotion | Walk `0.8–1.5 m/s` / Sprint up to `11.1 m/s` | Plantigrade amble + short-burst defensive gallop (`~40 km/h`) |

### Joint Range of Motion (`q42:rom:*`, Radians)

| Joint | Healthy Min (rad) | Healthy Max (rad) | Injury Threshold (rad) | Post-Injury Guarding |
|---|---|---|---|---|
| `shoulder` | `-0.85` | `+1.05` | `1.25` | `q42:obligateForelimbDiggingUnload` |
| `elbow` | `-1.82` | `-0.18` | `-2.02` | `q42:obligateForelimbDiggingUnload` |
| `wrist` | `-0.78` | `+0.62` | `-0.98` | `q42:obligateForelimbDiggingUnload` |
| `hip` | `-0.52` | `+1.18` | `1.38` | `q42:obligateInjuredAsymmetricAmbleGait` |
| `knee` | `-1.68` | `-0.15` | `-1.88` | `q42:obligateInjuredAsymmetricAmbleGait` |
| `ankle` | `-0.68` | `+0.84` | `1.02` | `q42:obligateInjuredAsymmetricAmbleGait` |
| `spine` | `-0.36` | `+0.48` | `0.64` | `q42:obligateBurrowShelterRetreat` |
| `neck` | `-0.58` | `+0.46` | `0.75` | `q42:obligateBurrowShelterRetreat` |

### `InstanceState64` Ontogenetic Stages

Deterministic 64-byte per-instance phenotype parameterization (`seed`, `ontogenetic_age_norm`, `height_scale`, `site_vigor`, `environmental_stress`, `sex_dimorphism_flag`, `pouch_occupancy_flag`, `pelage_grizzle_melanin`, `mange_stress_01`) spans:
1. `pouch_young` (`0.00–0.16`)
2. `juvenile_at_heel` (`0.16–0.36`)
3. `subadult` (`0.36–0.58`)
4. `adult_female` (`0.58–1.00`, `2n=14 XX`, backward-opening marsupium)
5. `adult_male` (`0.58–1.00`, `2n=14 XY`, broad cranium & pelvic dermal shield)

---

## 4. Grazing Ecology & South-Eastern Australian Biocultural Provenance

- **Grazing Ecology (`ro:0002470`):** Nocturnal/crepuscular grazer feeding on *Poa sieberiana* (snow tussock grass), *Themeda triandra* (kangaroo grass), *Carex appressa* and other sedges, *Lomandra longifolia* mat-rushes, bark, and subterranean roots; acts as an allogenic ecosystem engineer whose `15–30 m` burrows provide vital thermal and bushfire refugia for co-occurring native fauna.
- **Biocultural Custodianship (Social Permissive Commons `SPC`):**
  Attributed across **Dharug / Gundungurra (*Wombat* / *Wambad*), Ngarigo, Walgalu, Yuin, Wiradjuri, GunaiKurnai, Wurundjeri (*Waring*), Boonwurrung, and Taungurung Country** under Local Contexts TK/BC and CARE Principles.

---

## 5. Repository Artifacts & Verification

| Artifact | Purpose / Metrics | Bytes | SHA-256 | Status |
|---|---|---|---|---|
| [`synth.project.json`](synth.project.json) | Synth project descriptor (`synth.project/v1`) | `562` | — | Authored |
| [`.synth/bookmarks.json`](.synth/bookmarks.json) | Authoritative AFD, ALA, GBIF, NCBI, NSW NPWS, NSW BioNet, Vic VBA, TERN & TK/BC URLs | `4,530` | — | Authored |
| [`.synth/jobs.json`](.synth/jobs.json) | Reproducible Turtle → `.q42` compile job definitions | `1,561` | — | Authored |
| [`ontology/taxon.ttl`](ontology/taxon.ttl) | Taxon concept, `UBERON` subsystems, ROM bounds, `InstanceState64`, grazing & Country graph | `34,323` | `f4a71a65318fc74d6733abc258794bfe5295ad781fa07d19d9740d63d699ab23` | Compiled (`573` quins) |
| [`ontology/index.ttl`](ontology/index.ttl) | DCAT dataset & distribution manifest | `5,669` | `2a0d4f9d6c3987eef1e294e06b4d7247a24177ab31846ef04e63c7c35cdebeb4` | Compiled (`70` quins) |
| [`dist/taxon.q42`](dist/taxon.q42) | Sealed NQuin taxon & biophysical ontology | `44,087` | `d885c7be96215ec0b4457e445bdc21e80a8a9e9b6a7b7279173173d3a408a500` | Compiled & SPARQL-verified |
| [`dist/index.q42`](dist/index.q42) | Sealed NQuin package index | `7,463` | `415733b33bae31d37cec39a34b58e7be93794d68f6c8477416abe0d5ea535a00` | Compiled & SPARQL-verified |
| [`source/vombatus-ursinus.vibe`](source/vombatus-ursinus.vibe) | 98-part 3-layer zoological CAD (20–24 pt cubic lofts, `boolean_3d` nostrils, `vombatid_fossorial` 24-joint rig, `chiang_hair` BSDF) | `258,883` | `c39f2aa3ffed30ff46f9a0d69086b2f28299ffd5581b17cc828c4db8b8050eb1` | Produced (`ECO-WP-07B`) |
| [`source/actuation.vibe`](source/actuation.vibe) | `InstanceState64` stages, rotary scratch-digging, waddle walk, rump-block & aura hooks | `7,807` | `f6d2c4e1f03ea6ae6e30650061c2becb54e75b2caba8da848fe61fffdd7ada59` | `vibe_check` passed |
| [`dist/vombatus-ursinus.hmc`](dist/vombatus-ursinus.hmc) | Verified Hypermedia Container (`production16`, `strict_replay_verified: true`, 12 resources) | `3,178,572` | `eb25daf0b9d925177085fd4b8907b621be5b3af71009de21cda3dca479719d2c` | Produced (`ECO-WP-07B`) |
| [`dist/vombatus-ursinus.10d`](dist/vombatus-ursinus.10d) | 3-layer zoological CAD manifold (`27,799` triangles, `14,162` vertices, grounded `y = 0.0`) | `413,176` | `e2082353c35b107a7cac79fd8938f44678965d8a27c8edd34e98fa869eda81d0` | Produced & visually inspected |
| [`dist/vombatus-ursinus-pbr.10d`](dist/vombatus-ursinus-pbr.10d) | Topology/BVH 10D PBR torso compilation | `266,096` | `cebffb60725afe84b5f2b434fdb7a5e9a10b7fff9acab490116282727f7a0afc` | Produced (`ECO-WP-07B`) |
| [`dist/vombatus-ursinus-field.emf`](dist/vombatus-ursinus-field.emf) | Endothermic core (`34.8 C`, `32.0 W`) & fossorial muscle bioelectric `.emf` field | `1,053,440` | `4910673fc9877e62a756664eba1476a973d2572719e9e7f5387c6c3c557ee2e0` | Produced (`ECO-WP-07B`) |
| [`dist/vombatus-ursinus-call.qac`](dist/vombatus-ursinus-call.qac) | Low raspy defensive grunt/hiss (`110–420 Hz`, `112 Hz` fundamental) `.qac` v1 audio | `937,856` | `e9c48f2b8fde55de3249588a2d76751952fac23922652fd241adf55cb9bc7486` | Produced (`ECO-WP-07B`) |
| [`dist/rig-packet.json`](dist/rig-packet.json) | 24-joint `vombatid_fossorial` behavioral packet (`grazing` macro) | `311` | `6f249557d77cb704aef4132e2fd8bfc5fc903861187f6f1d25ef15242b3ba79a` | Produced (`ECO-WP-07B`) |
| [`dist/receipt.json`](dist/receipt.json) | `synth.production-receipt/v1` production & replay receipt | `5,348` | `2a116314d13e8570a900c6658657097d4ac94288ea45536a9016ff3851e10046` | Produced (`ECO-WP-07B`) |
| [`previews/`](previews/) | Native 2048×2048 orthographic PNGs (`front`, `side`, `three-quarter`), `turnaround.png`, `blueprint.svg`, `spectral-slice.png`, `fur-*.png`, `hair-bsdf.png`, `review-receipt.json` | — | `review-receipt.json`: `360cf481...` | Inspected (`ECO-WP-GATE` pending) |
| [`dossier/claims.json`](dossier/claims.json) | Pinned 193-row claims ledger (`2026-10-24.2`) | — | — | Updated (`reported_status: "incomplete"`) |
