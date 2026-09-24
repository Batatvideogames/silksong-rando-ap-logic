# Exhaust Organ Exterior (Dust_09)

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
| UD | up door | upper door plat | [Exhaust Organ Interior (Organ_01)](exhaust-organ-interior.md) | ML | none |  | Verified |  |
| LD | low door | middle platform | [Exhaust Organ Interior (Organ_01)](exhaust-organ-interior.md) | LL | none |  | Verified |  |
| L | left | left platform | [Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)](../sinner-s-road/sinner-s-road-mist-maze-completed.md) | UR | none |  | Verified |  |
| R | right | right platform | [Bilewater Organ Entrance (Shadow_04)](bilewater-organ-entrance.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LPM | left plat to middle | left platform | middle platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  | Verified |  |
| LPM | left plat to middle | middle platform | left platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  | Verified |  |
| RPM | right plat to middle | right platform | middle platform | swim |  | Verified |  |
| RPM | right plat to middle | middle platform | right platform | swim |  | Verified |  |
| MPU | mid plat to upper | middle platform | upper door plat | silk soar |  | Verified |  |
| MPU | mid plat to upper | upper door plat | middle platform | none |  | Verified | falling |
| LPF | left plat to flea | left platform | flea hall plat | silk soar |  | Verified |  |
| LPF | left plat to flea | flea hall plat | left platform | none |  | Verified | falling |
| UPF | upper plat to flea | upper door plat | flea hall plat | (cling grip OR ledge grab) OR scuttlebrace |  | Verified |  |
| UPF | upper plat to flea | flea hall plat | upper door plat | drifter's cloak OR faydown cloak OR run OR dash OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea Rescue | flea hall plat | (swim OR cling grip OR faydown cloak OR (silk soar AND (clawline OR ((drifter's cloak OR sharpdart) AND ledge grab)))) AND break vines left |  | Verified | collectible |  |
