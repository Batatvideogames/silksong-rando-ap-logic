# Greymoor East Bellshrine Room (Greymoor_02)

**Game ID:** Greymoor_02

**Contributors:** Isssma

## Subrooms

- lower section left
- lower section right
- middle section right
- middle section left
- bridge left section
- bridge right section
- upper crow nest
- lone crow platform
- top left
- top right
- hidden exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LSL | lower left | lower section left | [Greymoor West Bellshrine Room  (Greymoor_01)](greymoor-west-bellshrine-room.md) | LR | none |  | Verified |  |
| LR | lower right | lower section right | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | LL | none |  | Verified |  |
| ML | middle left | middle section left | [Greymoor Bellshrine (Bellshrine_02)](greymoor-bellshrine.md) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Craw Lake Entrance (Greymoor_15)](greymoor-craw-lake-entrance.md) | UL | none |  | Verified |  |
| BL | bridge left | bridge left section | [Greymoor West Bellshrine Room  (Greymoor_01)](greymoor-west-bellshrine-room.md) | TR | none |  | Verified |  |
| HR | hidden right | hidden exit | [Greymoor Silver Shells room (Greymoor_17)](greymoor-silver-shells-room.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | tall platform | lower section right | lower section left | ledge grab OR faydown cloak OR silk soar OR cling grip |  | Verified |  |
| TP | tall platform | lower section left | lower section right | nothing (just fall) |  | Verified |  |
| F1 | fall 1 | middle section left | lower section left | nothing (just fall) |  | Verified |  |
| LS1 | lever switch 1 | lower section right | middle section right | silk soar OR prereq balloon switch |  | Verified |  |
| LS1 | lever switch 1 | middle section right | lower section right | none (just fall) |  | Verified |  |
| G1 | gap 1 | middle section right | middle section left | prereq balloon switch OR progressive swift step 1 OR clawline OR sharpdart OR drifters cloak OR faydown cloak OR silk soar |  | Verified |  |
| G1 | gap 1 | middle section left | middle section right | Progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR silksoar OR (progressive swift step 1 AND (faydown cloak OR ledge grab)) OR prereq balloon switch |  | Verified |  |
| BG | bridge gap | bridge left section | bridge right section | (prereq bridge lever AND (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND (( flea brew AND ledge grab) OR (silkspeed anklets AND cling grip)))) AND (drifters cloak OR faydown cloak)))) OR nothing |  | Verified |  |
| BG | bridge gap | bridge right section | bridge left section | (prereq bridge lever AND (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND ((flea brew AND ledge grab) OR (silkspeed anklets AND cling grip)))) AND (drifters cloak OR faydown cloak)))) OR nothing |  | Verified |  |
| CR | climb right | middle section right | bridge right section | prereq bridge lever AND (cling grip OR silk soar) |  | Verified |  |
| CR | climb right | bridge right section | middle section right | prereq bridge lever |  | Verified |  |
| CL | climb left | middle section left | bridge left section | prereq bridge lever AND (silk soar OR (cling grip AND faydown cloak)) |  | Verified |  |
| CL | climb left | bridge left section | middle section left | prereq bridge lever |  | Verified |  |
| UL | upper left | bridge left section | upper crow nest | silk soar |  | Verified |  |
| UL | upper left | upper crow nest | bridge left section | none (fall) |  | Verified |  |
| UR | upper right | bridge right section | lone crow platform | nothing |  | Verified |  |
| UR | upper right | lone crow platform | bridge right section | none (fall) |  | Verified |  |
| G2 | gap 2 | lone crow platform | upper crow nest | silk soar OR faydown cloak OR hard enemy pogo OR clawline OR sharpdart OR progressive swift step 2 OR drifters cloak |  | Verified |  |
| G2 | gap 2 | upper crow nest | lone crow platform | nothing |  | Verified |  |
| S1 | shaft 1 | upper crow nest | top right | silk soar OR (cling grip AND ((proficient movement AND spike pogo) OR progressive swift step 1 OR clawline OR sharpdart OR drifters cloak OR medium enemy pogo )) |  | Verified |  |
| S1 | shaft 1 | top right | upper crow nest | nada |  | Verified |  |
| PG1 | platform gap | upper crow nest | top left | silk soar OR faydown cloak OR hard enemy pogo |  | Verified |  |
| PG1 | platform gap | top left | upper crow nest | nothing |  | Verified |  |
| G3 | gap 3 | top left | top right | faydown cloak OR (ledge grab AND (clawline OR progressive swift step 1 OR sharpdart) ) |  | Verified |  |
| G3 | gap 3 | top right | top left | nothing |  | Verified |  |
| B | blockade | top right | hidden exit | break wall right OR break wall up |  | Verified |  |
| B | blockade | hidden exit | top right | break wall left OR break wall up |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Spool Fragment | top left | nothing |  | Verified | collectible |  |
| Greymoor #2 - Rosary Cache | upper crow nest | nothing |  | Verified | resource |  |
| Greymoor #3 - Rosary Cache | upper crow nest | nothing |  | Verified | resource |  |
| Greeymoor - map purchase | lower section right | nothing |  | Verified | collectible |  |
| balloon switch | middle section right | flip lever up OR flip lever right OR flip lever left |  | Verified | switch |  |
| bridge lever | bridge right section | flip lever up OR flip lever right OR flip lever left |  | Verified | switch |  |
