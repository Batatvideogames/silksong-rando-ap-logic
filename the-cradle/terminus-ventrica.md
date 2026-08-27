# Terminus Ventrica (Tube_Hub)

**Game ID:** Tube_Hub

**Contributors:** Pyxl

## Subrooms

- Ventricas
- Silkeater Room
- Lower Shaft
- Central Shaft
- Upper Shaft

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left1 | Lower Shaft | [Lace 2 Fight (Song_Tower_01)](lace-2-fight.md) | R | ACT 2 |  | Verified |  |
| ML | left4 | Central Shaft | [Act2 Cradle Connector Hallway (Cradle_01)](act2-cradle-connector-hallway.md) | R | ACT 2 |  | Verified |  |
| UL | left3 | Upper Shaft | [ACT2 GMS Arena (Cradle_03)](act2-gms-arena.md) | R | ACT 2 |  | Verified |  |
| V | door_tubeEnter | Ventricas | [Ventrica Menu](../fast-travel/ventrica-menu.md) | T | Terminus Ventrica Owned |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SES | Silk Eater Shaft | Silkeater Room | Ventricas | Break Breakable Floor AND ( Cling Grip OR Scuttlebrace ) |  | Verified | Potentially possible with silk soar if you come during act 3 |
| SES | Silk Eater Shaft | Ventricas | Silkeater Room | Break Breakable Floor |  | Verified |  |
| TS1 | Tall Shaft1 | Ventricas | Lower Shaft | One way wall opened from Lower Shaft |  | Verified |  |
| TS1 | Tall Shaft1 | Lower Shaft | Ventricas | One way wall opened from Lower Shaft AND ( Scuttlebrace OR Cling Grip OR Silk Soar ) |  | Verified |  |
| TS2 | Tall Shaft2 | Lower Shaft | Central Shaft | Scuttlebrace OR Cling Grip OR Silk Soar |  | Verified |  |
| TS2 | Tall Shaft2 | Central Shaft | Lower Shaft | None |  | Verified |  |
| TS3 | Tall Shaft3 | Central Shaft | Upper Shaft | One way door opened from Upper Shaft AND ( Scuttlebrace OR Cling Grip OR Silk Soar ) |  | Verified |  |
| TS3 | Tall Shaft3 | Upper Shaft | Central Shaft | One way door opened from Upper Shaft |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeate: Terminus | Silkeater Room | None |  | Verified | Included |  |

## Notes

I entered this during act 3 and got the same scene dump, dont believe they count as differant rooms also cannot find the area on the map
