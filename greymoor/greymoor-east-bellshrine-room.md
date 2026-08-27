# Greymoor East Bellshrine Room (Greymoor_02)

**Game ID:** Greymoor_02

## Subrooms

- lower section left
- lower section right
- middle section right
- middle section left
- bridge left section
- bridge right section
- upper crow nest

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LSL | lower left | lower section left | [Greymoor West Bellshrine Room  (Greymoor_01)](greymoor-west-bellshrine-room.md) | LR | none |  | Verified |  |
| LR | lower right | lower section left | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | LL | none |  | Verified |  |
| ML | middle left | middle section left | [Greymoor Bellshrine (Bellshrine_02)](greymoor-bellshrine.md) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | UL | none |  | Verified |  |
| BL | bridge left | bridge left section | [Greymoor West Bellshrine Room  (Greymoor_01)](greymoor-west-bellshrine-room.md) | TR | none |  | Verified |  |
| HR | hidden right | upper crow nest | [Greymoor Silver Shells room (Greymoor_17)](greymoor-silver-shells-room.md) | L | (Wall broken FROM greymoor east bellshrine room (upper crow nest) (RIGHT)) AND (silk soar OR faydown cloak OR (cling grip AND (easy spike pogo OR progressive swift step 1 OR clawline OR sharpdart OR drifter cloak)) OR hard enemy pogo OR (medium enemy pogo AND ledge grab AND (progressive swift step 1 OR clawline))) |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | tall platform | lower section right | lower section left | ledge grab OR faydown cloak OR silk soar OR cling grip |  | Verified |  |
| TP | tall platform | lower section left | lower section right | none (just fall) |  | Verified |  |
| F1 | fall 1 | middle section left | lower section left | none (just fall) |  | Verified |  |
| LS1 | lever switch 1 | lower section right | middle section right | silk soar OR (LEVER broken FROM greymoor east bellshrine room (middle section) (RIGHT OR LEFT OR DOWN OR UP) AND  easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| LS1 | lever switch 1 | middle section right | lower section right | none (just fall) |  | Verified |  |
| G1 | gap 1 | middle section right | middle section left | (LEVER broken FROM greymoor east bellshrine room (middle section) (RIGHT OR LEFT OR DOWN OR UP) AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) OR progressive swift step 1 OR clawline OR sharpdart OR drifter cloak OR faydown cloak |  | Verified |  |
| G1 | gap 1 | middle section left | middle section right | Progressive swift step 2 OR clawline OR sharpdart OR drifter cloak OR silkspeed anklets  OR (progressive swift step 1 AND (faydown cloak OR ledge grab)) OR (LEVER broken FROM greymoor east bellshrine room (middle section) (RIGHT OR LEFT OR DOWN OR UP) AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| BG | bridge gap | bridge left section | bridge right section | NOT (LEVER broken FROM greymoor east bellshrine room (bridge right section)) OR (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND ((easy flea brew AND ledge grab) OR (speed anklets used AND cling grip)))) AND (drifter cloak OR faydown cloak))) |  | Verified |  |
| BG | bridge gap | bridge right section | bridge left section | NOT (LEVER broken FROM greymoor east bellshrine room (bridge right section)) OR (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND ((easy flea brew AND ledge grab) OR (silkspeed anklets used AND cling grip)))) AND (drifter cloak OR faydown cloak))) |  | Verified |  |
| CR | climb right | middle section right | bridge right section | (LEVER broken FROM greymoor east bellshrine room (bridge right section) (RIGHT OR LEFT OR DOWN OR UP) AND (cling grip OR silk soar)) |  | Verified |  |
| CR | climb right | bridge right section | middle section right | LEVER broken FROM greymoor east bellshrine room (bridge right section) (RIGHT OR LEFT OR DOWN OR UP) |  | Verified |  |
| CL | climb left | middle section left | bridge left section | (LEVER broken FROM greymoor east bellshrine room (bridge right section) (RIGHT OR LEFT OR DOWN OR UP)) AND silk soar OR (cling grip AND faydown cloak) |  | Verified |  |
| CL | climb left | bridge left section | middle section left | LEVER broken FROM greymoor east bellshrine room (bridge right section) (RIGHT OR LEFT OR DOWN OR UP) |  | Verified |  |
| UL | upper left | bridge left section | upper crow nest | silk soar |  | Verified |  |
| UL | upper left | upper crow nest | bridge left section | none (fall) |  | Verified |  |
| UR | upper right | bridge right section | upper crow nest | silk soar OR easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman) |  | Verified |  |
| UR | upper right | upper crow nest | bridge right section | none (fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Spool Fragment | upper crow nest | silk soar OR faydown cloak OR (cling grip AND (easy spike pogo OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR drifter cloak) OR (hard enemy pogo)) |  | Verified | Included |  |
| Greymoor #2 - Rosary Cache | upper crow nest | silk soar OR faydown cloak OR hard enemy pogo OR (easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman) AND (clawline OR sharpdart OR progressive swift step 2 OR drifter cloak)) |  | Verified | Not included |  |
| Greymoor #3 - Rosary Cache | upper crow nest | silk soar OR faydown cloak OR hard enemy pogo OR (easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman) AND (clawline OR sharpdart OR progressive swift step 2 OR drifter cloak)) |  | Verified | Not included |  |
| Greeymoor - map purchase | lower section right | none |  | Verified | Included |  |
