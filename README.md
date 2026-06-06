# SLR Weapon Skin
Weapon Skin And LAPD Skin


# How İnstall/Nasıl İndirilir

# Go here and paste this./buraya git ve yapıştır

# [qb]/qb-core/shared/items.lua

-- SLR CUSTOM WEAPONS
    weapon_fn509		     = {name = 'weapon_fn509', 			label = 'FN-509', 		        weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_beretta		     = {name = 'weapon_fn509', 			label = 'Beretta 92FS', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',       image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_ar15              = { name = 'weapon_ar15',          label = 'AR-15',                weight = 1000, type = 'weapon', ammotype = 'AMMO_RIFLE',        image = 'weapon_carbinerifle.png',  unique = true,      useable = false,    description = 'A light weight automatic rifle' },
    weapon_beanbag           = { name = 'weapon_beanbag',       label = 'BeanBag',              weight = 1000, type = 'weapon', ammotype = 'AMMO_SHOTGUN',      image = 'weapon_pumpshotgun.png',   unique = true,      useable = false,    description = 'A pump-action smoothbore gun for firing small shot at short range' },
    weapon_colt              = { name = 'weapon_colt',          label = 'Colt M4A1',            weight = 1000, type = 'weapon', ammotype = 'AMMO_RIFLE',        image = 'weapon_carbinerifle.png',  unique = true,      useable = false,    description = 'A light weight automatic rifle' },
    weapon_gtaser            = { name = 'weapon_gtaser',        label = 'Taser',                weight = 1000, type = 'weapon', ammotype = nil,                 image = 'weapon_stungun.png',       unique = true,      useable = false,    description = 'A weapon firing barbs attached by wires to batteries, causing temporary paralysis' },
    weapon_taser             = { name = 'weapon_taser',         label = 'Taser',                weight = 1000, type = 'weapon', ammotype = nil,                 image = 'weapon_stungun.png',       unique = true,      useable = false,    description = 'A weapon firing barbs attached by wires to batteries, causing temporary paralysis' },
    weapon_g17g4		     = {name = 'weapon_g17g4', 			label = 'Glock 17 Gen 4', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_gl26g5		     = {name = 'weapon_gl26g5', 		label = 'Glock 26 Gen 5', 	    weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_gl17g5		     = {name = 'weapon_gl17g5', 		label = 'Glock 26 Gen 5', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_gl18c		     = {name = 'weapon_gl18c', 			label = 'Glock 26 Gen 5', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_glock17hanami     = {name = 'weapon_glock17hanami', 	label = 'Glock 26 Gen 5', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},
    weapon_usp		         = {name = 'weapon_usp', 			label = 'USP', 		weight = 1000, type = 'weapon', ammotype = 'AMMO_PISTOL',		image = 'weapon_browning.png', 		unique = true, 		useable = false, 	description = 'VERY POWERFULL PISTOL!'},




   # [qb]/qb-core/shared/weapons.lua

   -- SLR CUSTOM WEAPONS
	[`weapon_fn509`] 			 = {['name'] = 'weapon_fn509', 		['label'] = 'FN-509', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_beretta`] 			 = {['name'] = 'weapon_beretta', 	['label'] = 'Beretta 92FS', 	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_ar15`] 		 	 = {['name'] = 'weapon_ar15', 	 	['label'] = 'AR-15', 		    ['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_beanbag`] 		 	 = {['name'] = 'weapon_beanbag', 	['label'] = 'BeanBag', 			['weapontype'] = 'Shotgun',	        ['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_colt`] 		 	 = {['name'] = 'weapon_colt', 	 	['label'] = 'Colt M4A1', 		['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_gtaser`]           = {  name   = 'weapon_gtaser',    label     = 'Taser',            weapontype     = 'Pistol',          ammotype =     'AMMO_STUNGUN',  damagereason     = 'Died' },
    [`weapon_taser`]           = {  name   = 'weapon_taser',    label     = 'Taser',            weapontype     = 'Pistol',          ammotype =     'AMMO_STUNGUN',  damagereason     = 'Died' },
	[`weapon_beanbag`] 		 	 = {['name'] = 'weapon_beanbag', 	['label'] = 'Remington M870', 			['weapontype'] = 'Shotgun',	        ['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_g17g4`] 			 = {['name'] = 'weapon_g17g4', 		['label'] = 'Glock 17 Gen 4', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_gl26g5`] 			 = {['name'] = 'weapon_gl26g5', 		['label'] = 'Glock 26 Gen 5', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_gl17g5`] 			 = {['name'] = 'weapon_gl17g5', 		['label'] = 'Glock 26 Gen 5', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_gl18c`] 			 = {['name'] = 'weapon_gl18c', 		['label'] = 'Glock 26 Gen 5', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock17hanami`] 			 = {['name'] = 'weapon_glock17hanami', 		['label'] = 'Glock 26 Gen 5', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_usp`] 			 = {['name'] = 'weapon_usp', 		['label'] = 'USP', 			['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},

    
    # [qb]/qbsmallresource/weapdrow.lua veya weapdraw.lua

    -- SLR CUSTOM WEAPONS
    'WEAPON_FN509',
    'WEAPON_BERETTA',
    'WEAPON_AR15',
    'WEAPON_GTASER',
    'WEAPON_TASER',
    'WEAPON_M870',
    'WEAPON_BEANBAG',
    'WEAPON_COLT',
    'WEAPON_G17G4',
    'WEAPON_GL26G5',
    'WEAPON_GL17G5',
    'WEAPON_GL18C',
    'WEAPON_GLOCK17HANAMİ',
    'WEAPON_USP',

    # [ox]/ox_inventory/data/weapons.lua 

    -- SLR CUSTOM WEAPONS
		['WEAPON_FN509'] = {
			label = 'FN-509',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_BEANBAG'] = {
			label = 'BeanBag',
			weight = 4400,
			durability = 0.05,
			ammoname = 'ammo-shotgun'
		},

		['WEAPON_AR15'] = {
			label = 'AR-15',
			weight = 3000,
			durability = 0.03,
			ammoname = 'ammo-rifle'
		},

		['WEAPON_BERETTA'] = {
			label = 'Beretta 92FS',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_GL17G5'] = {
			label = 'Glock 17 Gen 5',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_GL18C'] = {
			label = 'Glock 18C',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_GLOCK17HANAMİ'] = {
			label = 'Glock 17 Hanami',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_USP'] = {
			label = 'USP',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},
		
		['WEAPON_G17G4'] = {
			label = 'Glock 17 Gen 4',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_GL26G5'] = {
			label = 'Glock 26 Gen 5',
			weight = 2700,
			durability = 0.05,
			ammoname = 'ammo-9'
		},

		['WEAPON_COLT'] = {
			label = 'Colt M4A1',
			weight = 3000,
			durability = 0.03,
			ammoname = 'ammo-rifle'
		},

		['WEAPON_TASER'] = {
			label = 'Taser',
			weight = 227,
			durability = 0.1,
		},

		['WEAPON_M870'] = {
			label = 'Remington M870',
			weight = 4400,
			durability = 0.05,
			ammoname = 'ammo-shotgun'
		},

		['WEAPON_GTASER'] = {
			label = 'Taser',
			weight = 227,
			durability = 0.1,
		},