# Cogwork Core East Silk Spool & Gauntlet (Cog_07)

**Game ID:** Cog_07

**Contributors:** Rebel

## Subrooms

- Entrance
- Left Room
- Right Room
- Silk Spool Jump Left
- Silk Spool Jump Right
- Bottom Room
- Arena 

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | BR | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Entrance-Left | Entrance | Left Room | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LR | Left-Right | Left Room | Right Room | Flipped Switch |  | Verified |  |
| RB | Right-Bottom | Right Room | Bottom Room | Nothing. (Fall) |  | Verified |  |
| BLS | Bottom-Spool Left | Bottom Room | Silk Spool Jump Left | Nothing. (Fall) |  | Verified |  |
| SSJ | Silk Spool Jump | Silk Spool Jump Left | Silk Spool Jump Right | Dash OR Sprint OR Clawline OR Sharp Dart OR Scuttlebrace |  | Verified | hehe, funny dragonball reference. |
| SSJ | Silk Spool Jump | Silk Spool Jump Right | Silk Spool Jump Left | Dash OR Sprint OR Clawline OR Sharp Dart OR Scuttlebrace |  | Verified |  |
| BLS | Bottom-Spool Left | Silk Spool Jump Left | Bottom Room | Scuttlebrace OR Cling Grip |  | Verified |  |
| BE | Bottom-Entrance | Bottom Room | Entrance | Nothing. |  | Verified |  |
| BE | Bottom-Entrance | Entrance | Bottom Room | Can't. |  | Verified |  |
| EL | Entrance-Left | Left Room | Entrance | Nothing. (Fall) |  | Verified |  |
| LR | Left-Right | Right Room | Left Room | Flipped Switch |  | Verified |  |
| RB | Right-Bottom | Bottom Room | Right Room | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LG | Left-Gauntlet | Left Room | Arena | Silk Soar |  | Verified |  |
| LG | Left-Gauntlet | Arena | Left Room | Beat Arena. |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Silk Spool #1 | Silk Spool Jump Left | Nothing. |  | Verified | Included |  |
| Cogwork Core: Flip Switch (Up) #2 | Left Room | Nothing. |  | Verified | Included | interacting with this switch causes a mini-boss type enemy to spawn |
| Cogwork Core: Pristine Core | Arena | Beat Arena. |  | Verified | Included |  |
| Cogwork Core: Gauntlet #2 | Arena | Beat Arena. |  | Verified | Included |  |
