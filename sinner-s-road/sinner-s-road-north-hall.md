# Sinner's Road North Hall (Dust_05)

**Game ID:** Dust_05

**Contributors:** herchey

## Subrooms

- behind left wall
- left area
- middle area
- right door platform
- hatch

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | behind left wall | [Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)](sinner-s-road-mist-maze-completed.md) | LR | none |  | Verified |  |
| C | center | hatch | [Sinner's Road Vertical Hall West (Dust_02)](sinner-s-road-vertical-hall-west.md) | C | none |  | Verified |  |
| R | right | right door platform | [Sinner's Road Vertical Hall East (Dust_06)](sinner-s-road-vertical-hall-east.md) | L | faydown cloak OR (enemy pogo AND drifter’s cloak) OR (clawline AND (ledge grab OR cling grip)) |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LWL | Behind left wall to left area | behind left wall | left area | complete North Hall Breakable wall |  | Verified |  |
| LWL | Behind left wall to left area | left area | behind left wall | complete North Hall Breakable wall AND (Silk soar OR faydown cloak OR cling grip OR scuttlebrace) |  | Verified |  |
| LAM | Left area to middle area | left area | middle area | clawline OR enemy pogo OR (sharpdart x 3 AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND ((cling grip AND ledge grab) OR faydown cloak)) OR (swim AND ledge grab) |  | Verified |  |
| LAM | Left area to middle area | middle area | left area | clawline OR enemy pogo OR (sharpdart AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND faydown cloak) OR (swim AND (ledge grab OR cling grip)) |  | Verified |  |
| MAH | Middle area to hatch | middle area | hatch | none |  | Verified | Technically "any attack" is the requirement |
| MAH | Middle area to hatch | hatch | middle area | Ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| MAR | Middle area to right door platform | middle area | right door platform | (swim AND faydown cloak) OR (clawline AND (drifter’s cloak OR sharpdart OR enemy pogo)) OR (drifter’s cloak AND (sharpdart OR enemy pogo)) OR (sharpdart AND enemy pogo) |  | Verified |  |
| MAR | Middle area to right door platform | right door platform | middle area | enemy pogo OR swim OR (drifter’s cloak AND (run OR dash OR ledge grab OR sharpdart OR clawline OR faydown cloak)) OR (run AND (faydown cloak OR sharpdart OR clawline)) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sinner’s Road #6 | left area | swim AND attack up |  | Verified | collectible |  |
| Shell Shard Cache: Sinner’s Road #7 | left area | swim AND attack up |  | Verified | collectible |  |
| North Hall Breakable wall | left area | none |  | Verified | blockade |  |
