# Shellwood Right Side Big room (Shellwood_01)

**Game ID:** Shellwood_01

**Contributors:** Pyxl

## Subrooms

- Ground Level Left
- Central Platforms
- Right Platforms
- Ground Level Right

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Right Platforms | [Long Pin (Belltown_Room_shellwood)](long-pin.md) | L | Prereq Longpin Nest |  | Verified |  |
| UL | left1 | Central Platforms | [Shellwood Sister Splinter Bench (Shellwood_01b)](shellwood-sister-splinter-bench.md) | LR | None |  | Verified |  |
| LR | right2 | Ground Level Right | [Bellhart Hallway to Shellwood (Belltown_07)](../bellhart/bellhart-hallway-to-shellwood.md) | L | None |  | Verified |  |
| LL | left2 | Ground Level Left | [Shellwood Big Room Left (Shellwood_02)](shellwood-big-room-left.md) | LR | Prereq Big Door Button IN Shellwood Big Room Left |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lake | Ground Level Left | Ground Level Right | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| LA | Lake | Ground Level Right | Ground Level Left | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| C1 | Chasm 1 | Ground Level Left | Central Platforms | ( Ledge Grab AND ( Dash OR Drifters Cloak OR Easy Beast Crest pogo ) ) OR Clawline OR Cling Grip OR Silk Soar OR Sharpdart OR Faydown Cloak |  | Verified |  |
| C1 | Chasm 1 | Central Platforms | Ground Level Left | None |  | Verified |  |
| C2 | Chasm 2 | Central Platforms | Right Platforms | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling grip OR Dash OR Scuttlebrace OR Clawline  OR Sprint |  | Verified |  |
| C2 | Chasm 2 | Right Platforms | Central Platforms | None |  | Verified |  |
| C3 | Chasm 3 | Right Platforms | Ground Level Right | None |  | Verified |  |
| C3 | Chasm 3 | Ground Level Right | Right Platforms | Silk Soar OR ( Cling Grip AND Faydown Cloak  AND ( Swim OR ( Easy Enemy Pogo AND ( Sprint OR Dash ) ) OR Drifters Cloak OR Clawline OR Sharpdart ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shellwood - Frayed Rosary String | Central Platforms | None |  | Verified | collectible |  |
| Pollip Heart #1 | Right Platforms | Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified | collectible |  |
| Shell shard Cache: Shellwood #4 | Right Platforms | None |  | Verified | resource |  |
| Shell shard Cache: Shellwood #5 | Right Platforms | None |  | Verified | resource |  |
| Shell shard Cache: Shellwood #6 | Right Platforms | None |  | Verified | resource |  |
| Longpin Nest | Right Platforms | None |  | Verified | blockade |  |
