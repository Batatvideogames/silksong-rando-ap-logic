# Greymoor Upper Halfway Home Path (Greymoor_12)

**Game ID:** Greymoor_12

## Subrooms

- left section
- right section
- upper platform section
- check platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left section | TODO |  | swim OR medium enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR flea brew OR faydown cloak OR drifter cloak OR easy crest pogo (hunter, reaper, beast, witch, architect) OR (medium crest pogo (shaman) AND ledge grab) |  | Verified |  |
| R | right | right section | [Greymoor West Bellshrine Room  (Greymoor_01)](greymoor-west-bellshrine-room.md) | TL | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | tall platform | left section | right section | swim OR faydown cloak OR medium scuttlebrace OR medium enemy pogo OR ((easy enemy pogo OR easy flea brew) AND (ledge grab OR cling grip) OR clawline OR progressive swift step 1 OR sharpdart OR easy crest pogo (beast) OR (easy crest pogo (hunter, reaper, witch, architect, shaman)) |  | Verified |  |
| TP | tall platform | right section | left section | swim OR faydown cloak OR medium scuttlebrace OR medium enemy pogo OR (easy enemy pogo AND (cling grip OR ledge grab)) OR (cling grip AND (progressive swift step 1 OR clawline OR sharpdart)) OR (silk soar AND (clawline OR progressive swift step 2 OR sharpdart)) |  | Verified |  |
| UP | upper platform | left section | upper platform section | silk soar OR easy enemy pogo OR progressive swift step 1 OR faydown cloak OR shaprdart OR clawline OR flea brew OR (drifter cloak and (cling grip OR ledge grab)) |  | Verified |  |
| UP | upper platform | upper platform section | left section | none (just fall) |  | Verified |  |
| G | gap | check platform | upper platform section | faydown cloak OR (cling grip AND (clawline OR progressive swift step 1)) |  | Verified |  |
| G | gap | upper platform section | check platform | faydown cloak OR drifter cloak OR progressive swift step 1 OR sharpdart OR clawline OR easy crest pogo (hunter, reaper, beast, witch, architect OR shaman) |  | Verified |  |
| PG | pogo skip | left section | check platform | faydown cloak OR silk soar OR hard enemy pogo AND ledge grab |  | Verified |  |
| PG | pogo skip | check platform | left section | none (fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #2 - Shard Bundle: | left section | none |  | Verified | Not included |  |

## Notes

need to recheck this logic due to possible chain or requirements being repeated
