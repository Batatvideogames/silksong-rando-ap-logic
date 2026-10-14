# Choral Chambers East to West (Song_27)

**Game ID:** Song_27

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Left Side | ✓ |
| S2 | Right Side | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Left Side | [Choral Chambers Below Dining (Song_18)](choral-chambers-below-dining.md) | B | One way, can't be used at all from this side even if you entered from it! | TODO |  | ✓ | One way, can't be used at all from this side even if you entered from it! |
| R | right1 | Right Side | [Grand Bellway Shaft (Song_20)](grand-bellway-shaft.md) | UL |  | TODO |  | ✓ |  |
| L | left1 | Left Side | [Choral Chambers Eastern Shaft (Song_05)](choral-chambers-eastern-shaft.md) | R2 | activate door switch |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left Side | Right Side | clawline OR ledge grab OR faydown cloak OR spike pogo |  | Verified | ✓ |  |
| H | Horizontal | Right Side | Left Side | clawline OR ledge grab OR faydown cloak OR spike pogo |  |  | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | door switch | Left Side | flip switch left |  | Verified | switch |  |  |
| 2 | Second Sentinel Encounter | Right Side | complete THE Second Sentinel Activation |  | Verified | event | ✓ | Spawn conditions: songChevalierActiveInSong_27=true, songChevalierSeenInSong_27=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false FSM Boolean flags: encounteredSongChevalierBoss |
| 3 | Choir Hornhead 1 | Right Side | Invalid |  |  | enemy | ✓ | Part of Second Sentinel Encounter.  Spawn conditions: songChevalierActiveInSong_27=true, songChevalierSeenInSong_27=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false |
| 4 | Choir Flyer 1 | Right Side | Invalid |  |  | enemy | ✓ | Part of Second Sentinel Encounter.  Spawn conditions: songChevalierActiveInSong_27=true, songChevalierSeenInSong_27=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false |
| 5 | Envoy 1 | Right Side | Invalid |  |  | enemy | ✓ | Part of Second Sentinel Encounter.  Spawn conditions: songChevalierActiveInSong_27=true, songChevalierSeenInSong_27=false, songChevalierEncounterCooldown=false, songChevalierQuestReady=false |
| 6 | Choir Hornhead 2 |  |  |  |  | enemy | ✓ |  |
| 7 | Choir Flyer 2 |  |  |  |  | enemy | ✓ |  |
| 8 | Envoy 2 |  |  |  |  | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 9 | Choir Hornhead 3 |  |  |  |  | enemy | ✓ |  |
| 10 | Choir Flyer 3 |  |  |  |  | enemy | ✓ |  |
| 11 | Envoy 3 |  |  |  |  | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 12 | Cogworker 1 |  |  |  |  | enemy | ✓ |  |
| 13 | Cogworker 2 |  |  |  |  | enemy | ✓ |  |
| 14 | Cogworker 3 |  |  |  |  | enemy | ✓ |  |
| 15 | Choir Pouncer 1 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 16 | Choir Flyer 4 |  | Normal World Spawn |  |  | enemy | ✓ |  |
| 17 | Void Mass 1 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |
| 18 | Reed 1 |  | Black Thread World Spawn |  |  | enemy | ✓ |  |

## Notes

Door on the east can be only opened from the west

## Room Images

### Connections

[![Connections for Choral Chambers East to West (Song_27)](../00-annotations/choral-chambers/choral-chambers-east-to-west-connections.png)](../00-annotations/choral-chambers/choral-chambers-east-to-west-connections.png)

### Checks

[![Checks for Choral Chambers East to West (Song_27)](../00-annotations/choral-chambers/choral-chambers-east-to-west-checks.png)](../00-annotations/choral-chambers/choral-chambers-east-to-west-checks.png)

### Scene

[![Scene for Choral Chambers East to West (Song_27)](../00-annotations/choral-chambers/choral-chambers-east-to-west-scene.png)](../00-annotations/choral-chambers/choral-chambers-east-to-west-scene.png)
