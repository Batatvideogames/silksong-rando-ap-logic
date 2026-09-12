# Cogwork Core West Gauntlet (Cog_05)

**Game ID:** Cog_05

**Contributors:** Rebel

## Subrooms

- Top Entrance
- Main
- Arena
- Left Entrance

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right2 | Main | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | ML | Nothing. |  | Verified |  |
| L | left1 | Left Entrance | [Choral Chambers Over Dininig (Song_09)](../choral-chambers/choral-chambers-over-dininig.md) | R | Nothing. |  | Verified |  |
| T | top1 | Top Entrance | [Cogwork Core Second Sentinel (Cog_10)](cogwork-core-second-sentinel.md) | B | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MT | Main-Top | Main | Top Entrance | (Silk Soar OR (Faydown Cloak AND (Cling Grip OR Scuttlebrace OR Ledge Grab))) |  | Verified |  |
| MT | Main-Top | Top Entrance | Main | Nothing. (fall) |  | Verified |  |
| ML | Main-Left | Main | Left Entrance | (Complete Cogwork Core: Gauntlet #1 AND (Silk Soar OR Cling Grip OR Scuttlebrace)) |  | Verified |  |
| ML | Main-Left | Left Entrance | Main | Complete Cogwork Core: Gauntlet #1 |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Gauntlet #1 | Arena | Nothing |  | Verified | gauntlet |  |
