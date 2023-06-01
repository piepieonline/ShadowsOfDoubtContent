todo

but for now, 

DDSLoader

A library used to load additional DDS and string content into ShadowsOfDoubt

README is TODO, but content can either be included in your own mod folder, or under AdditionalContent (Includes all community content by default). GUIDs must be unique. DDSContent must follow the same structure as the example/game.

Very manual process to create atm, but content can be verified using my DDS website (https://www.piepieonline.com/ShadowsOfDoubt-DDSViewer/).

IE
Shadows of Doubt\BepInEx\plugins\DDSLoader\AdditionalContent\NewSpam\DDSContent
or
Shadows of Doubt\BepInEx\plugins\NewSpam\DDSContent

Installation:

    Download BepInEx (BepInEx_UnityIL2CPP_x64_6.0.0-pre.1 specifically) from https://github.com/BepInEx/BepInEx/releases/download/v6.0.0-pre.1/BepInEx_UnityIL2CPP_x64_6.0.0-pre.1.zip
    Extract into the same folder as "Shadows of Doubt.exe".
    Run the game, load the main menu and quit.
    Copy the DDSLoader folder to "BepInEx\plugins\", so you should have (for example) ".\BepInEx\plugins\DDSLoader\DDSLoader.dll"

Code:
https://github.com/piepieonline/ShadowsOfDoubtMods/tree/master/DDSLoader