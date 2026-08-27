# Greymoor Craw Lake (Greymoor_15b)

**Game ID:** Greymoor_15b

## Subrooms

- craw building
- lower left section
- middle craw nest
- upper craw nest
- spiked room
- flea room
- middle craw nest left
- small ass platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top | upper craw nest | [Greymoor Weaver Shrine (Greymoor_22)](greymoor-weaver-shrine.md) | B | silk soar OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman) AND (ledge grab OR faydown cloak OR cling grip)) |  | Verified |  |
| ML | middle left | middle craw nest left | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | UR | none |  | Verified |  |
| LR | lower right | craw building | TODO |  | ACT 3 AND green prince quest AND (((cling grip OR silk soar) AND (clawline OR (progressive swift step 1 AND (drifter cloak OR (sharpdart AND faydown cloak))) OR (progressive swift step 2 AND faydown cloak))) OR (LEVER broken FROM greymoor crow nest (crow arena) UP  AND (easy crest pogo (beast, architect, shaman) OR (easy crest pogo (reaper, wanderer, witch) AND ledge grab) OR (easy crest pogo (hunter, reaper, wanderer, witch) AND (faydown cloak OR drifter cloak OR clawline OR sharpdart OR progressive swift step 2))))) |  | Verified |  |
| CN | craw nest entrance | craw building | [Greymoor Crow Nest (Room_CrowCourt)](greymoor-crow-nest.md) | L | swim OR ledge grab OR cling grip OR hard enemy pogo |  | Verified |  |
| LL | lower left | lower left section | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | LR | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | lake gap | lower left section | craw building | swim OR clawline OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifter cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND drifter cloak) OR (silk soar AND drifter cloak AND (faydown cloak OR sharpdart OR progressive swift step 2)) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| LG | lake gap | craw building | lower left section | swim OR clawline OR silk soar OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifter cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND (drifter cloak OR ((ledge grab OR cling grip) AND faydown cloak))) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| FL | fall left | upper craw nest | flea room | progressive swift step 2 OR clawline OR sharpdart OR drifter cloak OR faydown cloak |  | Verified |  |
| FL | fall left | flea room | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| FR | fall right | upper craw nest | middle craw nest left | progressive swift step 2 OR clawline OR sharpdart OR drifter cloak OR (faydown cloak AND ledge grab) |  | Verified |  |
| FR | fall right | middle craw nest left | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| G1 | gap 1 | craw building | lower left section | (drifter cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND shaprdart AND faydown cloak))) OR medium crest pogo (hunter, reaper beast, witch, architect, shaman) |  | Verified |  |
| G1 | gap 1 | lower left section | craw building | (drifter cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND shaprdart AND faydown cloak))) OR easy crest pogo (hunter, reaper beast, witch, architect, shaman) |  | Verified |  |
| G2 | gap 2 | middle craw nest left | middle craw nest | none (normal jump) |  | Verified |  |
| G2 | gap 2 | middle craw nest | middle craw nest left | (progressive swift step 1 AND faydown cloak AND ledge grab) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND medium crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| G3 | gap 3 | middle craw nest | flea room | (drifter cloak OR clawline OR (progressive swift step 2 AND (ledge grab OR cling grip OR sharpdart OR faydown cloak)) OR (progressive swift step 1 AND (faydown cloak AND (ledge grab OR cling grip) OR sharpdart))) OR (LEVER broken FROM greymoor crow nest AND medium crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| G3 | gap 3 | flea room | middle craw nest | (drifter cloak OR clawline OR (progressive swift step 2 AND (ledge grab OR cling grip OR sharpdart OR faydown cloak)) OR (progressive swift step 1 AND (faydown cloak AND (ledge grab OR cling grip) OR sharpdart))) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| D1 | drop 1 | craw building | flea room | silk soar |  | Verified |  |
| D1 | drop 1 | flea room | craw building | none (just fall) |  | Verified |  |
| D2 | drop 2 | upper craw nest | middle craw nest | none (just fall) |  | Verified |  |
| D2 | drop 2 | middle craw nest | upper craw nest | silk soar OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| D3 | drop 3 | middle craw nest | craw building | none (just fall) |  | Verified |  |
| D3 | drop 3 | craw building | middle craw nest | silk soar OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| D4 | drop 4 | small ass platform | middle craw nest | (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| D4 | drop 4 | middle craw nest | small ass platform | clawline OR sharpdart OR progressive swift step 2 OR faydown cloak OR drifter cloak (progressive swift step 1 AND (ledge grab OR easy flea brew OR silkspeed anklets))) |  | Verified |  |
| H | hatch | craw building | flea room | LEVER broken FROM greymoor craw lake (flea room) (LEFT OR RIGHT OR UP) |  | Verified | It remains open for some time and closes again |
| H | hatch | flea room | craw building | LEVER broken FROM greymoor craw lake (flea room) (LEFT OR RIGHT OR UP) |  | Verified | It remains open for some time and closes again |
| SL | spike lower | spiked room | upper craw nest | LEVER broken FROM greymoor crow nest (crow arena) |  | Verified |  |
| SL | spike lower | upper craw nest | spiked room | clawline OR ((progressive swift step 2 OR sharpdart) AND (drifter cloak OR faydown cloak)) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND (medium crest pogo (hunter, reaper, wanderer, beast, witch, shaman) OR (medium crest pogo (architect) AND ledge grab))) |  | Verified |  |
| SU | spike upper | spiked room | upper craw nest | easy spike pogo OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified |  |
| SU | spike upper | upper craw nest | spiked room | none |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #2 | lower left section | none |  | Verified | Not included |  |
| Greymoor - Rosary Cache #20 | middle craw nest | faydown cloak OR silk soar (hard skip AND clawline AND shamna crest AND ledge grab) OR hard enemy pogo |  | Verified | Not included |  |
| Flea Freymoor - Craw Lake | flea room | silk soar OR ledge grab OR faydown cloak OR cling grip OR hard enemy pogo |  | Verified | Not included |  |
| Greymoor - Rosary Cache #21 | flea room | none |  | Verified | Not included |  |
| Greymoor - Rosary Cache #22 | flea room | none |  | Verified | Not included |  |
| Greymoor - Rosary Cache #19 | upper craw nest | silk soar OR clawline OR (drifter cloak AND (faydown cloak OR ledge grab OR sharpdart OR progressive swift step 1 OR easy flea brew)) OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND easy flea brew))) OR (progressive swift step 2 AND faydown cloak) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified | Not included |  |
| Threefold Pin | upper craw nest | silk soar OR silk soar OR clawline OR (drifter cloak AND (faydown cloak OR ledge grab OR sharpdart OR progressive swift step 1 OR easy flea brew)) OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND easy flea brew))) OR (progressive swift step 2 AND faydown cloak) OR (LEVER broken FROM greymoor crow nest (crow arena) UP AND easy crest pogo (hunter, reaper, wanderer, beast, witch, architect, shaman)) |  | Verified | Included |  |
