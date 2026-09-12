# Greymoor Craw Lake (Greymoor_15b)

**Game ID:** Greymoor_15b

**Contributors:** Isssma

## Subrooms

- craw building
- lower left section
- middle craw nest
- top craw nest
- spiked room
- flea room
- middle craw nest left
- small ass platform
- upper craw nest

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top | top craw nest | [Greymoor Weaver Shrine (Greymoor_22)](greymoor-weaver-shrine.md) | B | silk soar OR (prereq balloon lever IN greymoor crow nest AND (ledge grab OR faydown cloak OR cling grip)) |  | Verified |  |
| ML | middle left | middle craw nest left | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | UR | none |  | Verified |  |
| LR | lower right | craw building | TODO |  | ACT 3 AND (((cling grip OR silk soar) AND (clawline OR (progressive swift step 1 AND (drifters cloak OR (sharpdart AND faydown cloak))) OR (progressive swift step 2 AND faydown cloak))) OR (prereq balloon lever IN greymoor crow nest AND (easy beast pogo OR easy architect pogo OR easy shaman pogo OR clawline OR ((easy hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy witch pogo) AND (faydown cloak OR drifters cloak OR clawline OR sharpdart OR progressive swift step 2)) OR ((easy reaper pogo OR easy wanderer pogo OR easy witch pogo) AND ledge grab)))) |  | Verified |  |
| CN | craw nest entrance | craw building | [Greymoor Crow Nest (Room_CrowCourt)](greymoor-crow-nest.md) | L | swim OR ledge grab OR cling grip OR hard enemy pogo |  | Verified |  |
| LL | lower left | lower left section | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | LR | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | lake gap | lower left section | craw building | swim OR clawline OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND drifters cloak) OR (silk soar AND drifters cloak AND (faydown cloak OR sharpdart OR progressive swift step 2)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| LG | lake gap | craw building | lower left section | swim OR clawline OR silk soar OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND (drifters cloak OR ((ledge grab OR cling grip) AND faydown cloak))) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| FL | fall left | upper craw nest | flea room | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR faydown cloak |  | Verified |  |
| FL | fall left | flea room | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| FR | fall right | upper craw nest | middle craw nest left | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR (faydown cloak AND ledge grab) |  | Verified |  |
| FR | fall right | middle craw nest left | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| G1 | gap 1 | craw building | small ass platform | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR medium hunter pogo OR medium reaper pogo OR medium beast pogo OR medium witch pogo OR medium architect pogo OR medium shaman pogo |  | Verified |  |
| G1 | gap 1 | small ass platform | craw building | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |
| G2 | gap 2 | middle craw nest left | middle craw nest | none (normal jump) |  | Verified |  |
| G2 | gap 2 | middle craw nest | middle craw nest left | (progressive swift step 1 AND faydown cloak AND ledge grab) OR  prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | middle craw nest | flea room | drifters cloak OR clawline OR (progressive swift step 2 AND (ledge grab OR cling grip OR sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | flea room | middle craw nest | drifters cloak OR clawline OR (progressive swift step 2 AND (sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D1 | drop 1 | craw building | flea room | silk soar |  | Verified |  |
| D1 | drop 1 | flea room | craw building | none (just fall) |  | Verified |  |
| D2 | drop 2 | upper craw nest | middle craw nest | none (just fall) |  | Verified |  |
| D2 | drop 2 | middle craw nest | upper craw nest | silk soar OR (prereq balloon lever IN greymoor crow nest AND (medium hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy beast pogo OR medium witch pogo OR easy architect pogo OR easy shaman pogo OR clawline OR ledge grab)) |  | Verified |  |
| D3 | drop 3 | middle craw nest | craw building | none (just fall) |  | Verified |  |
| D3 | drop 3 | craw building | middle craw nest | silk soar OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | small ass platform | middle craw nest | prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | middle craw nest | small ass platform | clawline OR sharpdart OR progressive swift step 2 OR faydown cloak OR drifters cloak OR (progressive swift step 1 AND (ledge grab OR flea brew OR silkspeed anklets)) |  | Verified |  |
| H | hatch | craw building | flea room | prereq flea airlock |  | Verified |  |
| H | hatch | flea room | craw building | prereq flea airlock |  | Verified |  |
| SL | spike lower | spiked room | upper craw nest | prereq spike room lever |  | Verified |  |
| SL | spike lower | upper craw nest | spiked room | clawline OR ((progressive swift step 2 OR sharpdart) AND (drifters cloak OR faydown cloak)) OR (prereq balloon lever IN greymoor crow nest AND (easy hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy beast pogo OR easy witch pogo OR easy shaman pogo OR ledge grab OR clawline)) |  | Verified |  |
| SU | spike upper | spiked room | top craw nest | easy skip spike pogo OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| SU | spike upper | top craw nest | spiked room | none |  | Verified |  |
| F1 | fall 1 | top craw nest | upper craw nest | none (just fall) |  | Verified |  |
| F1 | fall 1 | upper craw nest | top craw nest | silk soar OR (cling grip AND (easy enemy pogo OR faydown cloak)) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #2 | lower left section | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #20 | middle craw nest | faydown cloak OR silk soar (hard skip AND clawline AND shamna crest AND ledge grab) OR hard enemy pogo |  | Verified | resource |  |
| Flea Freymoor - Craw Lake | flea room | silk soar OR ledge grab OR faydown cloak OR cling grip OR hard enemy pogo |  | Verified | collectible |  |
| Greymoor - Rosary Cache #21 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #22 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #19 | top craw nest | silk soar OR clawline OR (drifters cloak AND (faydown cloak OR ledge grab OR sharpdart OR progressive swift step 1 OR flea brew)) OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND flea brew))) OR (progressive swift step 2 AND faydown cloak) OR prereq balloon lever IN greymoor crow nest |  | Verified | resource |  |
| Threefold Pin | top craw nest | silk soar OR clawline OR (drifters cloak AND (faydown cloak OR ledge grab OR sharpdart OR progressive swift step 1 OR flea brew)) OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND flea brew))) OR (progressive swift step 2 AND faydown cloak) OR prereq balloon lever IN greymoor crow nest |  | Verified | collectible |  |
| flea airlock | flea room | open airlock left OR open airlock right OR open airlock up |  | Verified | switch |  |
| spike room lever | upper craw nest | flip lever up OR flip lever left OR flip lever right |  | Verified | switch |  |
