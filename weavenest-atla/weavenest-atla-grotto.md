# Weavenest Atla Grotto (Weave_03)

**Game ID:** Weave_03

**Contributors:** herounit

## Subrooms

- right exit area
- far east platforms
- upper east platforms
- mossberry platform
- causeway 
- upper west platforms
- lower west platforms
- boss room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit area | [Weavenest Atla Bench (Weave_07)](weavenest-atla-bench.md) | L | break vines |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BV1 | break vines 1 | right exit area | far east platforms | break vines left |  | Verified |  |
| BV1 | break vines 1 | far east platforms | right exit area | break vines right |  | Verified |  |
| P1 | platforming 1 | far east platforms | upper east platforms | none (falling) |  | Verified |  |
| P1 | platforming 1 | upper east platforms | far east platforms | ledge grab OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace OR sharpdart OR shaman crest |  | Verified |  |
| MU | mossberry upper | upper east platforms | mossberry platform | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR beast crest OR ( easy skips enabled AND ledge grab AND ( shaman crest OR architect crest ) ) |  | Verified | other stall techniques may also make it - untested; was unable to replicate previous reaper crest stall |
| ML | mossberry lower | causeway | mossberry platform | silk soar |  | Verified |  |
| ML | mossberry lower | mossberry platform | causeway | none (falling) |  | Verified |  |
| EV1 | east vertical 1 | causeway | upper east platforms | ledge grab OR faydown cloak OR   silk soar |  | Verified |  |
| EV1 | east vertical 1 | upper east platforms | causeway | none (falling) |  | Verified |  |
| WG1 | west gap 1 | causeway | upper west platforms | none (falling) |  | Verified |  |
| WG1 | west gap 1 | upper west platforms | causeway | ledge grab OR run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  |  |  |
| WG2 | west gap 2 | lower west platforms | causeway | ledge grab OR faydown cloak OR spike pogo OR silk soar |  | Verified |  |
| WG2 | west gap 2 | causeway | lower west platforms | none (falling) |  | Verified |  |
| BR | boss room jump | upper west platforms | boss room | break vines left AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR beast crest ) |  | Verified | beast pogo clears this easily |
| BR | boss room jump | boss room | upper west platforms | break vines right AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR beast crest OR scuttlebrace ) |  | Verified |  |
| F1 | fall 1 | boss room | lower west platforms | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla mossberry | mossberry platform | none |  | Verified | Included |  |
| double moss mother boss fight | boss room | none |  | Verified | Not included | BOSS IS NOT CURRENTLY TIED TO A CHECK - but does unlock weavelight check |
| weavelight | boss room | defeat double moss mother |  | Verified | Included |  |
