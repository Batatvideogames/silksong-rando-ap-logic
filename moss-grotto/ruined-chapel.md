# Ruined Chapel (Tut_03)

**Game ID:** Tut_03

**Contributors:** herounit

## Subrooms

- chapel
- boss arena
- bench passage
- bench spot

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | bench spot | [Moss Grotto Center (Tut_01)](moss-grotto-center.md) | UL | none |  | Verified |  |
| AR | ascend rope | chapel | [Bone Bottom Town (Bonetown)](../bone-bottom/bone-bottom-town.md) | DR | none |  | Verified |  |
| CD | chapel door | chapel | [Ruined Chapel Interior](ruined-chapel-interior.md) | CD |  | TODO |  | how the heck do you open this door again? |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | bench passage | boss arena | break vines left (starts fight) |  | Verified |  |
| RB | right boss entrance | boss arena | bench passage | complete moss mother boss fight |  | Verified |  |
| LB | left boss entrance | chapel | boss arena | none (starts fight) |  | Verified |  |
| LB | left boss entrance | boss arena | chapel | complete moss mother boss fight |  | Verified |  |
| V1 | ledge grab | bench spot | bench passage | ledge grab OR faydown OR silk soar OR cling grip |  | Verified |  |
| V1 | ledge grab | bench passage | bench spot | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| moss mother boss fight | boss arena | none |  | Verified | boss |  |
| bench | bench spot | none |  | Verified | bench |  |

## Notes

ROOM BUG: fighting moss mother without breaking the vines on the right side of the arena (by approaching from the left), you get locked into the arena with darkness still covering the area.

Ascend rope AND the ceiling are valid exits - but I believe they take you to the same bot1 exit on the other side.
