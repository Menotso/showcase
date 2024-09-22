weapon.xml:
```xml
<AddWeaponElu name="hammer" weapon_motion_type = "1" weapon_type = "1" >
    <AddBaseModel name="hammer" filename="model/weapon/katana/custom/hammer.elu" />
</AddWeaponElu>
```
zitem.xml:
```xml
<ITEM id="301" name="Bionic Hammer" mesh_name="hammer" totalpoint="0" type="melee" res_sex="a" res_level="0" slot="melee" weapon="katana" weight="10" bt_price="0" delay="359" damage="8" range="220" ctrl_ability="0" magazine="0" reloadtime="0" slug_output="false" gadget_id="0" hp="0" ap="0" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" image_id="0" bullet_image_id="0" magazine_image_id="0" desc="Boink!" />
```
shop.xml:
```xml
<SELL itemid="301"/> <!-- [CUSTOM] hammer-->
```