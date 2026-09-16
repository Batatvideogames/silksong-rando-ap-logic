# Memorium Karak (Arborium_06)

**Game ID:** Arborium_06

**Contributors:** heric

## Subrooms

- Right side
- Middle
- Left side
- left and up

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right side | [Seed Shooty Memorium (Arborium_03)](seed-shooty-memorium.md) | UT | none |  | Verified |  |
| B | bot1 | Middle | [Memorium water room (Arborium_05)](memorium-water-room.md) | T | complete Water karak ceiling IN Memorium water room |  | Verified | one way wall |
| L | left1 | Left side | [Memorium Start Shaft (Arborium_01)](memorium-start-shaft.md) | R | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| rm | blind gameplay | Right side | Middle | easy enemy pogo OR ledge grab OR faydown cloak OR silk soar | TODO | Verified | Room is blind unless dark stuff is removed |
| mr | middle --> right | Middle | Right side | easy enemy pogo OR (ledge grab AND (dash OR run)) OR faydown cloak OR dash OR (run AND cling grip) |  | Verified | theres also an enemy that you can super easily clawline even on accident to get the height you need but I have no clue what to label that as you can also clawline plus silk soar but it feels like it would fall under a skip of some kind and i feel like easy enemy pogo already covers that  damage boosts arent accounted for but if implemented "OR easy damage boost" that can be |
| Ml | Middle <-> Left | Left side | Middle | run OR drifter's cloak OR faydown cloak OR easy architect pogo OR (clawline AND silkhearts 1) OR easy beast pogo | TODO | Verified | Room is blind unless dark stuff is removed |
| Ml | Middle <-> Left | Middle | Left side | medium shaman pogo OR run OR faydown cloak  OR clawline OR drifter's cloak OR easy architect pogo OR easy hunter pogo OR easy needle strike stall(wanderers) OR easy beast pogo |  | Verified | can be done no items but need a precise movement option |
| lu | idk | Middle | left and up | faydown cloak OR (silk soar AND (dash OR clawline)) OR (run AND (ledge grab OR cling grip)) OR (clawline AND ledge grab) |  | Verified |  |
| ll | smth | Left side | left and up | faydown cloak OR (silk soar AND (dash OR (clawline AND silkhearts 1))) OR (run AND (ledge grab OR cling grip)) OR (clawline AND silkhearts 1 AND ledge grab) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Shell Shard Cache #2 | Middle | cling grip OR ledge grab OR faydown cloak OR silksoar OR easy shaman pogo |  | Verified | resource |  |
| Memorium - Shell Shard Cache #1 | left and up | none |  | Verified | resource |  |
