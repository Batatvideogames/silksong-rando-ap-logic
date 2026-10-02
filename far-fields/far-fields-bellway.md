# Far Fields Bellway (Bellway_03)

**Game ID:** Bellway_03

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | bellway | ✓ |
| S2 | hidden area | ✓ |
| S3 | right exit area | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right exit area | [Far Fields Pinstress Attic (Bone_East_09b)](far-fields-pinstress-attic.md) | L | none |  | Verified | ✓ |  |
| L | left1 | bellway | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | R2 | none |  | Verified | ✓ |  |
| BB | door_fastTravelExit | bellway | [Bellway Menu](../fast-travel/bellway-menu.md) | FF | unlock bellway far fields |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| HP | hidden pathway | bellway | hidden area | unlock bellway rosary lock |  | Verified | ✓ |  |
| HP | hidden pathway | hidden area | bellway | unlock bellway rosary lock |  | Verified | ✓ |  |
| TP | thorn path | hidden area | right exit area | ( silk soar AND ( ledge grab OR cling grip OR scuttlebrace ) )  OR ( faydown cloak AND cling grip )  OR ( break blast rock down AND drifter's cloak AND ( cling grip OR scuttlebrace ) ) |  | Verified | ✓ |  |
| TP | thorn path | right exit area | hidden area | silk soar OR drifter's cloak |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | bench | bellway | unlock bench rosary lock |  | Verified | bench | ✓ |  |
| 2 | bench rosary lock | bellway | none |  | Verified | lock | ✓ |  |
| 3 | bellway rosary lock | bellway | none |  | Verified | lock | ✓ |  |
| 4 | bellway far fields | bellway | unlock bellway rosary lock |  | Verified | travel |  |  |
| 5 | Craw Summons | bellway | craw summons ready |  | Verified | collectible |  |  |

## Room Images

### Scene

[![Scene for Far Fields Bellway (Bellway_03)](../00-annotations/far-fields/far-fields-bellway-scene.png)](../00-annotations/far-fields/far-fields-bellway-scene.png)

### Connections

[![Connections for Far Fields Bellway (Bellway_03)](../00-annotations/far-fields/far-fields-bellway-connections.png)](../00-annotations/far-fields/far-fields-bellway-connections.png)

### Checks

[![Checks for Far Fields Bellway (Bellway_03)](../00-annotations/far-fields/far-fields-bellway-checks.png)](../00-annotations/far-fields/far-fields-bellway-checks.png)
