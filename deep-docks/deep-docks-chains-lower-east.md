# Deep Docks Chains Lower East (Dock_03c)

**Game ID:** Dock_03c

**Contributors:** herounit and Rebel

## Subrooms

- upper chains
- spool fragment area
- lower chains
- middle chains
- upper lava platform
- lower lava platform
- gauntlet
- upper left of gauntlet

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RC | top2 | upper chains | [Deep Docks Chains Upper East (Dock_03)](deep-docks-chains-upper-east.md) | F | nothing. |  | Verified |  |
| LC | top1 | upper left of gauntlet | [Deep Docks Chains Flea Rescue (Dock_03d)](deep-docks-chains-flea-rescue.md) | F | open airlock Up |  | Verified |  |
| L | left2 | lower lava platform | [Deep Docks Chains Center (Dock_02b)](deep-docks-chains-center.md) | LR | Activate Shortcut Blast Rock |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | open spool door | spool fragment area | upper chains | open airlock left |  | Verified | one-way |
| SP | open spool door | upper chains | spool fragment area | Invalid |  | Verified |  |
| C1 | upper to middle chains | middle chains | upper chains | faydown cloak OR cling grip OR Scuttlebrace OR silk soar OR Ledge Grab |  | Verified |  |
| C1 | upper to middle chains | upper chains | middle chains | none (falling) |  | Verified |  |
| C2 | lower to middle chains | lower chains | middle chains | silk soar OR cling grip OR Scuttlebrace OR (faydown cloak AND Ledge Grab) |  | Verified |  |
| C2 | lower to middle chains | middle chains | lower chains | none (falling) |  | Verified |  |
| UC | upper clawline area | lower chains | upper lava platform | clawline |  | Verified |  |
| UC | upper clawline area | upper lava platform | lower chains | clawline OR Sharpdart OR drifter's cloak OR (Medium Flintslate Stall AND Medium Hunter Pogo) OR Medium Voltvessels Stall OR Medium Beast Pogo OR Medium Architect Pogo OR (Flea Brew AND (Easy Architect Charge OR Easy Beast Charge OR Easy Hunter Pogo)) OR (Medium Flea Brew Stall AND Flea Brew) |  | Verified |  |
| LG | cross lava gap | lower chains | lower lava platform | (clawline OR ( drifter's cloak AND (faydown cloak OR Medium Beast Charge OR Hard Architect Charge OR (Dash AND Easy Beast Pogo) ) ) OR (Sharpdart x 2 AND (Drifter's CLoak OR Easy Flea Brew Stall OR Easy Voltvessels Stall)) OR (Sharpdart x 3 AND Medium Flintslate Stall)) |  | Verified | seems just out of reach of drifter's cloak and dash |
| LG | cross lava gap | lower lava platform | lower chains | clawline OR ( drifter's cloak AND faydown cloak ) |  | Verified |  |
| UL | upper lava platform to lower lava platform | upper lava platform | lower lava platform | none (falling) |  | Verified |  |
| UL | upper lava platform to lower lava platform | lower lava platform | upper lava platform | Clawline OR Silk Soar |  | Verified |  |
| TGL | To Gauntlet Lower | lower lava platform | gauntlet | Silk Soar |  | Verified |  |
| TGL | To Gauntlet Lower | gauntlet | lower lava platform | Nothing. (Fall) |  | Verified |  |
| TGH | To Gauntlet Higher | upper lava platform | gauntlet | (Clawline AND (Cling Grip OR Scuttlebrace)) OR (((Sharpdart x 2 AND Cling Grip AND (Faydown Cloak OR Medium Flea Brew Stall)) AND (Spike Pogo OR Ledge Grab))) |  | Verified |  |
| TGH | To Gauntlet Higher | gauntlet | upper lava platform | Invalid |  | Verified |  |
| CG | Chain Gauntlet | gauntlet | middle chains | clear chains gauntlet |  | Verified |  |
| CG | Chain Gauntlet | middle chains | gauntlet | clear chains gauntlet |  | Verified |  |
| TF | To Flea | gauntlet | upper left of gauntlet | clear chains gauntlet AND (Silk Soar OR Cling Grip OR Faydown Cloak OR Scuttlebrace) |  | Verified |  |
| TF | To Flea | upper left of gauntlet | gauntlet | Nothing (Fall) |  | Verified |  |
| SC | spool crossing | lower chains | spool fragment area | cling grip  AND ( clawline OR ( dash AND ( run OR sharpdart OR drifter's cloak ) ) ) AND break blast rock up AND break blast rock down |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Deep Docks (Southeast) - Spool Fragment | spool fragment area | none |  | Verified | collectible |  |
| Shortcut Blast Rock | lower lava platform | nada |  | Verified | blockade |  |
| Chains Gauntlet | gauntlet | nothing. |  | Verified | gauntlet |  |
| Spool Door Switch | spool fragment area | Flip Switch Left |  | Verified | switch |  |
