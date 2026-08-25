# Cogwork Core Breakable Walls (Cog_10_Destroyed)

**Game ID:** Cog_10_Destroyed

**Contributors:** Rebel

## Subrooms

- Top Entrance
- Steam Shaft
- Center Shaft
- Northern Gauntlet
- Southern Shaft
- Breakable Wall Shaft
- Spike Platform
- Bottom Entrance

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom Entrance | [Memorium Entrance Tunnel (Song_25)](../choral-chambers/memorium-entrance-tunnel.md) | TL | Nothing. |  |  |  |
| L | left1 | Top Entrance | [Cogwork Core Architect's Melody (Act 3) (Cog_09_Destroyed)](cogwork-core-architect-s-melody-act-3.md) | R | Nothing. |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ESH | Top Entrance-Steam Shaft | Top Entrance | Steam Shaft | Break Wall #3 AND Dash OR Drifter's Cloak OR Faydown Cloak OR Sharp Dart OR Clawline OR Scuttlebrace OR Cling Grip |  | Verified |  |
| ESH | Top Entrance-Steam Shaft | Steam Shaft | Top Entrance | Break Wall #3 AND Silk Soar OR Faydown Cloak AND (Scuttlebrace OR (Ledge Grab AND Clawline) AND Cling Grip)) |  | Verified |  |
| SCS | Steam Shaft-Center Shaft | Steam Shaft | Center Shaft | Break Wall #4 |  | Verified |  |
| SCS | Steam Shaft-Center Shaft | Center Shaft | Steam Shaft | Break Wall #4 AND Silk Soar OR (Cling Grip OR Scuttlebrace) AND Faydown Cloak |  | Verified |  |
| SNG | Center Shaft-Northern Gauntlet | Center Shaft | Northern Gauntlet | Break Wall #5 |  | Verified |  |
| SNG | Center Shaft-Northern Gauntlet | Northern Gauntlet | Center Shaft | Break Wall #5 from other side AND Silk Soar AND Faydown Cloak |  | Verified |  |
| GSS | Northern Gauntlet-Southern Shaft | Northern Gauntlet | Southern Shaft | Complete Gauntlet |  | Verified |  |
| GSS | Northern Gauntlet-Southern Shaft | Southern Shaft | Northern Gauntlet | Complete Gauntlet AND Silk Soar OR Cling Grip AND Faydown Cloak |  | Verified |  |
| SWS | Southern Shaft-Wall Shaft | Southern Shaft | Breakable Wall Shaft | Break Wall #6 |  | Verified |  |
| SWS | Southern Shaft-Wall Shaft | Breakable Wall Shaft | Southern Shaft | Break Wall #6 AND (Cling Grip OR Faydown Cloak) |  | Verified |  |
| WSP | Breakable Wall Shaft-Spike Platform | Breakable Wall Shaft | Spike Platform | Break Wall #7 |  | Verified |  |
| WSP | Breakable Wall Shaft-Spike Platform | Spike Platform | Breakable Wall Shaft | Break Wall #7 AND Dash OR Faydown Cloak OR Drifter's Cloak OR Cling Grip OR Sharp Dart OR Clawline OR Scuttlebrace OR Ledge Grab |  | Verified |  |
| SPE | Spike Platform-Bottom Entrance | Spike Platform | Bottom Entrance | Nothing. (Fall) |  | Verified |  |
| SPE | Spike Platform-Bottom Entrance | Bottom Entrance | Spike Platform | Scuttlebrace AND (Spike Pogo OR Dash) OR Cling Grip OR Faydown Cloak AND (Spike Pogo OR Clawline) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Break Wall (Left OR Right) #3 | Steam Shaft | Nothing. |  | Verified | Included |  |
| Cogwork Core: Break Wall (Left OR Right) #4 | Steam Shaft | Nothing. |  | Verified | Included |  |
| Cogwork Core: Break Wall (Down) #5 | Center Shaft | Nothing. |  | Verified | Included | Can't be broken from the bottom. |
| Cogwork Core: Break Wall: (Left OR Right) #6 | Breakable Wall Shaft | Nothing. |  | Verified | Included |  |
| Cogwork Core: Break Wall: (Left OR Right) #7 | Breakable Wall Shaft | Nothing. |  | Verified | Included |  |
