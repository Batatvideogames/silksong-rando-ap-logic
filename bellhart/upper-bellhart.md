# Upper Bellhart (Belltown_04)

**Game ID:** Belltown_04

**Contributors:** Pyxl

## Subrooms

- Lower Exits
- Lower Big Room
- Silver Bell Cubby
- Central Passage
- Upper Big room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left2 | Lower Exits | [Shellwood Hidden Bellhart Connection (Shellwood_15)](../shellwood/shellwood-hidden-bellhart-connection.md) | R | None |  | Verified |  |
| F | bot1 | Lower Exits | [Widow Boss Fight (Belltown_Shrine)](widow-boss-fight.md) | C | None |  | Verified |  |
| UL | left1 | Upper Big room | [Shellwood Upper Bellhart Entrance (Shellwood_13)](../shellwood/shellwood-upper-bellhart-entrance.md) | R | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Lower Exits | Lower Big Room | ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling Grip ) |  | Verified |  |
| TS1 | Tall Shaft1 | Lower Big Room | Lower Exits | ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling grip ) |  | Verified |  |
| TS2 | Tall Shaft2 | Lower Exits | Silver Bell Cubby | ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  | Verified |  |
| TS2 | Tall Shaft2 | Silver Bell Cubby | Lower Exits | None |  | Verified |  |
| TS3 | Tall Shaft3 | Lower Big Room | Silver Bell Cubby | Cling Grip OR Scuttlebrace |  | Verified |  |
| TS3 | Tall Shaft3 | Silver Bell Cubby | Lower Big Room | None |  | Verified |  |
| TS4 | Tall Shaft4 | Silver Bell Cubby | Central Passage | Cling Grip OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| TS4 | Tall Shaft4 | Central Passage | Silver Bell Cubby | None |  | Verified |  |
| US | Upper Shafts | Central Passage | Upper Big room | ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  | Verified |  |
| US | Upper Shafts | Upper Big room | Central Passage | None |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silver Bell Spawn Location #1 | Lower Big Room | None |  | Verified | collectible |  |
| Silver Bell Spawn Location #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | collectible |  |
| Rosary Cache: Bellhart #1 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | resource |  |
| Rosary Cache: Bellhart #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | resource |  |
| Silver Bell Spawn Location #3 | Silver Bell Cubby | None |  | Verified | collectible |  |
| Silver Bell Spawn Location #4 | Central Passage | None |  | Verified | collectible |  |
| Rosary Cache: Bellhart #3 | Central Passage | None |  | Verified | resource |  |
| Silver Bell Spawn Location #5 | Upper Big room | None |  | Verified | collectible |  |
| Flea: Bellhart | Upper Big room | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy enemy pogo AND ( Faydown Cloak OR Drifters Cloak ) ) |  | Verified | collectible |  |
