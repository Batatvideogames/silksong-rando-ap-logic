# Chapel of the Wanderer (Chapel_Wanderer)

**Game ID:** Chapel_Wanderer

**Contributors:** herounit

## Subrooms

- door platform
- upper right
- middle right
- gauntlet arena
- lower left shaft 1
- lower left shaft 2
- crest room
- upper left

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door | door platform | [Bonegrave (Bonegrave)](bonegrave.md) | CD | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | right 1 | door platform | upper right | none (falling) |  | Verified |  |
| R1 | right 1 | upper right | door platform | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| R2 | right 2 | upper right | middle right | none (falling) |  | Verified |  |
| R2 | right 2 | middle right | upper right | silk soar OR cling grip |  | Verified |  |
| GR | gauntlet right | middle right | gauntlet arena | none (starts gauntlet) |  | Verified |  |
| GR | gauntlet right | gauntlet arena | middle right | clear gauntlet fight |  | Verified |  |
| GL | gauntlet left | gauntlet arena | lower left shaft 2 | clear gauntlet fight |  | Verified |  |
| GL | gauntlet left | lower left shaft 2 | gauntlet arena | none (starts gauntlet) |  | Verified | need to verify this with noclip, but probably doesn't matter |
| L1 | left 1 | door platform | upper left | none (falling) |  | Verified |  |
| L1 | left 1 | upper left | door platform | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| BW | break wall | lower left shaft 1 | upper left | clear one way wall |  | Verified |  |
| BW | break wall | upper left | lower left shaft 1 | clear one way wall |  | Verified |  |
| L2 | left 2 | lower left shaft 1 | lower left shaft 2 | none (falling) |  | Verified |  |
| L2 | left 2 | lower left shaft 2 | lower left shaft 1 | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| L3 | left 3 | lower left shaft 2 | crest room | none (falling) |  | Verified |  |
| L3 | left 3 | crest room | lower left shaft 2 | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wanderer's crest | crest room | none |  | Verified | collectible |  |
| One Way Wall | lower left shaft 1 | break wall up OR break wall right |  | Verified | blockade |  |
| gauntlet fight | gauntlet arena | none |  | Verified | gauntlet |  |
| rosary cache bongrave 1 | upper left | none |  | Verified | collectible |  |
| rosary cache bongrave 2 | upper left | none |  | Verified | collectible |  |
| rosary cache bongrave 3 | upper right | none |  | Verified | collectible |  |
| rosary cache bongrave 4 | upper right | none |  | Verified | collectible |  |

## Notes

need see if there are other checks in here
