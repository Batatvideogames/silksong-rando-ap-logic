# Deep Docks Upper Spire (Bone_East_05)

**Game ID:** Bone_East_05

**Contributors:** herounit

## Subrooms

- flea platform
- spire
- right exit platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | spire | [Deep Docks Bench Shaft (Dock_01)](deep-docks-bench-shaft.md) | UR | none (door switch is on this side) |  |  |  |
| R | right1 | right exit platform | [Is this still Deep Docks? (West) (Bone_East_04b)](is-this-still-deep-docks-west.md) | L | none |  |  | need to verify if silksoar works with magma bell |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SR | spire right | spire | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR (silk soar AND magma bell AND blue slot) OR beast crest |  |  | i did it exactly ONCE with shaman crest and couldn't do it again :( |
| SR | spire right | right exit platform | spire | none |  |  |  |
| PG | platform gaps | spire | flea platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR silk soar |  |  | Removed sharpdart - too many gaps in a row |
| PG | platform gaps | flea platform | spire | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea platform | none |  |  |  |  |
| swift step | spire | none |  |  |  |  |
| door switch | spire | none |  |  |  |  |
| platform switch | flea platform | none |  |  |  |  |
