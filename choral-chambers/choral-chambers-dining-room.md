# Choral Chambers Dining Room (Song_09b)

**Game ID:** Song_09b

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Diner |  |
| S2 | Below Diner |  |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Diner | [Choral Chambers Over Dining (Song_09)](choral-chambers-over-dining.md) | B | ledge grab either OR faydown cloak OR silk soar OR cling grip either |  | Verified | ✓ |  |
| L | left1 | Below Diner | [Choral Chambers Flea Shaft (Song_11)](choral-chambers-flea-shaft.md) | S1R | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Diner | Below Diner | Activate Lever - Dining #1 OR Activate Lever - Dining #2 |  | Verified |  |  |
| V | Vertical | Below Diner | Diner | ((cling grip left OR silk soar) AND Activate Lever - Dining #1) OR (cling grip right AND Activate Lever - Dining #2) |  | Verified |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Silkeater: Choral Chambers East | Below Diner | ledge grab OR easy hazard respawn |  | Verified | collectible | ✓ |  |
| 2 | Great Taste of Pharloom Wish Promised | Diner | none |  | Verified | event | ✓ |  |
| 3 | Lever - Dining #1 | Diner | none |  | Verified | switch | ✓ |  |
| 4 | Lever - Dining #2 | Diner | none |  | Verified | switch | ✓ |  |
| 5 | Choir Pouncer 1 | Below Diner | Invalid |  | Verified | enemy | ✓ | Spawn conditions:  citadelWoken == false  not sure if you can ever reach this guy - reaching the citadel wakes it as far as I know. maybe room rando? - hero, 10/16 |

## Room Images

### Connections

[![Connections for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-connections.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-connections.png)

### Checks

[![Checks for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-checks.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-checks.png)

### Scene

[![Scene for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-scene.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-scene.png)
