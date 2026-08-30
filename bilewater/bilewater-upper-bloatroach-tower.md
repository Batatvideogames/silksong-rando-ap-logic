# Bilewater Upper Bloatroach Tower (Shadow_01)

**Game ID:** Shadow_01

**Contributors:** Herchey and Red (his cat)

## Subrooms

- lower left
- lower right
- lower climb
- middle left
- middle right
- middle climb
- upper left
- upper right
- top

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MR | middle right | middle right | [Bilewater Hanging Corpse Room (Shadow_16)](bilewater-hanging-corpse-room.md) | L | none |  |  |  |
| UR | upper right | upper right | [Bilewater Groal Arena (Shadow_18)](bilewater-groal-arena.md) | L | none |  |  |  |
| LR | lower right | lower right | [Bilewater Upper East Column (Shadow_26)](bilewater-upper-east-column.md) | UL | none |  |  |  |
| ML | middle left | middle left | [Bilewater Bullshit Bench (Shadow_15)](bilewater-bullshit-bench.md) | LR | right attack |  |  | Cannot enter from right until broken from left. |
| UL | upper left | upper left | [Bilewater Bullshit Bench (Shadow_15)](bilewater-bullshit-bench.md) | UR | none |  |  |  |
| LL | lower left | lower left | [Bilewater Upper West Column (Shadow_14)](bilewater-upper-west-column.md) | UR | none |  |  |  |
| C | ceiling | top | [Putrified Ducts Connection To Bilewater (Aqueduct_04)](../putrified-ducts/putrified-ducts-connection-to-bilewater.md) | F | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LLR | lower left to lower right | lower left | lower right | swim OR (dash AND (faydown cloak OR cling grip OR crest pogo)) OR (faydown cloak AND drifter's cloak) |  |  | Due to the nature of the room, enemy pogos are expected here |
| LLR | lower left to lower right | lower right | lower left | (swim AND faydown cloak AND (ledge grab OR cling grip)) OR clawline OR (cling grip AND faydown cloak AND (crest pogo OR clawline)) |  |  | Due to the nature of the room, enemy pogos are expected here |
| LMR | lower left to middle right | lower left | middle right | cling grip AND ((faydown cloak AND (clawline OR crest pogo)) OR (drifter's cloak AND clawline)) |  |  | Due to the nature of the room, enemy pogos are expected here |
| LMR | lower left to middle right | middle right | lower left | swim OR crest pogo OR clawline OR dash |  |  | Dash only is very easily possible if the nearby bloatroach is dead |
| RML | middle right to middle left | middle right | middle left | cling grip AND (drifter's cloak AND (shartdart OR clawline OR (crest pogo AND ledge grab)) OR (faydown cloak AND (drifter's cloak OR dash OR clawline OR sharpdart))) OR (run AND faydown cloak AND (clawline OR crestpogo)) |  |  |  |
| RML | middle right to middle left | middle left | middle right | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR dash OR run |  |  | Doing this with only run is a pretty precise coyote jump to make it past the spikes. easy_skips maybe? |
| URT | upper right to top | upper right | top | cling grip AND dash AND (crest pogo OR clawline) |  |  |  |
| URT | upper right to top | top | upper right | none |  |  |  |
| MLL | middle left to upper left | middle left | upper left | faydown cloak AND (ledge grab OR cling grip) AND (crest pogo OR clawline) |  |  |  |
| MLL | middle left to upper left | upper left | middle left | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR run OR dash OR crest pogo OR scuttlebrace |  |  | Throw scuttle into easy_skips probably because it's not as intuitive |

## Check Locations

No check locations defined.
