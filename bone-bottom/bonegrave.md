# Bonegrave (Bonegrave)

**Game ID:** Bonegrave

**Contributors:** herounit, super epicguy

## Subrooms

- upper left exit
- upper right exit
- graveyard
- door platform
- middle right platform
- mossberry platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | UL | none |  | Verified |  |
| LR | lower right | door platform | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | LL | none |  | Verified |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](../wormways/wormways-lower-east.md) | F | silk soar OR cling grip OR faydown cloak OR scuttlebrace |  | Verified |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](chapel-of-the-wanderer.md) | CD | none |  | Verified | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage (Bone_Steel_Servant)](bonegrave-passage.md) | R | steel soul AND act 3 | TODO |  | need to check act 3 |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RV1 | right vertical 1 | middle right platform | upper right exit | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| RV1 | right vertical 1 | upper right exit | middle right platform | none (falling) |  | Verified |  |
| RV2 | right vertical 2 | door platform | middle right platform | silk soar |  | Verified |  |
| RV2 | right vertical 2 | middle right platform | door platform | none (falling) |  | Verified |  |
| BW | breakable wall | upper left exit | upper right exit | clear wormways access breakable wall |  | Verified |  |
| BW | breakable wall | upper right exit | upper left exit | clear wormways access breakable wall |  | Verified |  |
| PG | pond gap | door platform | graveyard | swim OR run OR clawline OR drifters OR silk soar OR sharpdart OR ( faydown AND ( ledge grab OR easy beast pogo OR easy hunter pogo OR easy reaper pogo OR easy architect pogo OR easy shaman pogo ) ) |  | Verified | A wide variety of stalls are likely to work with faydown here |
| PG | pond gap | graveyard | door platform | silk soar  OR clawline  OR sharpdart OR ( ( ledge grab OR cling grip ) AND run AND dash ) OR ( faydown cloak AND ( run OR dash ) ) OR ( swim AND ( ledge grab OR cling grip OR faydown cloak ) ) |  | Verified | A wide variety of stalls are likely to work here as well with ledge grab or faydown |
| MF | middle vertical 1 | door platform | mossberry platform | silk soar |  | Verified |  |
| MF | middle vertical 1 | mossberry platform | door platform | none (falling) |  | Verified |  |
| G2M | graveyard to mossberry | graveyard | mossberry platform | silk soar OR ledge grab OR cling grip OR faydown cloak |  | Verified |  |
| G2M | graveyard to mossberry | mossberry platform | graveyard | none (falling) |  | Verified |  |
| M2M | mossberry to middle | mossberry platform | middle right platform | faydown  OR clawline OR ( ( ledge grab OR cling grip ) AND ( dash OR easy scuttlebrace OR easy beast pogo OR easy architect pogo OR easy hunter pogo OR sharpdart OR drifters ) ) |  | Verified |  |
| M2M | mossberry to middle | middle right platform | mossberry platform | clawline OR ( run AND dash AND ( sharpdart OR ( ledge grab AND faydown ) ) ) |  | Verified |  |
| USF | upper stall fall | upper right exit | mossberry platform | sharpdart  OR clawline  OR drifters  OR ( run AND dash ) OR ( faydown AND ( run OR dash ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boneyard mossberry | mossberry platform | none |  | Verified | collectible |  |
| rosary cache bone bottom 6 | upper right exit | none |  | Verified | collectible |  |
| rosary cache bone bottom 7 | upper right exit | none |  | Verified | collectible |  |
| rosaries on grave | graveyard | none |  | Verified | collectible | NOT RANDOMIZED AS OF v0.4.5 |
| wormways access breakable wall | upper left exit | break wall right |  | Verified | blockade |  |
| vines holding door closed | door platform | break vines right |  | Verified | blockade |  |
