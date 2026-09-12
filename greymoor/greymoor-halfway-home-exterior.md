# Greymoor Halfway Home Exterior (Greymoor_03)

**Game ID:** Greymoor_03

**Contributors:** Isssma

## Subrooms

- lower left section
- lower right section
- sinner road entrance
- tower platform
- building left
- upper center room
- middle right section
- building roof
- upper right section

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower left section | [Greymoor Eastern Tower (Greymoor_04)](greymoor-eastern-tower.md) | LR | nothing |  | Verified |  |
| LR | lower right | lower right section | [Greymoor Lower Halfway Home Path (Greymoor_13)](greymoor-lower-halfway-home-path.md) | L | nothing |  | Verified |  |
| HR | hidden right | upper right section | [Greymoor Kraft Room (Greymoor_24)](greymoor-kraft-room.md) | L | prereq hidden right wall |  | Verified |  |
| MR | middle right | middle right section | [Greymoor Upper Halfway Home Path (Greymoor_12)](greymoor-upper-halfway-home-path.md) | L | nothing |  | Verified |  |
| HHR | halfway home right | lower right section | [Greymoor Halfway Home (Halfway_01)](greymoor-halfway-home.md) | R | activate pressure plate IN greymoor halfway home |  | Verified |  |
| UR | upper right | sinner road entrance | [Sinner's Road Entrance (Dust_01)](../sinner-s-road/sinner-s-road-entrance.md) | L | ledge grab OR progressive swift step 1 OR clawline OR sharpdart OR cling grip OR silk soar OR faydown cloak OR medium shaman pogo  OR drifters cloak OR easy beast pogo |  | Verified |  |
| HHL | halfway home left | building left | [Greymoor Halfway Home (Halfway_01)](greymoor-halfway-home.md) | L | nothing |  | Verified |  |
| ML | middle left | tower platform | [Greymoor Eastern Tower (Greymoor_04)](greymoor-eastern-tower.md) | MR | nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | lower right section | middle right section | silk soar OR cling grip OR (faydown cloak AND easy scuttlebrace) |  | Verified |  |
| S1 | shaft 1 | middle right section | lower right section | none (just fall) |  | Verified |  |
| PG1 | platform gap 1 | lower right section | building roof | silk soar OR flea brew OR drifters cloak OR faydown cloak OR progressive swift step 1 OR clawline OR sharpdart OR easy beast pogo  OR easy architect needle strike OR easy wanderer needle strike OR ((easy reaper needle strike OR medium shaman pogo) AND ledge grab) |  | Verified |  |
| PG1 | platform gap 1 | building roof | lower right section | none (just fall) |  | Verified |  |
| PG2 | platform gap 2 | building roof | middle right section | medium enemy pogo OR silk soar OR (faydown cloak AND (progressive swift step 2 OR sharpdart OR ((ledge grab OR cling grip) AND (progressive swift step 1 OR clawline OR drifters cloak OR medium shaman pogo OR easy beast pogo)))) |  | Verified |  |
| PG2 | platform gap 2 | middle right section | building roof | none (just fall) |  | Verified |  |
| F1 | fall 1 | middle right section | tower platform | silk soar |  | Verified |  |
| F1 | fall 1 | tower platform | middle right section | none (just fall) |  | Verified |  |
| F2 | fall 2 | tower platform | building roof | none |  | Verified |  |
| F2 | fall 2 | building roof | tower platform | silk soar OR activate tower elevator |  | Verified |  |
| LG | lake gap | building left | lower left section | progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR silk soar OR drifters cloak OR activate tower elevator OR swim OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |
| LG | lake gap | lower left section | building left | silk soar OR faydown cloak OR (activate tower elevator  AND (drifters cloak OR progressive swift step 1 OR sharpdart OR clawline OR easy beast pogo OR easy needle strike stall (architect) OR (swim AND (ledge grab OR cling grip)))) OR (activate tower elevator AND cling grip) |  | Verified |  |
| PG3 | platform gap 3 | building roof | building left | none (just fall) |  | Verified |  |
| PG3 | platform gap 3 | building left | building roof | silk soar OR (activate tower elevator AND faydown cloak) |  | Verified |  |
| G1 | gap 1 | tower platform | upper right section | ledge grab OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy shaman pogo OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR drifters cloak OR silksoar OR have Crest Architect |  | Verified |  |
| G1 | gap 1 | upper right section | tower platform | none (just fall) |  | Verified |  |
| S2 | shaft 2 | upper right section | sinner road entrance | silk soar OR cling grip OR easy scuttlebrace |  | Verified |  |
| S2 | shaft 2 | sinner road entrance | upper right section | none (just fall) |  | Verified |  |
| BG | baloon gap | upper right section | upper center room | hard enemy pogo OR (medium enemy pogo AND clawline) |  | Verified |  |
| BG | baloon gap | upper center room | upper right section | none (just fall) |  | Verified |  |
| G2 | gap 2 | upper center room | sinner road entrance | easy enemy pogo OR clawline OR progressive swift step 1 OR faydown cloak OR drifters cloak OR sharpdart OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo |  | Verified |  |
| G2 | gap 2 | sinner road entrance | upper center room | silk soar |  | Verified |  |
| F3 | fall 3 | tower platform | upper center room | silk soar |  | Verified |  |
| F3 | fall 3 | upper center room | tower platform | none (just fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #4 | sinner road entrance | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #5 | sinner road entrance | none |  | Verified | resource |  |
| Greymoor - Orders | upper center room | none |  | Verified | lore |  |
| tower elevator | tower platform | none (pressure switch) |  | Verified | switch |  |
| hidden right wall | upper right section | break wall right OR break wall up |  | Verified | blockade |  |
