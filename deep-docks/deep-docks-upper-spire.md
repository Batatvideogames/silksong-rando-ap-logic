# Deep Docks Upper Spire (Bone_East_05)

**Game ID:** Bone_East_05

**Contributors:** herounit and Rebel

## Subrooms

- left flea platform
- spire
- right exit platform
- Flea Access Lever

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | spire | [Deep Docks Bench Shaft (Dock_01)](deep-docks-bench-shaft.md) | UR | Activate Deep Docks Upper Spire Gate Lever |  | Verified |  |
| R | right1 | right exit platform | [Is this still Deep Docks West (Bone_East_04b)](is-this-still-deep-docks-west.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SR | spire right | spire | right exit platform | Cling Grip  OR Sprint  OR Faydown Cloak  OR Clawline  OR Easy Scuttlebrace  OR ((Dash OR Drifter's Cloak) AND (Ledge Grab OR (Silk Soar AND Magma Bell)))  OR Easy Beast Charge  OR Easy Beast Pogo  OR Flea Brew OR Sharpdart  OR (Medium Shaman Crest Pogo AND Ledge Grab)  OR ((Easy Voltvessels Stall OR Easy Flintslate Stall OR Easy Plasmium Stall) AND Ledge Grab)  OR Easy Architect Charge  OR ((Proficient Movement AND Architect Attack Right) AND (Easy Heal Stall AND Ledge Grab)) OR Hard Plasmium Stall |  | Verified | removed unqualified "OR Flea Brew" - is it used as a stall or just having it enables you to make the jump? As far as I can tell, flea brew still requires ledge grab - hero, 9/28 removed "OR (Easy Drill Skip AND Ledge Grab)" until rebel can give feedback on how this works - hero, 9/28 |
| SR | spire right | right exit platform | spire | Nothing. |  | Verified |  |
| PG | platform gaps | spire | Flea Access Lever | Sprint OR Dash OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Silk Soar OR Scuttlebrace OR Easy Beast Charge OR Easy Beast Pogo OR Easy Architect Charge OR Flea Brew OR Medium Voltvessels Stall OR Sharpdart x 4 |  | Verified |  |
| PG | platform gaps | Flea Access Lever | spire | Nothing. (fall) |  | Verified |  |
| FG | Flea Get | Flea Access Lever | left flea platform | Silk Soar OR (Faydown Cloak AND Ledge Grab) OR Cling Grip OR (Activate Deep Docks Upper Spire Flea Lever AND (Easy Scuttlebrace OR Sprint OR Dash)) OR (Drifter's Cloak AND (Ledge Grab OR (Proficient Movement AND Architect Attack Left) )) OR ((Easy Architect Charge OR Easy Beast Charge) AND Ledge Grab) |  | Verified |  |
| FG | Flea Get | left flea platform | Flea Access Lever | Nothing. (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Deep Docks Upper Spire - Flea | left flea platform | Nothing. |  | Verified | collectible |  |
| Swift Step | spire | Nothing. |  | Verified | collectible |  |
| Deep Docks Upper Spire Gate Lever | spire | Flip Switch Left |  | Verified | switch |  |
| Deep Docks Upper Spire Flea Lever | Flea Access Lever | Flip Switch Left |  | Verified | switch |  |
| Garmond and Zaza Act 3 Meeting Deep Docks | spire | Act 3 |  | Verified | event |  |
