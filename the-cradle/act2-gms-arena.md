# ACT2 GMS Arena (Cradle_03)

**Game ID:** Cradle_03

**Contributors:** Pyxl

## Subrooms

- Bottom
- Shell Shard Ledge
- Arena

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | Bottom | [Act2 Cradle Left Shaft (Cradle_02)](act2-cradle-left-shaft.md) | UR | None |  | Verified | None |
| R | right2 | Bottom | [Terminus Ventrica (Tube_Hub)](terminus-ventrica.md) | UL | None |  | Verified | None |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | Platforms 1 | Bottom | Shell Shard Ledge | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Faydown Cloak OR Sharpdart ) ) |  | Verified |  |
| P1 | Platforms 1 | Shell Shard Ledge | Bottom | None |  | Verified |  |
| P2 | Platforms 2 | Shell Shard Ledge | Arena | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Sharpdart ) ) OR Faydown Cloak |  | Verified |  |
| P2 | Platforms 2 | Arena | Shell Shard Ledge | None |  | Verified |  |
| P3 | Platforms 3 | Bottom | Arena | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Faydown Cloak OR Sharpdart ) ) |  | Verified |  |
| P3 | Platforms 3 | Arena | Bottom | None |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Cradle #1 | Shell Shard Ledge | None |  | Verified | Included |  |
| Boss: Grand Mother Silk | Arena | None |  | Verified | Included |  |
