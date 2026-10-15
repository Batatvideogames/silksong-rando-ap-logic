# Choral Chambers Outside Spa (Song_04)

**Game ID:** Song_04

**Contributors:** samupo

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Base | ✓ |
| S2 | Gauntlet | ✓ |
| S3 | Left | ✓ |
| S4 | Top | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Left | [Choral Chambers Above Ventrica (Song_03)](choral-chambers-above-ventrica.md) | T | none |  | Verified | ✓ |  |
| L | left1 | Top | [Slab Bridge (Slab_01)](../the-slab/slab-bridge.md) | R | none |  | Verified | ✓ |  |
| R1 | right1 | Top | [Choral Chambers Western Shaft (Song_12)](choral-chambers-western-shaft.md) | BL | none |  | Verified | ✓ |  |
| R2 | right2 | Base | [Choral Chambers Spa (Song_10)](choral-chambers-spa.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Base | none |  | Verified | ✓ | falling |
| V | Vertical | Base | Top | cling grip OR silk soar |  | Verified | ✓ |  |
| GL | Gauntlet Left | Left | Gauntlet | none |  | Verified | ✓ |  |
| GL | Gauntlet Left | Gauntlet | Left | defeat Gauntlet Fight |  | Verified | ✓ |  |
| GR | Gauntlet Right | Base | Gauntlet | none |  | Verified | ✓ |  |
| GR | Gauntlet Right | Gauntlet | Base | defeat Gauntlet Fight |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Heavy Rosary Necklace - Choral Chambers | Base | cling grip OR silk soar |  |  | collectible | ✓ | Secret hidden by breaking the ceiling |
| 2 | Second Sentinel Encounter | Gauntlet | defeat Gauntlet Fight AND Act 2 AND complete THE Second Sentinel Activation |  |  | resource |  | only act 2 per the wiki |
| 3 | Switch - Outside Spa | Left | none |  |  | switch | ✓ |  |
| 4 | import enemies |  |  | TODO | Needs verification |  |  |  |
| 5 | Gauntlet Fight | Gauntlet | none |  |  | gauntlet |  |  |
| 6 | Drapemite 1 |  |  |  |  | enemy | ✓ |  |
| 7 | Reed 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 8 | Choristor 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 9 | Choir Pouncer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 10 | Choir Flyer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 11 | Clawmaiden 1 |  | Normal World Spawn |  |  | enemy | ✓ | FSM Boolean flags: marionettesBurned |
| 12 | Choristor 2 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 13 | Choir Bellbearer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 14 | Reed 2 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 15 | Reed 3 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 16 | Clawmaiden 2 |  | Normal World Spawn |  |  | enemy | ✓ | FSM Boolean flags: marionettesBurned |
| 17 | Song Knight 1 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: songChevalierActiveInSong_04=true, songChevalierSeenInSong_04=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false FSM Boolean flags: encounteredSongChevalierBoss |
| 18 | Reed 4 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: songChevalierActiveInSong_04=true, songChevalierSeenInSong_04=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false |
| 19 | Choristor 3 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: songChevalierActiveInSong_04=true, songChevalierSeenInSong_04=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false |
| 20 | Void Mass 1 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 21 | Choristor 4 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 22 | Choir Bellbearer 2 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Outside Spa (Song_04)](../00-annotations/choral-chambers/choral-chambers-outside-spa-connections.png)](../00-annotations/choral-chambers/choral-chambers-outside-spa-connections.png)

### Checks

[![Checks for Choral Chambers Outside Spa (Song_04)](../00-annotations/choral-chambers/choral-chambers-outside-spa-checks.png)](../00-annotations/choral-chambers/choral-chambers-outside-spa-checks.png)

### Scene

[![Scene for Choral Chambers Outside Spa (Song_04)](../00-annotations/choral-chambers/choral-chambers-outside-spa-scene.png)](../00-annotations/choral-chambers/choral-chambers-outside-spa-scene.png)
