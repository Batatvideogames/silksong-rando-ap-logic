# Choral Chambers Dining Room (Song_09b)

**Game ID:** Song_09b

**Contributors:** samupo

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Diner |  |
| S2 | Below Diner |  |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Diner | [Choral Chambers Over Dininig (Song_09)](choral-chambers-over-dininig.md) | B | ledge grab OR clawline OR faydown cloak OR silk soar |  |  | ✓ |  |
| L | left1 | Below Diner | [Choral Chambers Flea Shaft (Song_11)](choral-chambers-flea-shaft.md) | S1R | none |  |  | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Diner | Below Diner | Activate Lever - Dining #1 OR Activate Lever - Dining #2 |  |  |  |  |
| V | Vertical | Below Diner | Diner | (silk soar AND (Activate Lever - Dining #1 OR Activate Lever - Dining #2)) OR (cling grip left AND Activate Lever - Dining #1) OR (cling grip right AND Activate Lever - Dining #2) |  |  |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Silkeater: Choral Chambers East | Below Diner | ledge grab OR easy hazard respawn |  |  | collectible | ✓ |  |
| 2 | Great Taste of Pharloom Wish Promised | Diner | none |  | Verified | event | ✓ |  |
| 3 | Lever - Dining #1 | Diner | none |  |  | switch | ✓ |  |
| 4 | Lever - Dining #2 | Diner | none |  |  | switch | ✓ |  |
| 5 | Choir Pouncer 1 |  |  |  |  | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-connections.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-connections.png)

### Checks

[![Checks for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-checks.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-checks.png)

### Scene

[![Scene for Choral Chambers Dining Room (Song_09b)](../00-annotations/choral-chambers/choral-chambers-dining-room-scene.png)](../00-annotations/choral-chambers/choral-chambers-dining-room-scene.png)
