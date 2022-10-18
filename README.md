# Useful-Tools
A place to put any useful little scripts/tools you would like to share here.

If you would like to contribute, and are not a member of the organisation, please contact me (Buckminsterfullerene#6666) on Discord so I can send you an invite.

If you are a member of the org, please make a folder to categorise what your script does and add a readme inside that explains how to use it/them (if not already inside the scripts).

### Items:
* [Empty Content Hierarchy](https://github.com/Foxhole-Modding/Useful-Scripts/blob/main/Empty%20Content.zip) - Created by Buckminsterfullerene
  - All the game's folders without any files in them
  - Saves you from having to spend time manually recreating folders for your mod, as any empty folders in the pak file has no effect on the game
  - Batch command to create this is just `DEL "path to unpacked files\*.*" /S /Q`
* [UnrealPaker4.24](https://github.com/Foxhole-Modding/Useful-Scripts/blob/main/UnrealPacker4.24.zip) - Created by Buckminsterfullerene
  - Extracted UnrealPak.exe binaries from UE4.24 for easy unpacking and packing mods
  - To unpack, simply drag 'n drop the pak file onto _Unpack.bat
  - To pack, put your mod's Content folder inside of the Input folder (e.g. Input/Content/Maps/...) and drag 'n drop the Input folder onto _Repack.bat
