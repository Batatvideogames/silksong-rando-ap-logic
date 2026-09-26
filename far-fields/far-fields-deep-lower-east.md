# Far Fields Deep Lower East (Bone_East_18b)

**Game ID:** Bone_East_18b

**Contributors:** herounit

## Subrooms

- left exit area
- right exit area
- ceiling exit area
- crossing
- trapper's arena
- trapper's den
- trapper's ledge

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | right exit area | [Sprintmaster Cave (Sprintmaster_Cave)](sprintmaster-cave.md) | L | none |  | Verified |  |
| C | top1 | ceiling exit area | [Far Fields Deep Fort Passage (Bone_East_26)](far-fields-deep-fort-passage.md) | F | none |  | Verified |  |
| L | left1 | left exit area | [Far Fields Deep Lower West (Bone_East_18)](far-fields-deep-lower-west.md) | R | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TB | trapped bench | crossing | trapper's arena | act 3 AND complete THE the hidden hunter wish promised |  | Verified |  |
| TB | trapped bench | trapper's arena | crossing | defeat gurr the outcast boss fight AND silk soar |  | Verified |  |
| RB | right boss fight | trapper's arena | trapper's den | defeat gurr the outcast boss fight |  | Verified |  |
| RB | right boss fight | trapper's den | trapper's arena | defeat gurr the outcast boss fight |  | Verified |  |
| G1 | gap 1 | left exit area | crossing | clawline AND silkhearts 1 |  | Verified |  |
| G1 | gap 1 | crossing | left exit area | clawline  AND silkhearts 1 AND ( run OR dash OR drifters OR faydown ) |  | Verified |  |
| G2 | gap 2 | crossing | right exit area | clawline AND silkhearts 1 |  | Verified | need to pogo to let silk recharge with only 1 heart, but it isn't that bad |
| G2 | gap 2 | right exit area | crossing | ( clawline AND silkhearts 2 ) OR ( clawline  AND silkhearts 1 AND ( dash OR faydown OR drifters ) ) |  | Verified | need enough silk to clawline twice to get the distance by itself |
| V1 | vertical 1 | crossing | ceiling exit area | ( faydown cloak AND ( cling grip OR scuttlebrace ) )  OR ( silk soar AND ( clawline OR drifter's cloak OR faydown cloak OR ( ledge grab AND dash ) ) ) |  | Verified |  |
| V1 | vertical 1 | ceiling exit area | crossing | run OR dash OR drifter's cloak OR  faydown cloak OR easy beast pogo OR sharpdart OR scuttlebrace |  | Verified |  |
| T1 | trapper 1 | trapper's den | trapper's ledge | faydown OR cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| T1 | trapper 1 | trapper's ledge | trapper's den | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gurr the outcast boss fight | trapper's arena | none |  | Verified | boss |  |
| AP Minor Cache - Rosary Cache: Far Fields #19 | trapper's ledge | none |  | Verified | collectible |  |
| Grass Doll | trapper's ledge | none |  | Verified | collectible |  |
