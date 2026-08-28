# Exhaust Organ External (Dust_09)

**Game ID:** Dust_09

**Contributors:** Herchey and the Forgotten Contributor

## Subrooms

- middle platform
- left platform
- right platform
- upper door plat
- flea hall plat

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UD | up door | upper door plat | TODO |  | none | TODO |  |  |
| LD | low door | middle platform | TODO |  | none | TODO |  |  |
| L | left | left platform | [Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)](../sinner-s-road/sinner-s-road-mist-maze-completed.md) | UR | none |  |  |  |
| R | right | right platform | [Bilewater Organ Entrance (Shadow_04)](bilewater-organ-entrance.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LPM | left plat to middle | left platform | middle platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  |  |  |
| LPM | left plat to middle | middle platform | left platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  |  |  |
| RPM | right plat to middle | right platform | middle platform | swim |  |  |  |
| RPM | right plat to middle | middle platform | right platform | swim |  |  |  |
| MPU | mid plat to upper | middle platform | upper door plat | silk soar |  |  |  |
| MPU | mid plat to upper | upper door plat | middle platform | none |  |  | falling |
| LPF | left plat to flea | left platform | flea hall plat | silk soar |  |  |  |
| LPF | left plat to flea | flea hall plat | left platform | none |  |  | falling |
| UPF | upper plat to flea | upper door plat | flea hall plat | cling grip OR ledge grip OR scuttlebrace |  |  |  |
| UPF | upper plat to flea | flea hall plat | upper door plat | drifter's cloak OR faydown cloak OR run OR dash OR clawline OR sharpdart OR scuttlebrace |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea Rescue | flea hall plat | (swim OR cling grip OR faydown cloak OR (silk soar AND (clawline OR ((drifter's cloak OR sharpdart) AND ledge grab)))) AND left attack |  |  | Included |  |
