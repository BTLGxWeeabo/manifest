BTLG x Weeabo | Onichann (Android 10) sources
========

To initialize your local repository, use this command:

	repo init -u https://github.com/BTLGxWeeabo/manifest.git -b queso

Then, be sure to add your device manifest in your local_manifests folder and finally, do:

	repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -jx
	(the x on jx it's the amount of cores you have)
	
When everything is done, be sure to shishufy your device (prepare it with the bootleg.mk file and bootleg_device product and stuff, that generic thing) and then when you're ready you can:

	source build/envsetup.sh
	lunch bootleg_device-userdebug
	mka bacon -jxxxxx
	
	(where it says device, it's your device codename. And you can use mka bacon ~~or mka bootleg~~, it's all up to you.)

Thanks section
--------------
Here's my thanks to people who made this possible:

* Shishu (For being there)
* Ground Zero ROMs Team
* AOSPExtended
* ABC ROMs
* NitrogenOS
* AICP
* DirtyUnicorns
* Lukas Koller (Camera Roll dev)
* fxckingdeathwish (for the amazing photos for wallpaper/headers)
* OmniROM
* CyanogenMod/LineageOS
* PixelExperience
* PureNexus
* merothh
* Resurrection Remix
* AOSiP
* CrDroid
* CypherOS
* PureKat
* theimpulson
* MatiHalperin
* Project Xtended
* Pixeldust Project
* AquariOS
* Alejandro Ponce (Quetzal/Calypso dev)
* PixysOS 
* ArrowOS
* BlissROMs
* The Memedo Testers team
* The weeabo.ppl
