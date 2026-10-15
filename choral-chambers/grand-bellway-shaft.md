# Grand Bellway Shaft (Song_20)

**Game ID:** Song_20

**Contributors:** samupo,Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top |  |
| S2 | Upper Right |  |
| S3 | Upper Left |  |
| S4 | Right Stage |  |
| S5 | Bottom Left |  |
| S6 | Bottom Right |  |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Upper Left | [Choral Chambers East to West (Song_27)](choral-chambers-east-to-west.md) | R | none |  |  | ✓ |  |
| T | top1 | Top | [Rotating Tunnel (Song_20b)](rotating-tunnel.md) | B | none |  |  | ✓ |  |
| UR | right4 | Upper Right | [Grand Bellway Library (Library_03)](../whispering-vaults/grand-bellway-library.md) | L | none |  |  | ✓ |  |
| RS | right5 | Right Stage | [Trobbio (Library_13)](../whispering-vaults/trobbio.md) | L | none |  |  | ✓ |  |
| BR | right6 | Bottom Right | [Grand Bellway (Bellway_City)](grand-bellway.md) | L | none |  |  | ✓ |  |
| BL | left2 | Bottom Left | [Grand Bellway Side Room (Song_24)](grand-bellway-side-room.md) | R | none |  |  | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | Top to Upper Right | Top | Upper Right | none |  | Verified |  | falling |
| F2 | Upper Right to Upper Left | Upper Right | Upper Left | none |  | Verified |  | falling |
| F3 | Upper Left to Right Stage | Upper Left | Right Stage | none |  | Verified |  | falling |
| F4 | Right Stage to Bottom Left | Right Stage | Bottom Left | none |  | Verified |  | falling |
| F5 | Bottom Left to Bottom Right | Bottom Left | Bottom Right | none |  | Verified |  | falling |
| J5 | Bottom Right to Bottom Left | Bottom Right | Bottom Left | silk soar OR cling grip OR (ledge grab AND hard pogo off Choristor AND (easy Shaman pogo OR hard Reaper pogo OR (hard [Hunter, Beast, Witch, Wanderer] pogo AND hard damage boost) OR (hard Architect pogo AND clawline AND hard damage boost))) |  | Verified |  |  |
| J4 | Bottom Left to Right Stage | Bottom Left | Right Stage | cling grip OR (ledge grab AND faydown cloak) OR silk soar OR easy pogo off Reed |  | Verified |  |  |
| J3 | Right Stage to Upper Left | Right Stage | Upper Left | easy [Hunter, Reaper, Wanderer, Shaman] pogo OR ledge grab |  | Verified |  |  |
| J3E | Bottom Right to Upper Left | Bottom Right | Upper Left | silk soar |  | Verified |  |  |
| J2 | Upper Left to Upper Right | Upper Left | Upper Right | (cling grip AND (faydown cloak OR dash OR clawline)) OR silk soar OR easy pogo off [Choir Elder, Choir Flyer, Reed] |  | Verified |  | pogo first the elder then Choir flyer then Reed twice |
| J1 | Upper Right to Top | Upper Right | Top | ledge grab OR silk soar OR clawline OR faydown cloak OR easy pogo off Reed |  | Verified |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Lace Second Encounter | Bottom Right | none |  | Verified | event |  |  |
| 2 | import enemies |  |  | TODO | Needs verification |  |  |  |
| 3 | Choir Pouncer 1 |  |  |  |  | enemy | ✓ |  |
| 4 | Choristor 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 5 | Reed 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 6 | Choir Elder 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 7 | Reed 2 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 8 | Reed 3 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 9 | Envoy 1 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: laceMeetCitadel=false |
| 10 | Reed 4 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: laceMeetCitadel=false |
| 11 | Envoy 2 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: bellShrineEnclave=true |
| 12 | Choristor 2 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: bellShrineEnclave=true |
| 13 | Choir Flyer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 14 | Choir Bellbearer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 15 | Choristor 3 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 16 | Reed 5 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Grand Bellway Shaft (Song_20)](../00-annotations/choral-chambers/grand-bellway-shaft-connections.png)](../00-annotations/choral-chambers/grand-bellway-shaft-connections.png)

### Checks

[![Checks for Grand Bellway Shaft (Song_20)](../00-annotations/choral-chambers/grand-bellway-shaft-checks.png)](../00-annotations/choral-chambers/grand-bellway-shaft-checks.png)

### Scene

[![Scene for Grand Bellway Shaft (Song_20)](../00-annotations/choral-chambers/grand-bellway-shaft-scene.png)](../00-annotations/choral-chambers/grand-bellway-shaft-scene.png)
