# Grand Gate Courtroom (Song_19_entrance)

**Game ID:** Song_19_entrance

**Contributors:** samupo

## Subrooms

- lower section
- upper section

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | lower section | [Grand Bridge (Coral_10)](grand-bridge.md) | R | Prereq Grand Bridge Plate IN Grand Bridge |  | Verified | blocked |
| TR | right1 | upper section | [Grand Gate Maintenance Room (Song_01c)](grand-gate-maintenance-room.md) | L | silk soar OR faydown cloak OR cling grip OR ledge grab |  | Verified |  |
| R | right2 | lower section | [Grand Elevator (Under_01)](grand-elevator.md) | TL | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BG | big gap | lower section | upper section | silk soar OR faydown cloak OR (ledge grab AND (progressive swift step 1 OR clawline OR sharpdart OR flea brew OR easy hunter pogo OR easy architect pogo OR drifters cloak)) |  | Verified |  |
| BG | big gap | upper section | lower section | nothing |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Spool Fragment: Grand Gate | upper section | silk soar OR ((cling grip OR scuttlebrace) AND (faydown cloak OR ledge grab)) |  | Verified | collectible |  |
| Map Purchase: Grand Gate | lower section | None |  | Verified | collectible |  |
| metal bars | upper section | break wall right OR break wall up OR clear metal wall IN grand gate maintenance room |  | Verified | blockade |  |

## Notes

the syntax assumes upswing is not randomized otherwise, must make upswing required for the subroom transition and the check of the spool
