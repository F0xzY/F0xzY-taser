
## es_extended\shared\config\weapons.lua
![](https://i.imgur.com/SiVi0Nb.png)
    {
        name = "WEAPON_STUNGUN",
        label = TranslateCap("weapon_stungun"),
        ammo = { label = TranslateCap("ammo_rounds"), hash = `AMMO_TASER` },
        tints = Config.DefaultWeaponTints,
        components = {},
    },


## ox_inventory/data/weapons.lua / Indsæt linje 18 til stungun item'et. 
![](https://i.imgur.com/SC9pegZ.png)

        ['WEAPON_STUNGUN'] = {
			label = 'Stungun',
			weight = 227,
			durability = 0.1,
			ammoname = 'ammo-taser'
		},


## ox_inventory/data/weapon.lua / Tilføj "ammo-taser" 
![](https://i.imgur.com/J1ykvsM.png)

        ['ammo-taser'] = {
			label = 'Taser Cartridges',
			weight = 3,
		},
