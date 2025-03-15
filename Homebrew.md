> [!CAUTION]
> - **DO NOT RUN ANYTHING THAT WRITES TO THE NAND! YOU WILL BRICK YOUR CONSOLE!**
> - **Always use a non-Xbox Live account** when running homebrew and **do not connect to the internet.**
> - Homebrew that will result in your account and/or console being **almost definitely banned** from Xbox Live will be marked with 👤 if you attempt to connect to the internet/use an Xbox Live account.

> [!NOTE]
> - **Remember to patch your apps!** If necessary, follow one of the tutorials in the [Wiki](https://github.com/XDanfr/FMX-Compatibility/wiki) to ensure proper functionality.
> - Emulators are listed separately from homebrew. See [Emulators](#emulators)
> - DashLaunch plugins (e.g. Stealth servers, XBDM) don't work as it can't be installed.
> - > - If Homebrew is listed as `❌ Borked` or `⚠️ Partial` in a specific format, try converting via another method. It might work completely!! (This doesn't apply to DashLaunch)

### Regular Homebrew

| Homebrew Title          | Works? | Method | Notes (Crashes, Fixes, Patches)                                                                                                                                           |
|-------------------------|:------:|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Aurora                  |   ✅   | Xex/Man | Covers will not install if you are offline, so you'll have to use [Aurora Asset Editor](https://github.com/XboxUnity/AuroraAssetEditor/) and download covers manually.<br><br>(beta 4 and above only), you can now connect to the internet and the assets will be automatically downloaded from [XboxUnity](http://xboxunity.net). **NOTE: You still need to disconnect from the internet before running the exploit again**                                                                                                                                                                                                                 |
| DashLaunch              |   ⚠️   | Xex/Man | **Do not install DashLaunch when prompted.** Runs, but is functionless at the moment. (Tested on beta 4)                                                                 |
| Freestyle 3             |   ✅   | XexTool | I tried the patched version of FSD 3 that fixes all bugs and it runs great. **Do not set it as the default dashboard.**                                                  |
| Simple 360 NAND Flasher |   ✅   | XexTool | Successfully dumps your NAND to your Bad Update USB. **Obviously**, do not place an updflash.bin beside the homebrew's XEX or try to flash your NAND in any way.         |
| XeXmenu                 |   ✅   | Xex/Man | Works as expected, no issues found :D (Tested on beta 3)                                                                                                                 |
| XeLL                    |   ✅   |   N/A   | Get your XeLL .bin files and FreeMyXe should recognise them and ask you if you want to boot it.                                                                          |
| XM360                   |   ✅   | XexTool | XBLA Games and DLC can be unlocked using XM360. **NOTE: This will prevent them from launching without being in a modded state, so back up your Games before unlocking.** |

### Emulators
| Emulator Title          | Works? | Method | Notes (Crashes, Fixes, Patches)                                                                                                                                           |
|-------------------------|:------:|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GenesisPlus360                 |   ✅ 👤   | XexTool | Runs ROMs with no issue, need to change the rom folder's location if needed. **NOTE: the Emulator has a Achievement system, must be offline if using the emulator, as will most likely make your console get banned if online**                                                                                                                                                       |
| Modded Xefu Emulator    |  ✅  | None | Remember to Run "OGXboxPrep.xex" to play your OG Xbox Game, replace the original compatibility folder From HddX: to allow you to run Backup, for a compatibily list of the games, use this [Site](https://consolemods.org/wiki/Xbox_360:Original_Xbox_Games_Compatibility_List#Compatibility_List)                                                                                                            |
| Snes360                 |   ✅ 👤   | XexTool | Runs ROMs with no issue. **NOTE: You immediately receive an achievement as soon as you launch the emulator with a profile logged in, and will most likely be why your console is banned if you run the emulator on an Xbox Live-enabled profile.**                                                                                                                                                       |
