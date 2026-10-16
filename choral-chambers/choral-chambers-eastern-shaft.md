# Choral Chambers Eastern Shaft (Song_05)

**Game ID:** Song_05

**Contributors:** Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Section 1 | ✓ |
| S2 | Section 2 | ✓ |
| S3 | Section 3 | ✓ |
| S4 | Section 4 | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | left5 | Section 1 | [Choral Chambers Below Spa (Song_02)](choral-chambers-below-spa.md) | R | none |  | Verified | ✓ |  |
| R1 | right3 | Section 1 | [Whiteward Entrance (Ward_01)](../whiteward/whiteward-entrance.md) | TL | none |  | Verified | ✓ |  |
| L2 | left4 | Section 3 | [Choral Chambers Merchant Room (Song_07)](choral-chambers-merchant-room.md) | R | none |  | Verified | ✓ |  |
| R2 | right4 | Section 2 | [Choral Chambers East to West (Song_27)](choral-chambers-east-to-west.md) | L | activate Lever East to West IN choral chambers east to west |  | Verified | ✓ |  |
| L3 | left3 | Section 3 | [Choral Chambers Flea Shaft (Song_11)](choral-chambers-flea-shaft.md) | BR | none |  | Verified | ✓ |  |
| R4 | right2 | Section 4 | [Choral Chambers Below Dining (Song_18)](choral-chambers-below-dining.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Section 1 to Section 2 | Section 1 | Section 2 | ledge grab OR silk soar OR (cling grip AND (dash OR clawline)) |  |  | ✓ |  |
| V2 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar OR (cling grip AND (ledge grab OR clawline)) OR faydown cloak OR (medium pogo off Reed AND medium Heal stall AND medium damage boost) OR (easy Shaman pogo AND easy pogo off Reed) |  |  | ✓ | Reed pogo |
| V3 | Section 3 to Section 4 | Section 3 | Section 4 | ledge grab OR clawline OR silk soar OR easy pogo off [Reed, Choristor] |  |  | ✓ |  |
| F4 | Falling from Section 4 | Section 4 | Section 3 | none |  |  |  | falling |
| F3 | Falling from Section 3 | Section 3 | Section 2 | none |  |  |  | falling |
| F2 | Falling from Section 2 | Section 2 | Section 1 | none |  |  |  | falling |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Lace Second Encounter | Section 1 | none |  | Verified | event |  |  |
| 2 | Choristor 1 |  |  |  |  | enemy | ✓ |  |
| 3 | Choir Pouncer 1 |  |  |  |  | enemy | ✓ |  |
| 4 | Reed 1 |  |  |  |  | enemy | ✓ |  |
| 5 | Choir Hornhead 1 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: song05MarchGroupReady=true |
| 6 | Envoy 1 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: song05MarchGroupReady=true |
| 7 | Choristor 2 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: song05MarchGroupReady=true |
| 8 | Reed 2 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 9 | Choir Bellbearer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 10 | Choir Pouncer 2 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 11 | Envoy 2 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: laceMeetCitadel=false |
| 12 | Reed 3 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: laceMeetCitadel=false |
| 13 | Reed 4 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 14 | Reed 5 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 15 | Void Mass 1 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 16 | Choir Bellbearer 2 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 17 | Choir Hornhead 2 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Eastern Shaft (Song_05)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-connections.png)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-connections.png)

### Checks

[![Checks for Choral Chambers Eastern Shaft (Song_05)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-checks.png)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-checks.png)

### Scene

[![Scene for Choral Chambers Eastern Shaft (Song_05)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-scene.png)](../00-annotations/choral-chambers/choral-chambers-eastern-shaft-scene.png)
