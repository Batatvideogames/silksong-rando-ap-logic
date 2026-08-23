# Underworks East Shaft (Under_13)

**Game ID:** Under_13

## Subrooms

- Lower Central Shaft
- Bottom Left Entrance
- Bottom Right Entrance
- Bottom
- Lower Left Entrance
- High Left Entrance
- Top Left Entrance
- Mid Right Entrance
- Top Right Entrance
- Upper Central Shaft

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Left Entrance | [Underworks Flea Room (Under_21)](underworks-flea-room.md) | R | Nothing. |  | Verified |  |
| BR | Bottom Right | Bottom Right Entrance | [Underworks Lava Flow Corridor (Under_19)](underworks-lava-flow-corridor.md) | L | Nothing. |  | Verified |  |
| TL | Top Left | Top Left Entrance | [Underworks Lever Spike Corridor (Under_11)](underworks-lever-spike-corridor.md) | R | Nothing. |  | Verified |  |
| TR | Top Right | Top Right Entrance | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | FL | Nothing. |  | Verified |  |
| HL | High Left | High Left Entrance | [Underworks Ventrica (Under_22)](underworks-ventrica.md) | R | Nothing. |  | Verified |  |
| MR | Mid Right | Mid Right Entrance | [Underworks Clawline Room (Under_18)](underworks-clawline-room.md) | L | Nothing. |  | Verified |  |
| LL | Low Left | Lower Left Entrance | [Underworks Eastern Gauntlet (Under_10)](underworks-eastern-gauntlet.md) | R | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left-Bottom Right | Bottom Left Entrance | Bottom Right Entrance | Ledge Grab OR Clawline OR Faydown Cloak |  | Verified |  |
| BLR | Bottom Left-Bottom Right | Bottom Right Entrance | Bottom Left Entrance | Ledge Grab AND (Sprint OR Dash OR Drifter's Cloak) OR Clawline OR Cling Grip OR Faydown Cloak |  | Verified |  |
| BC | Bottom-Lower Central | Bottom | Lower Central Shaft | Silk Soar OR (Faydown Cloak OR Clawline) AND Enemy Pogo OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LHL | Lower Left-High Left | Lower Left Entrance | High Left Entrance | Cling Grip Or Scuttlebrace |  | Verified |  |
| LHL | Lower Left-High Left | High Left Entrance | Lower Left Entrance | Nothing. (Fall) |  | Verified |  |
| HLT | High Left-Top Left | High Left Entrance | Top Left Entrance | Silk Soar OR Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |
| HLT | High Left-Top Left | Top Left Entrance | High Left Entrance | Nothing. (Fall) |  | Verified |  |
| HLR | High Left-Mid Right | High Left Entrance | Mid Right Entrance | Activate shortcut from other side, flip lever. |  | Verified |  |
| HLR | High Left-Mid Right | Mid Right Entrance | High Left Entrance | Flip bridge lever AND Silk Soar OR Cling Grip OR Faydown Cloak OR Scuttlebrace AND (Drifter's Cloak OR (Dash AND Ledge Grab)) |  | Verified |  |
| LUC | Lower Central-Upper Central | Lower Central Shaft | Upper Central Shaft | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LUC | Lower Central-Upper Central | Upper Central Shaft | Lower Central Shaft | Nothing. (Fall) |  | Verified |  |
| BC | Bottom-Lower Central | Lower Central Shaft | Bottom | Nothing. (Fall) |  | Verified |  |
| CTP | Upper Central-Top Left | Upper Central Shaft | Top Right Entrance | Clawline OR Ledge Grab OR Scuttlebrace OR Faydown Cloak OR Cling Grip OR Silk Soar |  | Verified |  |
| CTP | Upper Central-Top Left | Top Right Entrance | Upper Central Shaft | Nothing. (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flip Switch (Left OR Right) #3 | Mid Right Entrance | Nothing. |  | Verified | Included | is this even a check? |
