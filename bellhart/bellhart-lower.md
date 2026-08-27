# Bellhart Lower (Belltown_basement_03)

**Game ID:** Belltown_basement_03

**Contributors:** Pyxl

## Subrooms

- Top Exit
- Hermit
- Upper Hall
- Under Hermit Hall
- Rosary Room
- Passage below rosary
- Breakable Wall Passage
- Lower Passage 1
- Lower Passage 2
- Bottom Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | Top Exit | [Bellhart Bellway (Belltown_basement)](bellhart-bellway.md) | F | None |  | Verified |  |
| L | left1 | Bottom Exit | [The Marrow Jail Pathway (Bone_08)](../the-marrow/the-marrow-jail-pathway.md) | UR | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms Upper | Top Exit | Hermit | None |  | Verified |  |
| PL | Platforms Upper | Hermit | Top Exit | Clawline OR Ledge Grab OR Shamen Crest OR ( Dash AND Scuttlebrace ) OR Faydown Cloak OR Silk Soar OR  Cling Grip |  | Verified |  |
| UP | Upper Hall | Hermit | Upper Hall | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| UP | Upper Hall | Upper Hall | Hermit | None |  | Verified |  |
| TL | Tall Passage Left | Upper Hall | Under Hermit Hall | None |  | Verified |  |
| TL | Tall Passage Left | Under Hermit Hall | Upper Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| HH | Hermit Hole | Hermit | Under Hermit Hall | Hermit hole breakable wall broken from "under Hermit Hall" |  | Verified |  |
| HH | Hermit Hole | Under Hermit Hall | Hermit | Hermit hole breakable wall broken from "under Hermit Hall" AND ( Cling Grip OR Silk Soar OR Scuttlebrace ) |  | Verified |  |
| TR | Tall Passage Right | Under Hermit Hall | Rosary Room | None |  | Verified |  |
| TR | Tall Passage Right | Rosary Room | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| WS | Wide Shaft | Rosary Room | Passage below rosary | None |  | Verified |  |
| WS | Wide Shaft | Passage below rosary | Rosary Room | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| RS | Shaft near Rosary Cache | Passage below rosary | Breakable Wall Passage | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| RS | Shaft near Rosary Cache | Breakable Wall Passage | Passage below rosary | None |  | Verified |  |
| BW | Broken Floor Shaft | Breakable Wall Passage | Under Hermit Hall | Breakable Wall Passage Breakable Wall broken from "Breakable Wall Passage" AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| BW | Broken Floor Shaft | Under Hermit Hall | Breakable Wall Passage | Breakable Wall Passage Breakable Wall broken from "Breakable Wall Passage" |  | Verified |  |
| BL | Tall Passage Bottom Left | Breakable Wall Passage | Lower Passage 1 | None |  | Verified |  |
| BL | Tall Passage Bottom Left | Lower Passage 1 | Breakable Wall Passage | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| LV | Lower Passages Shaft | Lower Passage 1 | Lower Passage 2 | None |  | Verified |  |
| LV | Lower Passages Shaft | Lower Passage 2 | Lower Passage 1 | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| WP | Wide Platform Shaft | Lower Passage 2 | Passage below rosary | Lower Passage 2 Breakable Wall broken from "Lower Passage 2" AND ( Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace AND ( Ledge Grab OR Clawline OR Faydown Cloak OR Sharpdart OR Beast Crest ) ) ) |  | Verified |  |
| WP | Wide Platform Shaft | Passage below rosary | Lower Passage 2 | Lower Passage 2 Breakable Wall broken from "Lower Passage 2" AND ( Dash OR Sprint OR Ledge grab OR Clawline OR Drifters Cloak OR Faydown Cloak OR Cling grip OR Shamen Crest OR Architect Crest OR Beast Crest ) |  | Verified |  |
| ES | Exit Shaft | Lower Passage 2 | Bottom Exit | Lower Passage 2 Breakable  Wall To Exit broken from "Lower Passage 2" |  | Verified |  |
| ES | Exit Shaft | Bottom Exit | Lower Passage 2 | Lower Passage 2 Breakable  Wall To Exit broken from "Lower Passage 2" AND ( Cling Grip OR Silk Soar ( Dash AND Scuttlebrace AND Faydown Cloak ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hermits Soul | Hermit | Silk and Soul Wish Started |  | Verified | Not included |  |
| Silver Bell Spawn Location #6 | Upper Hall | Silver Bells Wish Started |  | Verified | Not included |  |
| Rosary Cache: Bellhart #6 | Upper Hall | None |  | Verified | Included |  |
| Silver Bell Spawn Location #7 | Upper Hall | Silver Bells Wish Started |  | Verified | Not included |  |
| Silver Bell Spawn Location #8 | Under Hermit Hall | Silver Bells Wish Started |  | Verified | Not included |  |
| Silver Bell Spawn Location #12 | Under Hermit Hall | Silver Bells Wish Started |  | Verified | Not included |  |
| Rosary Cache: Bellhart #7 | Rosary Room | None |  | Verified | Included |  |
| Silver Bell Spawn Location #9 | Passage below rosary | Silver Bells Wish Started |  | Verified | Not included |  |
| Silver Bell Spawn Location #10 | Lower Passage 1 | Silver Bells Wish Started |  | Verified | Not included |  |
| Silver Bell Spawn Location #11 | Lower Passage 2 | Silver Bells Wish Started |  | Verified | Not included |  |
| Rosary Cache: Bellhart #5 | Bottom Exit | None |  | Verified | Included |  |
| Hermit Hole Breakable Wall | Under Hermit Hall | None |  | Verified | Not included |  |
| Breakable Wall Passage Breakable Wall | Breakable Wall Passage | None |  | Verified | Not included |  |
| Lower Passage 2 Breakable Wall | Lower Passage 2 | None |  | Verified | Not included |  |
| Lower Passage 2 Breakable  Wall To Exit | Lower Passage 2 | None |  | Verified | Not included |  |
