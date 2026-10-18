# Greymoor Craw Nest (Room_CrowCourt)

**Game ID:** Room_CrowCourt

**Contributors:** Isssma

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | crow lower nest | ✓ |
| S2 | crow arena | ✓ |
| S3 | crow nest entrance | ✓ |
| S4 | balloon control room | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bottom | crow lower nest | [Greymoor Craw Court (Room_CrowCourt_02)](greymoor-craw-court.md) | T | craw summons ready |  | Verified | ✓ |  |
| L | left | crow nest entrance | [Greymoor Craw Lake (Greymoor_15b)](greymoor-craw-lake.md) | CN | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| f1 | fall 1 | crow nest entrance | crow lower nest | none (just fall) |  | Verified | ✓ |  |
| f1 | fall 1 | crow lower nest | crow nest entrance | silk soar OR prereq balloon lever |  | Verified | ✓ |  |
| f2 | fall 2 | crow arena | crow lower nest | none (just fall) |  | Verified | ✓ |  |
| f2 | fall 2 | crow lower nest | crow arena | ledge grab OR silk soar OR faydown cloak OR easy enemy pogo |  | Verified | ✓ |  |
| PG1 | platform gap 1 | crow arena | balloon control room | clear Craw Lake Gauntlet AND (easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR easy hunter pogo OR faydown cloak OR ledge grab OR silk soar OR ledge grab) |  | Verified | ✓ |  |
| PG1 | platform gap 1 | balloon control room | crow arena | clear Craw Lake Gauntlet |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | balloon lever | balloon control room | flip lever up OR flip lever left OR flip lever right |  | Verified | switch | ✓ |  |
| 2 | Greymoor - entrance rosary stash | crow nest entrance | nothing |  | Verified | resource | ✓ |  |
| 3 | Greymoor - entrance food savings | crow nest entrance | nothing |  | Verified | resource | ✓ |  |
| 4 | Greymoor - nest savings at the extreme left | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 5 | Greymoor - nest savings at the extreme right | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 6 | Greymoor - nest mortage at the inner right | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 7 | Greymoor - nest mortage at the inner left | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 8 | Greymoor - some dumb bird life savings left outside in the nest | crow arena | none |  | Verified | resource | ✓ |  |
| 9 | Craw Lake Gauntlet | crow arena | nothing |  | Verified | gauntlet | ✓ |  |
| 10 | Squatcraw 1 |  |  |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 11 | Craw 1 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 12 | Craw 2 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 13 | Craw 3 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 14 | Tallcraw 1 |  |  |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 15 | Craw 4 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 16 | Craw 5 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 17 | Craw 6 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 18 | Craw 7 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 19 | Craw 8 |  |  |  |  | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 20 | Tallcraw 2 |  |  |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 21 | Squatcraw 2 |  |  |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 22 | Tallcraw 3 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 23 | Squatcraw 3 |  | Normal World Spawn |  |  | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 24 | Mite 1 |  |  |  |  | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |
| 25 | Mite 2 |  |  |  |  | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |
| 26 | Mite 3 |  |  |  |  | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |

## Room Images

### Connections

[![Connections for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-connections.png)](../00-annotations/greymoor/greymoor-craw-nest-connections.png)

### Checks

[![Checks for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-checks.png)](../00-annotations/greymoor/greymoor-craw-nest-checks.png)

### Scene

[![Scene for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-scene.png)](../00-annotations/greymoor/greymoor-craw-nest-scene.png)
