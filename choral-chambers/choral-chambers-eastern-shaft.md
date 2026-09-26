# Choral Chambers Eastern Shaft (Song_05)

**Game ID:** Song_05

## Subrooms

- Section 1
- Section 2
- Section 3
- Section 4

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | left5 | Section 1 | [Choral Chambers Below Spa (Song_02)](choral-chambers-below-spa.md) | R | none |  | Verified |  |
| R1 | right3 | Section 1 | [Whiteward Entrance (Ward_01)](../whiteward/whiteward-entrance.md) | TL | none |  | Verified |  |
| L2 | left4 | Section 3 | [Choral Chambers Merchant Room (Song_07)](choral-chambers-merchant-room.md) | R | none |  | Verified |  |
| R2 | right4 | Section 2 | [Choral Chambers East to West (Song_27)](choral-chambers-east-to-west.md) | L | activate door switch IN choral chambers east to west |  | Verified |  |
| L3 | left3 | Section 3 | [Choral Chambers Flea Shaft (Song_11)](choral-chambers-flea-shaft.md) | BR | none |  | Verified |  |
| R4 | right2 | Section 4 | [Choral Chambers Below Dining (Song_18)](choral-chambers-below-dining.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Section 1 to Section 2 | Section 1 | Section 2 | (ledge grab AND pogo) OR silk soar OR (cling grip AND (dash OR clawline)) |  |  |  |
| V2 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar OR (cling grip AND (ledge grab OR clawline)) OR faydown cloak |  |  |  |
| V3 | Section 3 to Section 4 | Section 3 | Section 4 | ((ledge grab OR clawline) AND pogo) OR silk soar |  |  |  |
| F4 | Falling from Section 4 | Section 4 | Section 3 | none |  |  | falling |
| F3 | Falling from Section 3 | Section 3 | Section 2 | none |  |  | falling |
| F2 | Falling from Section 2 | Section 2 | Section 1 | none |  |  | falling |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lace Second Encounter | Section 1 | none |  | Verified | event |  |
