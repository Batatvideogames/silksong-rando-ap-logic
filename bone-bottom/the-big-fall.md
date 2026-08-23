# The Big Fall (Aspid_01)

**Game ID:** Aspid_01

**Contributors:** herounit, Super EpicGuy

## Subrooms

- top area
- upper right ledge
- upper left ledge
- wish ledge
- middle right ledge
- lower left area
- lower right area
- bottom area
- upper silk soar only zone
- lower silk soar only zone

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T1 | top1 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B1 | silk soar AND lace gone |  |  | if lace starts her cutscene on you she cancels your silk soar and you fall back down without clearing the cutscene |
| T2 | top2 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B2 | silk soar AND lace gone |  |  |  |
| T3 | top3 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B3 | silk soar AND lace gone |  |  |  |
| T4 | top4 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B4 | silk soar AND lace gone |  |  |  |
| T5 | top5 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B5 | silk soar AND lace gone |  |  |  |
| T6 | top6 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B6 | silk soar AND lace gone |  |  |  |
| T7 | top7 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B7 | silk soar AND lace gone |  |  |  |
| UR | upper right | upper right ledge | [Shellwood Lower Toll bench (Shellwood_08c)](../shellwood/shellwood-lower-toll-bench.md) | L | none |  |  |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](mosshome-upper.md) | L | breakable wall -must be opened from the other side |  |  |  |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](mosshome-lower.md) | L | none |  |  |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](../wormways/wormways-upper-east.md) | R | none |  |  |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](../wormways/wormways-craggler-hallway.md) | R | none |  |  |  |
| B1 | bot1 | bottom area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T1 | none |  |  |  |
| B2 | bot2 | lower right area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T2 | none |  |  |  |
| B3 | bot3 | bottom area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T3 | none |  |  |  |
| B4 | bot4 | bottom area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T4 | none |  |  |  |
| B5 | bot5 | bottom area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T5 | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  |  |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling |  |  |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  |  |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  |  |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  |  |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  |  |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom area | none (falling) |  |  |  |
| F8 | lower left area fall | lower left area | bottom area | none (falling) |  |  |  |
| F9 | lower right area fall | lower right area | bottom area | none (falling) |  |  |  |
| S1 | bottom silk soar | bottom area | lower silk soar only zone | silk soar |  |  |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  |  |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  |  |  |
| LC | lower crossing | lower left area | lower right area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak OR silk soar |  |  |  |
| LC | lower crossing | lower right area | lower left area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak |  |  |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar OR cling grip OR (dash AND scuttlebrace) |  |  | can't be collected unless the wish has been started from bellhart |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar OR cling grip OR faydown cloak OR ((medium enemy pogo OR ledge grab) AND (run OR sharpdart OR easy crest pogo beast)) OR (easy enemy pogo AND (clawline OR dash OR medium crest pogo shaman)) |  |  |  |
| UC | upper crossing | upper right ledge | upper left ledge | none |  |  |  |
| LM | lower to middle climb | lower right area | middle right ledge | silk soar OR (CBT skips AND hard enemy pogo AND hard spike pogo AND (cocoon skip OR hard tool stall) AND wall cling AND drifters cloak) OR (medium enemy pogo AND easy spike pogo AND wall cling AND faydown cloak) |  |  |  |
| LM | lower to middle climb | middle right ledge | lower right area | none (fall) |  |  |  |
| LW | lower to wish climb | lower right area | wish ledge | silk soar OR (hard enemy pogo AND easy spike pogo AND ((run AND ledge grab) OR dash) AND wall cling AND faydown cloak AND drifters cloak AND clawline) |  |  |  |
| LW | lower to wish climb | wish ledge | lower right area | none (fall) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache moss grotto | lower left area | none |  |  | Included |  |
| choral commandment moss grotto | middle right ledge | none |  |  | Included |  |
| wish my missing courier | wish ledge | none |  |  | Included |  |
