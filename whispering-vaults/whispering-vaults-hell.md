# Whispering Vaults Hell (Library_04)

**Game ID:** Library_04

**Contributors:** Rebel

## Subrooms

- Ground
- Lowest Hallway
- Middle Hallway
- Upper Platform
- Map Room
- Top Hallway
- Upper Low Hallway
- Rosary Dish
- Left Side Shaft
- Lever
- Distant Platform
- Shortcut Box

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Map Room | [Songclave (Song_Enclave)](../choral-chambers/songclave.md) | B | Nothing. |  | Verified |  |
| HR | High Right | Distant Platform | [Whispering Vaults Silkeater (Library_14)](whispering-vaults-silkeater.md) | L | Nothing. |  | Verified |  |
| CR | Center Right | Middle Hallway | [Whispering Vaults East To West (Library_05)](whispering-vaults-east-to-west.md) | TL | Nothing. |  | Verified |  |
| BL | Bottom Left | Lowest Hallway | [Whispering Vaults Music Box (Library_16)](whispering-vaults-music-box.md) | R | Nothing. |  | Verified |  |
| CL | Center Left | Middle Hallway | [Trobbio Entrance (Library_13b)](trobbio-entrance.md) | R | Nothing. |  | Verified |  |
| LL | Low Left | Left Side Shaft | [Whispering Vaults Flea Shaft (Library_01)](whispering-vaults-flea-shaft.md) | BR | Nothing. |  | Verified |  |
| LR | Low Right | Upper Platform | [Whispering Vaults East To West (Library_05)](whispering-vaults-east-to-west.md) | BL | Nothing. |  | Verified |  |
| TR | Top Right | Top Hallway | [Whispering Vaults Jumps (Library_09)](whispering-vaults-jumps.md) | L | Nothing. |  | Verified |  |
| TL | Top Left | Top Hallway | [Whispering Vaults Flea Shaft (Library_01)](whispering-vaults-flea-shaft.md) | TR | Nothing. |  | Verified |  |
| BR | Bottom Right | Ground | [Vaultkeeper Cauldron Entrance (Library_10)](vaultkeeper-cauldron-entrance.md) | L | Nothing. |  | Verified |  |
| MHR | Mid High Right | Upper Platform | [Whispering Vaults Bench (Library_08)](whispering-vaults-bench.md) | L | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A1 | Ascent 1 | Ground | Lowest Hallway | Silk Soar OR Ledge Grab OR Clawline OR Faydown Cloak OR Cling Grip |  | Verified |  |
| BR | BL to LR | Lowest Hallway | Upper Low Hallway | Silk Soar OR Enemy Pogo/Ledge Grab/Clawline/Faydown Cloak/Sprint/Cling Grip/Scuttlebrace |  | Verified |  |
| CR | Collect Rosaries | Lever | Rosary Dish | Sprint/Dash/Clawline/Drifter's Cloak/Faydown Cloak/Cling Grip/Scuttlebrace/Sharp Dart/Beast Pogo/Beast Charge/Architect Pogo/Architect Charge |  | Verified |  |
| PR! | Progresion! | Left Side Shaft | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| MP! | More Progression! | Lever | Upper Platform | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak AND Ledge Grab/Clawline/Shaman Pogo |  | Verified |  |
| EMP | Even More Progression! | Upper Platform | Distant Platform | Silk Soar OR Cling Grip/Scuttlebrace AND Clawline/(Sprint/Dash/Drifter's Cloak AND Ledge Grab)/Faydown Cloak |  | Verified |  |
| LP! | Last Push! | Distant Platform | Top Hallway | Silk Soar OR Cling Grip OR Scuttlebrace AND |  | Verified |  |
| MT! | Map Time! | Top Hallway | Map Room | Silk Soar OR Cling Grip OR Scuttlebrace AND Enemy Pogo/Faydown Cloak |  | Verified |  |
| MT! | Map Time! | Map Room | Top Hallway | Nothing. (fall) |  | Verified |  |
| LP! | Last Push! | Top Hallway | Distant Platform | Nothing. Fall) |  | Verified |  |
| EMP | Even More Progression! | Distant Platform | Upper Platform | Nothing. (Fall) |  | Verified |  |
| MP! | More Progression! | Upper Platform | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified | accounting for the fact the player may not have activated the shortcut |
| PR! | Progresion! | Lever | Left Side Shaft | Nothing. (Fall) |  | Verified |  |
| BR | BL to LR | Upper Low Hallway | Lowest Hallway | Nothing. (Fall) |  | Verified |  |
| A1 | Ascent 1 | Lowest Hallway | Ground | Nothing. (Fall) |  | Verified |  |
| US | Unlock Shortcut | Middle Hallway | Shortcut Box | Ledge Grab OR Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline |  | Verified | Opens Shortcut |
| US2 | Use Shortcut | Shortcut Box | Middle Hallway | Opened Shortcut |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Flip Switch #7 (Left OR Right) | Distant Platform | Nothing. |  | Verified | Included |  |
| Whispering Vaults: Flip Switch #8 (Left OR Right) | Lever | Nothing. |  | Verified | Included |  |
| Whispering Vaults: Flip Switch #9 (Up) | Top Hallway | Nothing. |  | Verified | Included |  |
| Map: Whispering Vaults | Map Room | Nothing. |  | Verified | Included |  |
| Whispering Vaults: Break Wall #5 (Up) | Map Room | Nothing. |  | Verified | Included |  |
| Whispering Vaults: Rosary Dish #3 | Rosary Dish | Nothing. |  | Verified | Included |  |
