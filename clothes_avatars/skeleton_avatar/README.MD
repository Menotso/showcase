- Doesn't have eq_chest;
- 1.564 verts / 2.988 polys; and
- 3 known issues in the joints.

man01.xml:
```xml
	<AddParts name="parts152" filename="man-parts_skel.elu" autoload="true"> </AddParts>
```

zitem.xml:
```xml
  <ITEM id="306" name="Skeleton Hands" mesh_name="eq_hands_skel" totalpoint="0" type="equip" res_sex="m" res_level="0" slot="hands" weight="4" bt_price="0" hp="0" ap="8" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" desc="Spooky Hands" elu="man-parts_skel.elu" />
  <ITEM id="307" name="Skeleton Legs" mesh_name="eq_legs_skel" totalpoint="0" type="equip" res_sex="m" res_level="0" slot="legs" weight="4" bt_price="0" hp="0" ap="8" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" desc="Spooky Legs" elu="man-parts_skel.elu" />
  <ITEM id="308" name="Skeleton Head" mesh_name="eq_head_skel" totalpoint="0" type="equip" res_sex="m" res_level="0" slot="head" weight="4" bt_price="0" hp="0" ap="8" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" desc="Who are you scaring today?" elu="man-parts_skel.elu" />
  <ITEM id="309" name="Skeleton Feet" mesh_name="eq_feet_skel" totalpoint="0" type="equip" res_sex="m" res_level="0" slot="feet" weight="4" bt_price="0" hp="0" ap="8" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" desc="Spooky Feet" elu="man-parts_skel.elu" />
```

shop.xml
```xml
<SELL itemid="306"/> <!-- [CUSTOM] spooky hands-->
<SELL itemid="307"/> <!-- [CUSTOM] spooky legs-->
<SELL itemid="308"/> <!-- [CUSTOM] spooky head-->
<SELL itemid="309"/> <!-- [CUSTOM] spooky feet-->
```
