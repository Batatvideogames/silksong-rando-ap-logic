# Coral Tower Entrance (Coral_28)

**Game ID:** Coral_28

**Contributors:** Pxyl

## Subrooms

- Exit
- Door

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Sands of Karak Upper Left Long Room (Coral_27)](sands-of-karak-upper-left-long-room.md) | L | None |  | Verified |  |
| D | door1 | Door | [Coral Tower (Coral_Tower_01)](coral-tower.md) | L | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Door | Exit | Clawline OR Sharpdart OR Drifters Cloak OR ( Sprint AND ( Dash OR Faydown Cloak OR easy Beast Crest pogo ) ) OR  ( Faydown Cloak AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo ( Wanderer Crest AND Needle strike ) ) ) |  | Verified |  |
| SC | Sandcarver Pit | Exit | Door | Clawline OR Sharpdart OR ( Sprint AND ( Dash OR Faydown Cloak OR Drifters Cloak OR easy Beast Crest pogo OR easy Architect Crest pogo ) )  OR ( Sprint AND ( easy Shaman Crest pogo OR easy Hunter crest pogo OR medium Heal stall OR ( easy Wanderer Crest pogo AND easy Needle Strike stall AND Ledge Grab ) ) ) OR ( Dash AND ( easy Reaper Crest pogo OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak OR ( easy Architect Crest pogo AND ( Ledge Grab OR easy Needle Strike stall ) ) ) ) OR ( Faydown Cloak AND ( easy Beast Crest pogo OR easy Architect Crest pogo OR medium Shaman Crest pogo OR easy Hunter Crest pogo OR Drifters Cloak OR ( easy Reaper Crest pogo AND Ledge Grab ) OR ( easy Wanderer Crest pogo AND easy Needle strike stall ) ) ) OR ( Drifters Cloak AND ( easy Beast Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo OR easy Wanderer Crest pogo OR medium Heal Stall OR Ledge Grab OR Silk Soar OR ( easy Reaper Crest pogo AND easy Needle Strike stall ) ) ) OR ( Silk Soar AND ( easy Beast Crest pogo OR easy Architect Crest pogo ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Resting Site | Door | prereq Wish: A vassal lost started1 AND Steel soul AND ( Sprint AND ( ( Dash OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo ) OR Clawline OR ( Silk soar AND Ledge Grab ) ) ) |  | Verified | collectible | Not Included for the better |
| Wish: A vassal lost started1 | Door | None |  | Verified | event |  |
