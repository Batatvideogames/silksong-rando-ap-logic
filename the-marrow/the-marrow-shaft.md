# The Marrow Shaft (Bone_03)

**Game ID:** Bone_03

**Contributors:** herounit

## Subrooms

- bottom shaft
- lower middle shaft
- upper middle shaft
- the bridge
- ceiling exit area
- big boy shelf
- collapsing upper crossing

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | bottom shaft | [The Marrow Lava Intro (Bone_02)](the-marrow-lava-intro.md) | LC | none |  | Verified |  |
| LL | lower left | bottom shaft | [The Marrow Shaft Side Room (Bone_17)](the-marrow-shaft-side-room.md) | R | none |  | Verified |  |
| ML | middle left | upper middle shaft | [The Marrow Map Shop (Bone_04)](the-marrow-map-shop.md) | R | none |  | Verified |  |
| UL | upper left | the bridge | [The Marrow Bellshrine (Bellshrine)](the-marrow-bellshrine.md) | R | ( bellshrinesanity off AND activate bellshrine switch IN the marrow bellshrine )  OR ( bellshrinesanity on AND have bell the marrow ) |  | Verified | requirement for inner and outer gate must be maintained in sync |
| LR | lower right | lower middle shaft | [The Marrow Flea Caravan (Bone_10)](the-marrow-flea-caravan.md) | L | none |  | Verified |  |
| UR | upper right | the bridge | [The Marrow Mr Burns House (Bone_14)](the-marrow-mr-burns-house.md) | L | none |  | Verified |  |
| C | ceiling | ceiling exit area | [The Marrow Skull Wall (Bone_06)](the-marrow-skull-wall.md) | F | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | upper middle shaft | the bridge | activate door switch AND ( ledge grab OR run OR dash OR easy beast pogo OR easy shaman pogo OR drifters OR faydown OR cling grip OR silk soar OR clawline OR sharpdart ) |  | Verified |  |
| DS | door switch | the bridge | upper middle shaft | activate door switch |  | Verified |  |
| V1 | vertical 1 | bottom shaft | lower middle shaft | ledge grab OR easy enemy pogo OR cling grip OR faydown OR silk soar |  | Verified |  |
| V1 | vertical 1 | lower middle shaft | bottom shaft | none (falling) |  | Verified |  |
| V2 | vertical 2 | lower middle shaft | upper middle shaft | ledge grab OR easy enemy pogo OR run OR dash OR drifters OR faydown OR cling grip OR scuttlebrace OR clawline OR sharpdart OR silk soar OR easy shaman pogo OR easy hunter pogo OR easy architect pogo OR easy beast pogo OR easy wanderer charge OR easy reaper charge OR easy heal stall OR easy flea brew stall OR easy flintslate stall OR easy plasmium phial stall OR easy voltvessels stall |  | Verified | a WIDE variety of stalls work here. karma for the bottom section all being one chunk |
| V2 | vertical 2 | upper middle shaft | lower middle shaft | none (falling) |  | Verified |  |
| V3 | vertical 3 | the bridge | collapsing upper crossing | ledge grab OR cling grip OR faydown OR silk soar |  | Verified |  |
| V3 | vertical 3 | collapsing upper crossing | the bridge | none (falling) |  | Verified |  |
| V4 | vertical 4 | collapsing upper crossing | big boy shelf | ledge grab OR cling grip OR faydown OR silk soar OR easy enemy pogo |  | Verified |  |
| V4 | vertical 4 | big boy shelf | collapsing upper crossing | none (falling) |  | Verified |  |
| V5 | vertical 5 | big boy shelf | ceiling exit area | ledge grab OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| V5 | vertical 5 | ceiling exit area | big boy shelf | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | the bridge | flip switch down |  | Verified | switch |  |

## Notes

no checks
