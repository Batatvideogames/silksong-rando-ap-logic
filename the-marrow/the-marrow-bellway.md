# The Marrow Bellway (Bone_05)

**Game ID:** Bone_05

**Contributors:** herounit

## Subrooms

- left area
- boss room
- right area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left area | [Mosshome Middle (Mosstown_01)](../bone-bottom/mosshome-middle.md) | LR | none |  | Verified |  |
| F | floor | left area | [The Marrow Map Shop (Bone_04)](the-marrow-map-shop.md) | C | none |  | Verified |  |
| R | right | right area | [The Marrow Bellshrine (Bellshrine)](the-marrow-bellshrine.md) | L | none |  | Verified |  |
| BB | bellway | left area | [Bellway Menu](../fast-travel/bellway-menu.md) | TM | unlock bellway the marrow |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  | Verified |  |
| LB | left boss fight | boss room | left area | none |  | Verified | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | defeat bell beast boss fight |  | Verified | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | defeat bell beast boss fight |  | Verified | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bell beast boss fight | boss room | silkspear |  | Verified | boss | only silkspear works here |
| bell beast silk heart | boss room | defeat bell beast boss fight |  | Verified | collectible |  |
| bellway the marrow | right area | defeat bell beast boss fight |  | Verified | travel |  |
