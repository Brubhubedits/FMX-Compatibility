> [!CAUTION]
> - **DO NOT RUN ANYTHING THAT WRITES TO THE NAND! YOU WILL BRICK YOUR CONSOLE!**
> - **Always use a non-Xbox Live account** when running homebrew and **do not connect to the internet.**
> - Homebrew that will result in your account and/or console being **almost definitely banned** from Xbox Live will be marked with 👤 if you attempt to connect to the internet/use an Xbox Live account.

> [!NOTE]
> - **Remember to patch your apps!** If necessary, follow one of the tutorials in the [Wiki](https://github.com/XDanfr/FMX-Compatibility/wiki) to ensure proper functionality.
> - Emulators are listed separately from homebrew. See [Emulators](#emulators)
> - DashLaunch plugins (e.g. Stealth servers, XBDM) don't work as it can't be installed.
> - If Homebrew is listed as `❌ Borked` or `⚠️ Partial` in a specific format, try converting via another method. It might work completely!! (This doesn't apply to DashLaunch)

### Regular Homebrew

| Homebrew Title          | Format | XexTool | Manual | No patching | Notes (Crashes, Fixes, Patches)                                                                                                                                           |
|-------------------------|:------:|:-------:|:------:|:-----------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Aurora                  |  XEX   |   ✅    |   ✅   |      ❌     | ~~Covers will not install if you are offline, so you'll have to use [Aurora Asset Editor](https://github.com/XboxUnity/AuroraAssetEditor/) and download covers manually.~~<br><br>(beta 4 and above only), you can now connect to the internet and the assets will be automatically downloaded from [XboxUnity](http://xboxunity.net). **NOTE: You still need to disconnect from the internet before running the exploit again** (Beta 5 and above), now the Aurora Guide Menu works as it should now  |
| DashLaunch              |  XEX   |   ⚠️    |   ⚠️   |      ❌     | **Do not install DashLaunch when prompted.** Runs, but is functionless at the moment. (Tested on beta 4)                                                                                                   |
| DOSBox                  |  XEX   |   ✅    |        |             | [Reported working](https://github.com/XDanfr/FMX-Compatibility/issues/45) by [Lowyk](https://github.com/Lowyk).                                                                                           |
| XeBoyAdvance            |  XEX   |   ✅    |        |             | v0.4.7 Works as expected (Tested on beta 5)                                                                                                                                                                       |
| Freestyle 3             |  XEX   |   ✅    |        |      ❌     | I tried the patched version of FSD 3 that fixes all bugs and it runs great. **Do not set it as the default dashboard.**                                                                                   |
| NXE2GOD                 |  XEX   |   ✅    |        |           | Turns your disc installed to the hard drive to a Game on Demand correctly.                                                                                                                                  |
| Simple 360 NAND Flasher |  XEX   |   ✅    |        |      ❌     | Successfully dumps your NAND to your Bad Update USB. **Obviously**, do not place an updflash.bin beside the homebrew's XEX or try to flash your NAND in any way.                                         |
| XeXmenu                 |  XEX   |   ✅    |   ✅   |      ❌     | Works as expected, no issues found :D (Tested on beta 3)                                                                                                                                                   |
| XeLL                    |  bin   |         |        |      ✅      | Get your XeLL .bin files and FreeMyXe should recognise them and ask you if you want to boot it.                                                                                                          |
| XM360                   |  XEX   |   ✅    |        |             | XBLA Games and DLC can be unlocked using XM360. **NOTE: This will prevent them from launching without being in a modded state, so back up your Games before unlocking.**                                 |

### Emulators
| Emulator Title          | Format | XexTool | Manual | No patching | Notes (Crashes, Fixes, Patches)                                                                                                                                           |
|-------------------------|:------:|:-------:|:------:|:-----------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GenesisPlus360 👤       |  XEX   |   ✅    |        |             | Runs ROMs with no issue, need to change the rom folder's location if needed. **NOTE: the Emulator has a Achievement system so you must be using an offline account if using the emulator, as it will most likely make your console or account get banned if online.**                                      |
| Modded Xefu Emulator    |  XEX   |         |        |      ✅      | Remember to Run "OGXboxPrep.xex" to play your OG Xbox Game, replace the original compatibility folder From HddX: to allow you to run Backup, for a compatibily list of the games, use this [Site](https://consolemods.org/wiki/Xbox_360:Original_Xbox_Games_Compatibility_List#Compatibility_List) |
| Snes360 👤              |  XEX   |   ✅    |        |             | Runs ROMs with no issue. **NOTE: You immediately receive an achievement as soon as you launch the emulator with a profile logged in, and will most likely be why your console or account is banned if you run the emulator on an Xbox Live-enabled profile.**                                                |

| Status | Meaning |
|--------|---------|
| ✅ Works | Fully functional with no issues. |
| ⚠️ Partially | Works, but has glitches or requires fixes. |
| ❌ Borked | Does not work or crashes. |
| 👤 Offline | Only use an offline account (not Xbox Live) to prevent a ban. |
