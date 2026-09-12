# Sands of Karak Tall Centre Room (Coral_35b)

**Game ID:** Coral_35b

**Contributors:** Pyxl

## Subrooms

- Ground Level
- Shakra Ledge
- Stalactite
- Crust Nut Ledge
- Bridge Level
- Voltnest Level

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | Voltnest Level | [Voltnest (Coral_29)](voltnest.md) | L | None |  | Verified |  |
| LL | left3 | Ground Level | [Sands of Karak Lower Left Long Room (Coral_23)](sands-of-karak-lower-left-long-room.md) | R | None |  | Verified |  |
| F | bot1 | Ground Level | [Blasted Steps Thin Long Vertical (Coral_35)](../blasted-steps/blasted-steps-thin-long-vertical.md) | T | prereq Stalactite |  | Verified |  |
| LR | right2 | Ground Level | [Sands of Karak Lower Right Long Room (Coral_24)](sands-of-karak-lower-right-long-room.md) | L | None |  | Verified |  |
| UL | left2 | Bridge Level | [Sands of Karak Upper Left Long Room (Coral_27)](sands-of-karak-upper-left-long-room.md) | R | None |  | Verified |  |
| UML | left5 | Crust Nut Ledge | [Crustnut (Coral_41)](crustnut.md) | R | None |  | Verified |  |
| UR | right1 | Bridge Level | [Sands of Karak Upper Right Long Room (Coral_44)](sands-of-karak-upper-right-long-room.md) | L | None |  | Verified |  |
| ULL | left4 | Shakra Ledge | [Sands of Shakra (Coral_40)](sands-of-shakra.md) | R | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | Lower Shaft | Ground Level | Shakra Ledge | Silk Soar OR ( Faydown Cloak AND ( Cling grip OR ( Dash AND Scuttlebrace ) ) ) OR ( Cling grip AND ( ( Dash OR Sprint OR Drifters Cloak OR Clawline OR Sharpdart ) OR ( ( easy Beast Crest pogo OR easy Architect Crest pogo ) AND easy Needle Strike stall ) ) ) |  | Verified |  |
| LS | Lower Shaft | Shakra Ledge | Ground Level | None |  | Verified |  |
| ST1 | Stalactite | Ground Level | Stalactite | Silk Soar |  | Verified |  |
| ST1 | Stalactite | Stalactite | Ground Level | None |  | Verified |  |
| ST2 | Stalactite2 | Shakra Ledge | Stalactite | ( ( Scuttlebrace OR Cling grip ) AND ( Dash OR Sprint OR Drifters Cloak OR Faydown Cloak OR SharpDart OR Clawline ) ) OR ( Cling Grip AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR easy Shaman Crest pogo OR ( ( easy Reaper Crest pogo OR easy Architect Crest pogo ) AND easy Needle Strike stall ) ) ) |  | Verified |  |
| St2 | Stalactite2 | Stalactite | Shakra Ledge | None |  | Verified |  |
| US1 | Upper Shaft1 | Shakra Ledge | Crust Nut Ledge | ( ( Scuttlebrace  OR  Cling grip )  AND  ( ( Dash AND ( Ledge Grab OR easy Shaman Crest pogo ) )   OR Clawline OR Faydown Cloak OR Sharpdart ) ) OR ( Cling Grip AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR ( easy Reaper Crest pogo AND easy Needle Strike stall ) ) ) |  | Verified |  |
| US1 | Upper Shaft1 | Crust Nut Ledge | Shakra Ledge | None |  | Verified |  |
| US2 | Upper Shaft2 | Crust Nut Ledge | Bridge Level | Prereq Stalactite 2 AND ( (  Scuttlebrace OR Cling grip OR  Faydown Cloak  OR (  Silk Soar AND ( easy Architect Crest pogo OR easy Witch Crest pogo OR easy Reaper Crest pogo OR easy Shaman Crest pogo OR ( easy Wanderer Crest pogo AND ( ledge grab OR Dash OR Sharpdart OR Clawline OR Drifters Cloak ) ) ) ) ) ) |  | Verified |  |
| US2 | Upper Shaft2 | Bridge Level | Crust Nut Ledge | Prereq Stalactite 2 |  | Verified |  |
| VS | Voltwyrm Shaft | Bridge Level | Voltnest Level | ( Cling Grip AND Faydown Cloak AND ( Clawline OR Dash OR Sharpdart OR ( ( Medium Beast Crest pogo AND medium Needle Strike stall AND Cling Grip  )  OR ( ( ( medium Architect Crest pogo OR medium Reaper Crest pogo )  AND medium Needle Strike stall ) OR medium Shaman Crest pogo )  )  )  ) OR (  Silk soar AND ( Cling Grip OR Faydown Cloak OR Scuttlebrace ) ) |  | Verified |  |
| VS | VoltWyrm Shaft | Voltnest Level | Bridge Level | None |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Stalactite | Stalactite | None |  | Verified | blockade |  |
| Stalactite 2 | Bridge Level | None |  | Verified | blockade |  |
