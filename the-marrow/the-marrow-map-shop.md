# The Marrow Map Shop (Bone_04)

**Game ID:** Bone_04

**Contributors:** herounit

## Subrooms

- right lower path
- right upper path
- middle upper platform
- shakra intro
- bench spot

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right upper path | [The Marrow Shaft (Bone_03)](the-marrow-shaft.md) | ML | none |  | Verified |  |
| F | floor | right lower path | [The Marrow Entrance (Bone_01)](the-marrow-entrance.md) | C | none |  | Verified |  |
| UL | upper left | bench spot | [Mosshome Lower (Bone_11)](../bone-bottom/mosshome-lower.md) | UR | none |  | Verified |  |
| LL | lower left | shakra intro | [Mosshome Lower (Bone_11)](../bone-bottom/mosshome-lower.md) | LR | none |  | Verified |  |
| C | ceiling | shakra intro | [The Marrow Bellway (Bone_05)](the-marrow-bellway.md) | F | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | shakra intro | bench spot | activate bench gate switch |  | Verified |  |
| DS | door switch | bench spot | shakra intro | activate bench gate switch |  | Verified |  |
| V1 | vertical 1 | right lower path | right upper path | ledge grab  OR cling grip OR silk soar OR faydown |  | Verified |  |
| V1 | vertical 1 | right upper path | right lower path | none (falling) |  | Verified |  |
| G1 | gap 1 | right upper path | middle upper platform | activate lower platform switch same room OR clawline OR sharpdart OR faydown OR ( run AND ( ledge grab OR dash OR easy beast pogo OR easy shaman pogo OR drifters ) ) |  | Verified |  |
| G1 | gap 1 | middle upper platform | right upper path | activate lower platform switch same room |  | Verified |  |
| V2 | vertical 2 | right lower path | middle upper platform | silk soar |  | Verified |  |
| V2 | vertical 2 | middle upper platform | right lower path | none (falling) |  | Verified |  |
| V3 | vertical 3 | right lower path | shakra intro | ledge grab  OR cling grip OR silk soar OR faydown OR scuttlebrace OR easy shaman pogo |  | Verified |  |
| V3 | vertical 3 | shakra intro | right lower path | none (falling) |  | Verified |  |
| G2 | gap 2 | middle upper platform | shakra intro | run  OR dash OR easy beast pogo OR easy architect pogo OR drifters OR faydown OR clawline OR sharpdart |  | Verified |  |
| G2 | gap 2 | shakra intro | middle upper platform | clawline OR sharpdart |  | Verified | anything that would get you from lower to upper is excluded for simplicity (ledge grab) |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lower platform switch same room | right lower path | flip switch down |  | Verified | switch |  |
| the marrow rosary cache 7 | right lower path | none |  | Verified | collectible |  |
| lower platform switch other room | middle upper platform | flip switch up |  | Verified | switch | lowers platform into the marrow entrance room |
| the marrow shell shard cache 2 | shakra intro | none |  | Verified | collectible |  |
| the marrow shell shard cache 3 | shakra intro | none |  | Verified | collectible |  |
| quill | shakra intro | rosaries 50 |  | Verified | collectible | shakra's shop |
| compass | shakra intro | rosaries 70 |  | Verified | collectible | shakra's shop |
| map mosslands | shakra intro | rosaries 40 |  | Verified | collectible | shakra's shop |
| map the marrow | shakra intro | rosaries 50 |  | Verified | collectible | shakra's shop |
| map bench pins | shakra intro | rosaries 60 |  | Verified | collectible | shakra's shop |
| map bellway pins | shakra intro | rosaries 60 |  | Verified | collectible | shakra's shop \| appears to be bugged in availability logic still. shows available but isn't |
| volatile flintbeetle 2 | right upper path | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | this one swaps position based on when the marrow bellshrine is activated (per the wiki) - best to ensure both locations are accessible for the quest |
| bench gate switch | bench spot | flip switch up |  | Verified | switch |  |
| bench | bench spot | none |  | Verified | bench |  |
