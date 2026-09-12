# Far Fields Upper Shaft (Bone_East_11)

**Game ID:** Bone_East_11

**Contributors:** herounit

## Subrooms

- the bottom
- above middle gate
- hunters march bridge
- top wind tunnel
- left march bridge room
- right march bridge room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | top wind tunnel | [Greymoor West Bellshrine Room  (Greymoor_01)](../greymoor/greymoor-west-bellshrine-room.md) | D | drifter's cloak |  | Verified | silk soar does not work |
| UR | right1 | right march bridge room | [Far Fields Deep Entrance (Bone_East_24)](far-fields-deep-entrance.md) | L | none |  | Verified |  |
| L | left1 | left march bridge room | [Hunter's March Deep Entrance (Ant_09)](../hunter-s-march/hunter-s-march-deep-entrance.md) | R | none |  | Verified |  |
| LR | right2 | the bottom | [Far Fields Pilgrim's Rest (Bone_East_10)](far-fields-pilgrim-s-rest.md) | UL | none |  | Verified |  |
| F | bot1 | the bottom | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | C | none (activate lower gate lever) |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | the bottom | above middle gate | drifter's cloak OR silk soar |  | Verified |  |
| V1 | vertical 1 | above middle gate | the bottom | none (falling) |  | Verified |  |
| V2 | vertical 2 | above middle gate | hunters march bridge | drifter's cloak OR silk soar |  | Verified |  |
| V2 | vertical 2 | hunters march bridge | above middle gate | none (falling) |  | Verified |  |
| V3 | vertical 3 | hunters march bridge | top wind tunnel | silk soar OR ( drifter's cloak AND NOT activate hunter's march bridge lever ) | TODO | Verified | the bridge blocks the wind stream - not sure exactly how this should be represented |
| V3 | vertical 3 | top wind tunnel | hunters march bridge | none (falling) |  | Verified |  |
| LB | left bridge crossing | left march bridge room | hunters march bridge | activate hunter's march bridge lever |  | Verified |  |
| LB | left bridge crossing | hunters march bridge | left march bridge room | activate hunter's march bridge lever |  | Verified |  |
| RB | right bridge crossing | hunters march bridge | right march bridge room | activate hunter's march bridge lever |  | Verified |  |
| RB | right bridge crossing | right march bridge room | hunters march bridge | activate hunter's march bridge lever |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lower gate lever | the bottom | flip switch down |  | Verified | switch |  |
| middle gate lever | above middle gate | flip switch down |  | Verified | switch |  |
| hunter's march bridge lever | left march bridge room | flip switch down |  | Verified | switch |  |
