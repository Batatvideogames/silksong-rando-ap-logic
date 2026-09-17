# Greymoor Crow Nest (Room_CrowCourt)

**Game ID:** Room_CrowCourt

**Contributors:** Isssma

## Subrooms

- crow lower nest
- crow arena
- crow nest entrance
- balloon control room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| b | bottom | crow lower nest | [Greymoor Crow Court (Room_CrowCourt_02)](greymoor-crow-court.md) | T | craw summons ready |  | Verified |  |
| L | left | crow nest entrance | [Greymoor Craw Lake (Greymoor_15b)](greymoor-craw-lake.md) | CN | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| f1 | fall 1 | crow nest entrance | crow lower nest | none (just fall) |  | Verified |  |
| f1 | fall 1 | crow lower nest | crow nest entrance | silk soar OR prereq balloon lever |  | Verified |  |
| f2 | fall 2 | crow arena | crow lower nest | none (just fall) |  | Verified |  |
| f2 | fall 2 | crow lower nest | crow arena | ledge grab OR silk soar OR faydown cloak OR easy enemy pogo |  | Verified |  |
| PG1 | platform gap 1 | crow arena | balloon control room | clear Craw Lake Gauntlet AND (easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR easy hunter pogo OR faydown cloak OR ledge grab OR silk soar OR ledge grab) |  | Verified |  |
| PG1 | platform gap 1 | balloon control room | crow arena | clear Craw Lake Gauntlet |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| balloon lever | balloon control room | flip lever up OR flip lever left OR flip lever right |  | Verified | switch |  |
| Greymoor - Rosary Cache #30 | crow nest entrance | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #29 | crow nest entrance | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #28 | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #32 | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #33 | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #31 | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #34 | crow arena | none |  | Verified | resource |  |
| Craw Lake Gauntlet | crow arena | nothing |  | Verified | gauntlet |  |
