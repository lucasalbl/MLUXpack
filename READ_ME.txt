Heya! This is the "official" modpack of the MLUX server. Most of these mods are simply replacements for optifine, so things like better looking grass, connected textures and most importantly way better performance (even better than optifine!). This pack also includes SimpleVoiceChat and it will be expanded with any future mods we might add to the server. Why release this as a modpack instead of just linking people to the mods? Because curseforge is an annoying website and it's very easy to accidentally end up installing the wrong version of a mod (especially for SimpleVoiceChat!), so we release this pack as "tried and tested" for our server.

INSTRUCTIONS:
1. Open fabric-installer-0.10.2.jar (if it doesn't open, drag it out of this folder, into your downloads and try again).

2. Change minecraft version from 1.18.2 to 1.18.1.

3. Press install.

4. Open up the minecraft launcher.

4. To the left of the play button it should say "fabric-loader-1.18.1". If it doesn't, try clicking on what it is saying (probably something like "Latest release") and change it over to the fabric loader.

5. Start minecraft.

6. When minecraft has started to the main menu, quit the game. This is needed for the fabric loader to initialise some files and folders it needs.

7. locate your mods folder. For Windows this should be in "%appdata%\.minecraft\" (remove the quotes and enter this in explorer). For MacOS it is in "~/Library/Application Support/minecraft". Press cmd+shift+G when in finder and paste the text between the quotes.

8. Copy all the mods from the "MLUXmods" folder to the "mods" folder in minecraft.

9. Start the game again.

10. This step will be for MacOS users only. Due to the permissions system on MacOS the SimpleVoiceChat mod will have to make adjustments to minecraft itself, so it can access the microphone. This will involve a window popping up, to which you must drag the minecraft launcher icon from the applications folder in finder. It should then automatically patch the game, so that it will correctly ask for microphone permissions.

10. Note 1: When starting minecraft the game will ask for access to your keychain. This is because the change made by the mod has invalidated the game's "signature" which means it isn't being recognised as minecraft anymore. To make these popups stop appearing you need to enter your computer's password and press "always allow". Note that you will probably get some more of these popups (around six I think), as Mojang has multiple keys stored in the keychain, and each one needs to be allowed access to individually. Just keep entering your password and pressing "always allow" and they will seize after a while.

10. Note 2: If after patching the launcher it asks you to patch again once you restarted the game you might have to delete the games signature manually. To do this follow these steps:

10.1 Shut down any instance of minecraft or the minecraft launcher.

10.2 Press cmd+space, type terminal and press enter.

10.3 paste "codesign —-force --deep --sign - ". Do not press enter yet!

10.4 Go to your applications folder in finder, right click on minecraft and hold alt (option). You should see copy change into copy "Minecraft" as Pathname. Click on this.

10.5 Go back to terminal and press cmd+V to paste the path into the command. Press enter. There should be no obvious effect.

10.6 Boot up minecraft and it should work fine now.

11. Go play minecraft! If you get any errors, or you don't understand a part of this guide, leave a message in the discord. Both a message in general or a DM to an admin are acceptible.

Credits:
We obviously didn't create the mods ourself, so what will follow is a link to every mod included in this pack. If you are wondering what a mod does you can follow the link and read the description on the website.

https://www.curseforge.com/minecraft/mc-mods/enhanced-block-entities
https://www.curseforge.com/minecraft/mc-mods/dark-loading-screen
https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights
https://www.curseforge.com/minecraft/mc-mods/lambdabettergrass
https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat
https://www.curseforge.com/minecraft/mc-mods/entityculling
https://www.curseforge.com/minecraft/mc-mods/raised-clouds
https://www.curseforge.com/minecraft/mc-mods/logical-zoom
https://www.curseforge.com/minecraft/mc-mods/cloth-config
https://www.curseforge.com/minecraft/mc-mods/clear-skies
https://www.curseforge.com/minecraft/mc-mods/dynamic-fps
https://www.curseforge.com/minecraft/mc-mods/cull-leaves
https://www.curseforge.com/minecraft/mc-mods/continuity
https://www.curseforge.com/minecraft/mc-mods/starlight
https://www.curseforge.com/minecraft/mc-mods/lithium
https://www.curseforge.com/minecraft/mc-mods/lazydfu
https://www.curseforge.com/minecraft/mc-mods/modmenu
https://www.curseforge.com/minecraft/mc-mods/sodium
https://modrinth.com/mod/ferrite-core
https://modrinth.com/mod/fabric-api
