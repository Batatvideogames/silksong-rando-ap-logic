# Bilewater Lower Bloatroach Tower (Shadow_02)

**Game ID:** Shadow_02

**Contributors:** Herchey and Wesker (his cat)

## Subrooms

- low left
- low right
- mid right
- halfway up
- rosary plat
- up left

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | low right | [Bilewater Lower East Hall (Shadow_03)](bilewater-lower-east-hall.md) | L | none |  | Verified |  |
| UR | upper right | halfway up | [Bilewater Upper East Column (Shadow_26)](bilewater-upper-east-column.md) | LL | (clawline OR enemy pogo) AND (faydown cloak OR drifter's cloak) |  | Verified |  |
| LL | lower left | low left | [Bilewater West Hall (Shadow_04b)](bilewater-west-hall.md) | R | none |  | Verified |  |
| MR | middle right | mid right | [Bilewater Shakra Room (Shadow_23)](bilewater-shakra-room.md) | L | none |  | Verified |  |
| UL | upper left | up left | [Bilewater Upper West Column (Shadow_14)](bilewater-upper-west-column.md) | LR | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LOW | low left and right | low left | low right | swim OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy beast pogo |  | Verified |  |
| LOW | low left and right | low right | low left | swim OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy beast pogo |  | Verified |  |
| LLM | low left to mid | low left | mid right | ((faydown cloak AND cling grip) OR silk soar) AND (clawline OR sharpdart OR drifter's cloak OR faydown cloak) |  | Verified |  |
| LLM | low left to mid | mid right | low left | silk soar OR clawline OR sharpdart OR drifter's cloak OR faydown cloak OR dash |  | Verified |  |
| LRM | low right to mid | low right | mid right | silk soar AND faydown cloak AND cling grip |  | Verified | Pretty goddamn precise from the silk soar to faydown. Maybe easy_skip though. Very easy to try again without penalty. |
| LRM | low right to mid | mid right | low right | none |  | Verified | falling |
| MUR | mid to halfway | mid right | halfway up | cling grip AND (clawline OR faydown cloak OR (drifter's cloak AND enemy pogo)) |  | Verified |  |
| MUR | mid to halfway | halfway up | mid right | none |  | Verified | falling |
| UPR | halfway to rosary | halfway up | rosary plat | faydown cloak AND (clawline OR enemy pogo) |  | Verified |  |
| UPR | halfway to rosary | rosary plat | halfway up | none |  | Verified | falling |
| HUL | halfway to upper left | halfway up | up left | faydown cloak AND cling grip AND (clawline OR enemy pogo) |  | Verified |  |
| HUL | halfway to upper left | up left | halfway up | none |  | Verified | falling |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Frayed Rosary String | rosary plat | none |  | Verified | collectible |  |
