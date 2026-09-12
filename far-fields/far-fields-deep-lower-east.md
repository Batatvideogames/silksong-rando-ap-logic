# Far Fields Deep Lower East (Bone_East_18b)

**Game ID:** Bone_East_18b

**Contributors:** herounit

## Subrooms

- left exit area
- right exit area
- ceiling exit area
- trapper's arena
- trapper's den
- crossing

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | right exit area | [Sprintmaster Cave (Sprintmaster_Cave)](sprintmaster-cave.md) | L | none |  | Verified |  |
| C | top1 | ceiling exit area | [Far Fields Deep Fort Passage (Bone_East_26)](far-fields-deep-fort-passage.md) | F | none |  | Verified |  |
| L | left1 | left exit area | [Far Fields Deep Lower West (Bone_East_18)](far-fields-deep-lower-west.md) | R | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TB | trapped bench | crossing | trapper's arena | act 3 AND the hidden hunter wish in progress | TODO | Needs verification |  |
| TB | trapped bench | trapper's arena | crossing | defeat gurr the outcast boss fight AND silk soar | TODO | Needs verification |  |
| RB | right boss fight | trapper's arena | trapper's den | defeat gurr the outcast boss fight | TODO | Needs verification |  |
| RB | right boss fight | trapper's den | trapper's arena | defeat gurr the outcast boss fight | TODO | Needs verification |  |
| G1 | gap 1 | left exit area | crossing | clawline AND silk heart AND ( ledge grab OR faydown cloak ) |  | Verified |  |
| G1 | gap 1 | crossing | left exit area | clawline AND silk heart AND ( run OR dash OR drifter's cloak OR faydown cloak ) |  | Verified |  |
| G2 | gap 2 | crossing | right exit area | clawline AND silk heart |  | Verified |  |
| G2 | gap 2 | right exit area | crossing | clawline AND silk heart |  | Verified |  |
| V1 | vertical 1 | crossing | ceiling exit area | ( faydown cloak AND ( cling grip OR scuttlebrace ) )  OR ( silk soar AND (  clawline OR drifter's cloak OR faydown cloak OR ( ( ledge grab AND dash ) ) ) ) |  | Verified |  |
| V1 | vertical 1 | ceiling exit area | crossing | run OR dash OR drifter's cloak OR  faydown cloak OR easy beast pogo OR sharpdart OR scuttlebrace |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| AP Minor Cache - Rosary Cache: Far Fields #19 | trapper's den | defeat gurr the outcast boss fight | TODO | Needs verification | collectible |  |
| gurr the outcast boss fight | trapper's arena | none | TODO | Needs verification | boss |  |
