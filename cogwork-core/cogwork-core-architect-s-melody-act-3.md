# Cogwork Core Architect's Melody (Act 3) (Cog_09_Destroyed)

**Game ID:** Cog_09_Destroyed

**Contributors:** Rebel

## Subrooms

- Bottom
- Center
- Silk Soar Ceiling
- Top Entrance

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Bottom | [Cogwork Core Breakable Walls (Cog_10_Destroyed)](cogwork-core-breakable-walls.md) | L | Nothing. |  | Verified |  |
| T | top1 | Top Entrance | [ACT3 Lace2 Arena (Song_Tower_Destroyed)](../the-cradle/act3-lace2-arena.md) | F | Nothing. | TODO | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BC | Bottom-Center | Bottom | Center | Silk Soar OR (Faydown Cloak AND Cling Grip) |  | Verified |  |
| BC | Bottom-Center | Center | Bottom | Nothing. (Fall) |  | Verified |  |
| CSE | Center-Silk Soar Entrance | Center | Silk Soar Ceiling | Silk Soar |  | Verified |  |
| CSE | Center-Silk Soar Entrance | Silk Soar Ceiling | Center | Nothing. (Fall) |  | Verified |  |
| STE | Soar Ceiling-Top Entrance | Silk Soar Ceiling | Top Entrance | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| STE | Soar Ceiling-Top Entrance | Top Entrance | Silk Soar Ceiling | Nothing. (Fall) |  | Verified |  |

## Check Locations

No check locations defined.
