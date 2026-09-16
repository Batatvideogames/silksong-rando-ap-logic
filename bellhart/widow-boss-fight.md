# Widow Boss Fight (Belltown_Shrine)

**Game ID:** Belltown_Shrine

**Contributors:** Pyxl

## Subrooms

- Arena
- Upper

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Arena | [Bellhart Right Entrance (Belltown_06)](bellhart-right-entrance.md) | UL | None |  | Verified |  |
| C | top1 | Upper | [Upper Bellhart (Belltown_04)](upper-bellhart.md) | F | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy Heal Stall AND ( Faydown Cloak OR Drifters Cloak ) ) |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TD | Trapdoor | Arena | Upper | prereq widow lever AND ( Cling Grip OR Silk soar OR ( Dash AND Scuttlebrace ) ) |  | Verified | Permanently open |
| TD | Trapdoor | Upper | Arena | prereq widow lever |  | Verified | Permanently open |
| RH | Roof Hole | Arena | Upper | Silk Soar OR ( Cling Grip AND Faydown Cloak AND ( Clawline OR Sharpdart ) ) |  | Verified |  |
| RH | Roof Hole | Upper | Arena | None |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Widow | Arena | None |  | Verified | boss |  |
| Bell: Bellhart | Arena | Activate Bellshrine Lever |  | Verified | collectible |  |
| Needolin | Arena | Defeat Boss Widow |  | Verified | collectible |  |
| Bellshrine Lever | Arena | Defeat Boss Widow |  | Verified | switch |  |
| Bench | Arena | Activate Bellshrine Lever |  | Verified | bench |  |
