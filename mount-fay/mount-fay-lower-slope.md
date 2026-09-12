# Mount Fay Lower Slope (Peak_05)

**Game ID:** Peak_05

**Contributors:** Pyxl

## Subrooms

- Bottom
- Ceiling Area
- Right Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top2 | Ceiling Area | [Mount Fay Upper Slope (Peak_08)](mount-fay-upper-slope.md) | F | None |  | Verified |  |
| F | bot1 | Bottom | [Mount Fay Bench Toll (Bellway_Peak)](mount-fay-bench-toll.md) | C | None |  | Verified |  |
| R | right3 | Right Exit | [Mount Fay Frozen Flea (Peak_05c)](mount-fay-frozen-flea.md) | L | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Ceiling Area | Right Exit | Complete Mount Fay Slope Lever |  | Verified |  |
| SH | Shaft | Right Exit | Ceiling Area | Complete Mount Fay Slope Lever AND ( ( Faydown Cloak AND Drifters Cloak AND Cling Grip AND Sharpdart ) OR Silk Soar OR ( Clawline AND Faydown Cloak AND Cling Grip ) ) |  | Verified |  |
| BS | Big Slope | Right Exit | Bottom | None |  | Verified |  |
| BS | Big Slope | Bottom | Right Exit | Faydown Cloak OR ( Cling Grip AND Clawline ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay Slope Lever | Ceiling Area | None |  | Verified | switch |  |
