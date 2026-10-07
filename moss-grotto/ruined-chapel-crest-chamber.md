# Ruined Chapel Crest Chamber (Tut_05)

**Game ID:** Tut_05

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | left exit area | ✓ |
| S2 | crest area | ✓ |
| S3 | lore area | ✓ |
| S4 | blocked area 1 | ✓ |
| S5 | blocked area 2 | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Ruined Chapel Interior (Tut_04)](ruined-chapel-interior.md) | R | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | left exit area | blocked area 1 | (run AND dash) OR drifters OR faydown OR clawline OR sharpdart OR spike pogo |  | Verified |  |  |
| V1 | vertical 1 | blocked area 1 | left exit area | silk soar AND ( run OR faydown OR clawline OR sharpdart OR ( ( ledge grab OR cling grip ) AND ( dash OR drifters ) ) ) |  | Verified |  |  |
| V2 | vertical 2 | blocked area 1 | lore area | break wall left |  | Verified | ✓ |  |
| V2 | vertical 2 | lore area | blocked area 1 | silk soar AND break wall right |  | Verified | ✓ |  |
| BW1 | break wall 1 | lore area | blocked area 2 | break wall right |  | Verified | ✓ |  |
| BW1 | break wall 1 | blocked area 2 | lore area | break wall left |  | Verified | ✓ |  |
| V3 | vertical 3 | blocked area 2 | crest area | break wall right |  | Verified | ✓ |  |
| V3 | vertical 3 | crest area | blocked area 2 | silk soar AND break wall left |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Crest Shaman | crest area | none |  | Verified | collectible | ✓ |  |
| 2 | Shaman Crest Ritual Recipe | lore area | none |  | Verified | lore | ✓ |  |

## Room Images

### Connections

[![Connections for Ruined Chapel Crest Chamber (Tut_05)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-connections.png)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-connections.png)

### Checks

[![Checks for Ruined Chapel Crest Chamber (Tut_05)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-checks.png)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-checks.png)

### Scene

[![Scene for Ruined Chapel Crest Chamber (Tut_05)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-scene.png)](../00-annotations/moss-grotto/ruined-chapel-crest-chamber-scene.png)
