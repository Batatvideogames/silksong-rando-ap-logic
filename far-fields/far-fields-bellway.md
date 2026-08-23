# Far Fields Bellway (Bellway_03)

**Game ID:** Bellway_03

**Contributors:** herounit

## Subrooms

- bellway
- hidden area
- right exit area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | bellway | [Far Fields Pinstress Attic (Bone_East_09b)](far-fields-pinstress-attic.md) | L | none |  | Verified |  |
| L | left1 | bellway | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | R2 | none |  | Verified |  |
| BB | door_fastTravelExit | bellway | [Bellway Menu](../fast-travel/bellway-menu.md) | FF | bellway pay gate unlocked |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HP | hidden pathway | bellway | hidden area | bellway pay gate unlocked |  | Verified |  |
| HP | hidden pathway | hidden area | bellway | bellway pay gate unlocked |  | Verified |  |
| TP | thorn path | hidden area | right exit area | break blast rock down AND ( silk soar AND (  ledge grab OR cling grip OR scuttlebrace ) ) OR ( faydown cloak AND cling grip ) OR ( drifter's cloak AND ( cling grip OR scuttlebrace ) ) |  | Verified |  |
| TP | thorn path | right exit area | hidden area | silk soar OR drifter's cloak |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench | bellway | bench pay gate unlocked |  | Verified | Not included |  |
| bench pay gate | bellway | none |  | Verified | Not included |  |
| bellway pay gate | bellway | none |  | Verified | Included |  |
