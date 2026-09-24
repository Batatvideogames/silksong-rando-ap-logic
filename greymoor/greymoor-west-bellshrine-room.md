# Greymoor West Bellshrine Room  (Greymoor_01)

**Game ID:** Greymoor_01

**Contributors:** Isssma

## Subrooms

- main path
- middle section left
- middle section right
- upper path right
- upper path left

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top left | upper path left | [Greymoor Upper Halfway Home Path (Greymoor_12)](greymoor-upper-halfway-home-path.md) | R | Ledge grab OR cling grip OR enemy pogo OR faydown cloak OR medium scuttlebrace OR (progressive swift step 1 AND (clawline OR sharpdart)) OR silk soar |  | Verified |  |
| TR | top right | upper path right | [Greymoor East Bellshrine Room (Greymoor_02)](greymoor-east-bellshrine-room.md) | BL | cling grip OR progressive swift step 1 OR faydown cloak OR silk soar OR clawline OR sharpdart OR (drifters cloak AND ledge grab) |  | Verified |  |
| LR | lower right | main path | [Greymoor East Bellshrine Room (Greymoor_02)](greymoor-east-bellshrine-room.md) | LSL | (prereq shrine entrance lever AND (ledge grab OR medium shaman pogo OR faydown cloak OR silk soar)) OR nothing |  | Verified |  |
| LL | lower left | main path | [Greymoor Lower Halfway Home Path (Greymoor_13)](greymoor-lower-halfway-home-path.md) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Bellshrine (Bellshrine_02)](greymoor-bellshrine.md) | L | ( bellshrinesanity off AND activate bellshrine switch IN greymoor bellshrine )  OR ( bellshrinesanity on AND have bell greymoor ) |  | Verified | need to make sure this stays in sync with the connection on the other side |
| D | down | main path | [Far Fields Upper Shaft (Bone_East_11)](../far-fields/far-fields-upper-shaft.md) | C | clear greymoor floor blockade IN far fields upper shaft |  | Verified | MUST enter from far fields to activate this connection |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | lever switch | main path | middle section right | cling grip OR medium scuttlebrace OR (prereq shrine entrance lever AND (ledge grab OR medium shaman pogo)) |  | Verified |  |
| LS | lever switch | middle section right | main path | none (Switch is on this sidel) |  | Verified |  |
| P | Platform | middle section left | upper path left | ledge grab OR faydown cloak OR silk soar OR medium shaman pogo OR cling grip |  | Verified |  |
| P | Platform | upper path left | middle section left | none (just fall) |  | Verified |  |
| F1 | Fall 1 | middle section right | upper path right | Silk soar |  | Verified |  |
| F1 | Fall 1 | upper path right | middle section right | none (just fall) |  | Verified |  |
| BG | Big Gap | middle section right | middle section left | progressive swift step 1 AND clawline AND drifters cloak AND faydown cloak |  | Verified |  |
| BG | Big Gap | middle section left | middle section right | progressive swift step 1 AND clawline AND drifters cloak AND faydown cloak |  | Verified |  |
| G | Gap | upper path right | upper path left | faydown cloak OR drifters cloak OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR medium scuttlebrace |  | Verified |  |
| G | Gap | upper path left | upper path right | ledge grab OR medium enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR easy beast pogo OR medium shaman pogo |  | Verified |  |
| F2 | Fall 2 | middle section left | main path | none (just fall) |  | Verified |  |
| F2 | Fall 2 | main path | middle section left | silk soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #1 - Rosary Cache | middle section left | none |  | Verified | resource |  |
| shrine entrance lever | middle section right | flip switch right OR flip switch up OR flip switch left |  | Verified | switch |  |
