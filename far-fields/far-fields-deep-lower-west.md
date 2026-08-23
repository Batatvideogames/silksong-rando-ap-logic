# Far Fields Deep Lower West (Bone_East_18)

**Game ID:** Bone_East_18

**Contributors:** herounit

## Subrooms

- ceiling exit area
- ground level
- upper right alcove
- left of alcove gate

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | ceiling exit area | [Far Fields Deep Entrance (Bone_East_24)](far-fields-deep-entrance.md) | F | none |  | Verified |  |
| L | left1 | ground level | [Far Fields Pilgrim's Rest Deep Passage (Bone_East_18c)](far-fields-pilgrim-s-rest-deep-passage.md) | R | none |  | Verified |  |
| R | right1 | ground level | [Far Fields Deep Lower East (Bone_East_18b)](far-fields-deep-lower-east.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | ground level | upper right alcove | silk soar OR scuttlebrace OR ( cling grip AND ( run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest ) ) |  | Verified |  |
| V1 | vertical 1 | upper right alcove | ground level | none (falling) |  | Verified |  |
| DS | door switch | upper right alcove | left of alcove gate | door switch activated |  | Verified |  |
| DS | door switch | left of alcove gate | upper right alcove | door switch activated |  | Verified |  |
| V2 | vertical 2 | ground level | ceiling exit area | silk soar OR faydown cloak OR ( ledge grab AND ( run OR clawline OR ( drifter's cloak AND ( dash OR sharpdart ) ) ) |  | Verified |  |
| V2 | vertical 2 | ceiling exit area | ground level | none (falling) |  | Verified |  |
| V3 | vertical 3 | left of alcove gate | ceiling exit area | silk soar OR clawline OR faydown cloak OR scuttlebrace OR ( run AND ledge grab ) OR ( cling grip AND ( run OR dash OR sharpdart OR beast crest OR drifter's cloak ) ) |  | Verified | no inverse because there isn't much point |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | upper right alcove | activate door switch floor |  | Verified | Not included |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #2 | upper right alcove | none |  | Verified | Included |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #3 | upper right alcove | none |  | Verified | Included |  |
| AP Minor Cache - Rosary Cache: Far Fields #18 | upper right alcove | none |  | Verified | Included |  |
