# Sinner's Road Vertical Hall West (Dust_02)

**Game ID:** Dust_02

**Contributors:** herchey

## Subrooms

- basement
- lower
- middle right
- middle left
- upper right
- top

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower | [Sinner's Road Entrance (Dust_01)](sinner-s-road-entrance.md) | R | none |  | Verified |  |
| ML | middle left | middle left | [Sinner's Road Bench (Dust_10)](sinner-s-road-bench.md) | R | none |  | Verified |  |
| C | ceiling | top | [Sinner's Road North Hall (Dust_05)](sinner-s-road-north-hall.md) | C | none |  | Verified |  |
| LR | lower right | lower | [Sinner's Road Muckroach Cages (Dust_03)](sinner-s-road-muckroach-cages.md) | L | none |  | Verified |  |
| MR | middle right | middle right | [Sinner's Road Hanging Cages (Dust_04)](sinner-s-road-hanging-cages.md) | LL | none |  | Verified |  |
| UR | upper right | upper right | [Sinner's Road Hanging Cages (Dust_04)](sinner-s-road-hanging-cages.md) | UL | prereq Upper Entry Switch IN Sinner's Road Hanging Cages |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | basement to lower | lower | basement | none |  | Verified | Technically "any attack" is a requirement |
| BL | basement to lower | basement | lower | cling grip |  | Verified |  |
| LMR | low to mid right | lower | middle right | Cling grip OR silk soar OR (scuttlebrace AND faydown cloak) |  | Verified |  |
| LMR | low to mid right | middle right | lower | none |  | Verified |  |
| MRL | mid right to mid left | middle right | middle left | silk soar |  | Verified |  |
| MRL | mid right to mid left | middle left | middle right | none |  | Verified |  |
| LUR | mid left to upper right | middle left | upper right | Cling grip OR faydown cloak |  | Verified |  |
| LUR | mid left to upper right | upper right | middle left | none |  | Verified |  |
| URT | upper right to top | upper right | top | Silk soar OR (cling grip AND (enemy pogo OR faydown cloak OR (proficient movement AND drifter's cloak) OR clawline OR sharpdart OR dash)) OR (faydown cloak AND ledge grab AND enemy pogo) |  | Verified |  |
| URT | upper right to top | top | upper right | none |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #1 | lower | swim AND (Ledge grab OR cling grip OR faydown cloak) |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #2 | upper right | none |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #3 | upper right | none |  | Verified | collectible |  |
