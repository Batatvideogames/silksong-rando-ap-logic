# Greymoor Craw Lake (Greymoor_15b)

**Game ID:** Greymoor_15b

**Contributors:** Isssma

## Subrooms

- craw building
- lower left section
- middle craw nest
- left top craw nest
- spiked room
- flea room
- middle craw nest left
- small ass platform
- upper craw nest
- lower flea room
- right top craw nest
- lil top

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top | lil top | [Greymoor Weaver Shrine (Greymoor_22)](greymoor-weaver-shrine.md) | B | silk soar OR ledge grab OR faydown cloak OR cling grip |  | Verified |  |
| ML | middle left | middle craw nest left | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | UR | none |  | Verified |  |
| LR | lower right | craw building | TODO |  | ACT 3 AND (((cling grip OR silk soar) AND (clawline OR (progressive swift step 1 AND (drifters cloak OR (sharpdart AND faydown cloak))) OR (progressive swift step 2 AND faydown cloak))) OR (prereq balloon lever IN greymoor crow nest AND (clawline OR faydown cloak OR drifters cloak OR sharpdart OR progressive swift step 2 OR ledge grab OR easy hunter pogo OR easy architect pogo OR easy shaman pogo OR easy beast crest pogo))) |  | Verified |  |
| CN | craw nest entrance | craw building | [Greymoor Crow Nest (Room_CrowCourt)](greymoor-crow-nest.md) | L | swim OR ledge grab OR cling grip OR hard enemy pogo |  | Verified |  |
| LL | lower left | lower left section | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | LR | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | lake gap | lower left section | craw building | swim OR clawline OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND drifters cloak) OR (silk soar AND drifters cloak AND (faydown cloak OR sharpdart OR progressive swift step 2)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| LG | lake gap | craw building | lower left section | swim OR clawline OR silk soar OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND (drifters cloak OR ((ledge grab OR cling grip) AND faydown cloak))) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| FR | fall right | right top craw nest | flea room | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR faydown cloak |  | Verified |  |
| FL | fall left | upper craw nest | middle craw nest left | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR (faydown cloak AND ledge grab) |  | Verified |  |
| FL | fall left | middle craw nest left | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| G1 | gap 1 | craw building | small ass platform | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G1 | gap 1 | small ass platform | craw building | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR  prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G2 | gap 2 | middle craw nest left | middle craw nest | none (normal jump) |  | Verified |  |
| G2 | gap 2 | middle craw nest | middle craw nest left | (progressive swift step 1 AND faydown cloak AND ledge grab) OR  prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | middle craw nest | flea room | drifters cloak OR clawline OR (progressive swift step 2 AND (ledge grab OR cling grip OR sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | flea room | middle craw nest | drifters cloak OR clawline OR (progressive swift step 2 AND (sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G4 | gap 4 | craw building | lower flea room | faydown cloak OR silk soar OR hard enemy pogo |  | Verified |  |
| G4 | gap 4 | lower flea room | craw building | none |  | Verified |  |
| G5 | gap 5 | left top craw nest | right top craw nest | clawline OR drifters cloak OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND flea brew))) OR (progressive swift step 2 AND faydown cloak) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G5 | gap 5 | right top craw nest | left top craw nest | (progressive swift step 1 AND faydown cloak AND (drifters cloak OR sharpdart)) OR (clawline AND (faydown cloak OR progressive swift step 2 OR drifters cloak OR sharpdart OR (progressive swift step 1 AND medium beast pogo))) OR (progressive swift step 2 AND faydown cloak AND flea brew) OR (sharpdart AND faydown cloak AND drifters cloak) OR (prereq balloon lever IN greymoor crow nest AND (clawline OR faydown cloak OR sharpdart OR (drifters cloak AND progressive swift step 1) OR progressive swift step 2)) |  | Verified |  |
| D1 | drop 1 | craw building | flea room | silk soar |  | Verified |  |
| D1 | drop 1 | flea room | craw building | none (just fall) |  | Verified |  |
| D2 | drop 2 | upper craw nest | middle craw nest | none (just fall) |  | Verified |  |
| D2 | drop 2 | middle craw nest | upper craw nest | silk soar OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D3 | drop 3 | middle craw nest | craw building | none (just fall) |  | Verified |  |
| D3 | drop 3 | craw building | middle craw nest | silk soar OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | small ass platform | middle craw nest | prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | middle craw nest | small ass platform | clawline OR sharpdart OR progressive swift step 2 OR faydown cloak OR drifters cloak OR (progressive swift step 1 AND (ledge grab OR flea brew OR silkspeed anklets)) |  | Verified |  |
| H | hatch | lower flea room | flea room | prereq flea airlock |  | Verified |  |
| H | hatch | flea room | lower flea room | prereq flea airlock |  | Verified |  |
| SL | spike lower | spiked room | upper craw nest | prereq spike room lever AND (clawline AND faydown cloak AND (ledge grab OR progressive swift step 1)) |  | Verified |  |
| SL | spike lower | upper craw nest | spiked room | (clawline OR ((progressive swift step 2 OR sharpdart) AND (drifters cloak OR faydown cloak)) ) AND prereq spike room lever |  | Verified |  |
| SU | spike upper | spiked room | left top craw nest | easy skip spike pogo OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| SU | spike upper | left top craw nest | spiked room | none |  | Verified |  |
| F1 | fall 1 | left top craw nest | upper craw nest | none (just fall) |  | Verified |  |
| F1 | fall 1 | upper craw nest | left top craw nest | silk soar OR (cling grip AND (easy enemy pogo OR faydown cloak)) |  | Verified |  |
| F2 | fall 2 | right top craw nest | middle craw nest | nothing (just fall) |  | Verified |  |
| F2 | fall 2 | middle craw nest | right top craw nest | silk soar OR (prereq balloon lever IN greymoor crow nest AND faydown cloak AND (ledge grab OR cling grip)) |  | Verified |  |
| F3 | fall 3 | right top craw nest | upper craw nest | drifters cloak OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR (flea brew AND ledge grab) |  | Verified |  |
| F4 | fall 4 | spiked room | middle craw nest left | prereq spike room lever |  | Verified |  |
| F4 | fall 4 | middle craw nest left | spiked room | (prereq balloon lever IN greymoor crow nest OR silk soar) AND prereq spike room lever |  | Verified |  |
| FF | free fall | lil top | right top craw nest | nothing (just fall) |  | Verified |  |
| FF | free fall | right top craw nest | lil top | silk soar |  | Verified |  |
| BG | balloon gap | left top craw nest | lil top | prereq balloon lever IN greymoor crow nest |  | Verified |  |
| BG | balloon gap | lil top | left top craw nest | prereq balloon lever IN greymoor crow nest OR clawline OR sharpdart OR drifters cloak OR progressive swift step 2 OR (faydown cloak AND (ledge grab OR flea brew OR progressive swift step 1)) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #2 | small ass platform | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #20 | lower flea room | none |  | Verified | resource |  |
| Flea Freymoor - Craw Lake | flea room | silk soar OR ledge grab OR faydown cloak OR cling grip OR medium enemy pogo |  | Verified | collectible |  |
| Greymoor - Rosary Cache #21 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #22 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #19 | right top craw nest | nothing |  | Verified | resource |  |
| Threefold Pin | right top craw nest | nothing |  | Verified | collectible |  |
| flea airlock | flea room | open airlock left OR open airlock right OR open airlock up |  | Verified | switch |  |
| spike room lever | upper craw nest | flip lever up OR flip lever left OR flip lever right |  | Verified | switch |  |
