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
- bottom gap area
- upper silk soar only zone
- lower silk soar only zone
- bottom left area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T1 | top1 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B1 | silk soar |  | Verified | if lace starts her cutscene on you she cancels your silk soar and you fall back down without clearing the cutscene |
| T2 | top2 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B2 | silk soar |  | Verified |  |
| T3 | top3 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B3 | silk soar |  | Verified |  |
| T4 | top4 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B4 | silk soar |  | Verified |  |
| T5 | top5 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B5 | silk soar |  | Verified |  |
| T6 | top6 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B6 | silk soar |  | Verified |  |
| T7 | top7 | top area | [Blasted Steps Map Edge (Coral_19)](../blasted-steps/blasted-steps-map-edge.md) | B7 | silk soar |  | Verified |  |
| UR | upper right | upper right ledge | [Shellwood Lower Toll bench (Shellwood_08c)](../shellwood/shellwood-lower-toll-bench.md) | L | none |  | Verified |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](mosshome-upper.md) | L | clear left exit breakable wall IN mosshome upper |  | Verified |  |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](mosshome-lower.md) | L | none |  | Verified |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](../wormways/wormways-upper-east.md) | R | none |  | Verified |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](../wormways/wormways-craggler-hallway.md) | R | none |  | Verified |  |
| B1 | bot1 | bottom gap area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T1 | none |  | Verified |  |
| B2 | bot2 | lower right area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T2 | none |  | Verified |  |
| B3 | bot3 | bottom gap area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T3 | none |  | Verified |  |
| B4 | bot4 | bottom gap area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T4 | none |  | Verified |  |
| B5 | bot5 | bottom gap area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | T5 | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  | Verified |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling) |  | Verified |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  | Verified |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  | Verified |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  | Verified |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  | Verified |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom gap area | none (falling) |  | Verified |  |
| F8 | lower left area fall | bottom left area | bottom gap area | none (falling) |  | Verified |  |
| F9 | lower right area fall | lower right area | bottom gap area | none (falling) |  | Verified |  |
| S1 | bottom silk soar | bottom gap area | lower silk soar only zone | silk soar |  | Verified |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  | Verified |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  | Verified |  |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar  OR cling grip  OR faydown cloak  OR ( ledge grab AND ( dash OR clawline OR medium scuttlebrace ) ) OR ( ( medium enemy pogo OR ledge grab ) AND ( run OR sharpdart OR easy beast pogo ) )  OR ( easy enemy pogo AND ( clawline OR dash OR medium shaman pogo ) ) |  | Verified |  |
| UC | upper crossing | upper right ledge | upper left ledge | none (parkour) |  | Verified |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar  OR cling grip OR ( ledge grab AND scuttlebrace ) |  | Verified |  |
| LW | lower to wish climb | lower right area | wish ledge | silk soar  OR ( hard enemy pogo AND ( spike pogo AND proficient movement ) AND ( ( run AND ledge grab ) OR dash ) AND cling grip AND faydown cloak AND drifters cloak AND clawline ) |  | Verified | Super EpicGuy has a clip of doing this skip from the lower right exit to the wish ledge. Insane. |
| LM | lower to middle climb | lower right area | middle right ledge | silk soar  OR ( proficient movement AND hard enemy pogo AND spike pogo AND ( hard cocoon skip OR hard flintslate  stall OR hard flea brew stall OR hard plasmium stall ) AND cling grip AND drifters )  OR ( proficient movement AND medium enemy pogo AND spike pogo AND cling grip AND faydown cloak ) |  | Verified |  |
| LC | lower crossing | lower left area | lower right area | silk soar OR faydown OR medium scuttlebrace (due to risk of falling) OR ( ( ledge grab OR cling grip ) AND ( easy enemy pogo OR run OR dash OR clawline OR sharpdart x 2 OR drifters ) ) |  | Verified |  |
| LC | lower crossing | lower right area | lower left area | silk soar OR faydown OR medium scuttlebrace (due to risk of falling) OR easy enemy pogo OR run  OR dash  OR clawline  OR sharpdart x 1 OR drifters |  | Verified |  |
| BLL | bottom to lower left | bottom left area | lower left area | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| BLL | bottom to lower left | lower left area | bottom left area | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| moss grotto rosary cache | bottom left area | none |  | Verified | collectible |  |
| relic choral commandment moss grotto | middle right ledge | none |  | Verified | collectible |  |
| my missing courier wish granted | wish ledge | complete my missing courier wish promised IN belltown |  | Verified | event |  |
