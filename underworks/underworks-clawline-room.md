# Underworks Clawline Room (Under_18)

**Game ID:** Under_18

**Contributors:** Rebel

## Subrooms

- Clawline Statue
- Blocked Off Corridor Left
- Shard Bundle Check
- Main Side Door
- Arena
- Blocked Off Corridor Top

- **Arena:** Arena activated by Clawline Ring

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | Top Right | Arena | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BR | (Complete Underworks: Gauntlet #3 AND (Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown Cloak) AND (Easy Shaman Crest Pogo OR Easy Needle Strike Stall (Beast))) |  | Verified |  |
| L | Left | Blocked Off Corridor Left | [Underworks East Shaft (Under_13)](underworks-east-shaft.md) | MR | Nothing. |  | Verified |  |
| R | Right | Main Side Door | [Underworks Clawline Entrance (Under_19c)](underworks-clawline-entrance.md) | TL | Invalid |  | Verified |  |
| TL | Top Left | Blocked Off Corridor Top | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BL | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AP | Arena Path | Main Side Door | Arena | Clawline OR (Faydown Cloak AND (Sharpdart OR Swift Step 2) AND Ledge Grab AND Enemy Pogo) |  | Verified | getting up here without clawline is worthless unless cause the exit needs clawline anyway lmao |
| CP | Clawline Path | Main Side Door | Clawline Statue | Clawline OR (Faydown Cloak AND Sprint AND Drifter's Cloak) OR (Dash AND Enemy Pogo AND Ledge Grab) |  | Verified |  |
| SP | Shard Path | Main Side Door | Shard Bundle Check | Clawline OR (Faydown Cloak AND (Sharpdart OR Swift Step 2) AND Ledge Grab AND Enemy Pogo) |  | Verified | same thing as the arena path but you go left at the end instead of right |
| LST | Left Side Travel | Blocked Off Corridor Left | Blocked Off Corridor Top | Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND Ledge Grab) |  | Verified |  |
| AP | Arena Path | Arena | Main Side Door | Clawline OR Sharpdart OR Dash OR Sprint OR Scuttlebrace OR Drifter's Cloak OR (Faydown Cloak AND Ledge Grab) |  | Verified |  |
| CP | Clawline Path | Clawline Statue | Main Side Door | Clawline OR (Sharpdart AND Faydown Cloak AND (Swift Step 2 OR Drifter's Cloak)) |  | Verified |  |
| SP | Shard Path | Shard Bundle Check | Main Side Door | Clawline OR ((Drifter's Cloak OR Swift Step 2) AND (Enemy Pogo OR (Faydown Cloak AND Sharpdart))) |  | Verified |  |
| LST | Left Side Travel | Blocked Off Corridor Top | Blocked Off Corridor Left | Nothing. (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Clawline Pickup | Clawline Statue | Nothing. |  | Verified | collectible |  |
| Underworks: Shard Bundle #2 | Shard Bundle Check | Nothing. |  | Verified | collectible |  |
| Clawline Ring | Arena | Clawline |  | Verified | switch |  |
| Underworks: Gauntlet #3 | Arena | Activate Clawline Ring |  | Verified | gauntlet |  |
