# How to use the Template
This folder structure demonstrates how to structure the folders in order to create a working pak patch file.
Inside the nested folders, there's a Game.locres file which you have to edit with the localizations tool: https://github.com/amrshaheen61/UE4LocalizationsTool/releases/tag/v1.8

This example setup creates a patch that overwrites the default English localization. You can use it to create localizations for languages that aren't added to the Master patch (yet).

I recommend renaming the topmost folder to say the language you added instead of "GENERIC". It will however conflict with any other pak that alters the default English localization and overwrite the English text in the game.

You have to use unrealpak to turn the folder into a .pak file that the game can read: https://github.com/RiotOreO/unrealpak