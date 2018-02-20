# OwnersCraft
Welcome to my personal Minecraft Modpack. It has been created for my old Youtube channel. Now I maintain this project only for fun
# Directories
As you can see you can find two directories: one for the client and one for the server. Download and use them always on separate folders, because they use some directories and files in common. You can find more details on the tree chart below
# Mods
This is the list of the mods. This list will update with the publish of new versions
* ArmorStatusHUD
* Extended Workbench
* ReiMinimap
* StatusEffectHUD
* Advanced Machines
* Ars Magica 2
* Applied Energistics
* AutoMiner
* Bob Gary's Growable Ores
* Backpack
* Bibliocraft
* Biomes o Plenty
* Buildcraft + 2 addons
* Chicken Chunks
* Computercraft
* Dartcraft
* Defense
* DenPipes with Emerald and Forestry
* Dye Trees
* Emasher Resource
* EnchantingPlus
* Ender Forest
* EnderIO
* EnderStorage
* Engineers Toolbox
* Equivalent Exchange 3 + Equivalency
* Extended Enchant
* Extra Utilities
* Factorisation
* Finder Compass
* Forestry + plugins
* GasCraft
* Geostrata
* HopperDuctsMod
* Industrial Craft 2 + Nuclear Control + Gravisuit
* Inventory Tweaks
* Iron Chest
* Logistics Pipes
* Mekanism
* Minefactory Reloaded
* Mystcraft
* Natura
* NEI
* Open Blocks + addons
* Optifine
* Power Converters
* Powersuits + addons
* PortalGun 2
* Project Bench
* Project Red
* QuarryPlus
* Railcraft
* Reactorcraft
* Readstone Armor
* Readstone Arsenal
* Rotarycraft
* Simply Jetpacks
* Soul Shards 2
* Tinkers Construct
* Thaumcraft
* Thermal Expansion
* Tree Capitator
* Twilight Forest
* Vein Miner
* Waila (What Am I Looking At)
* Mod loaders & libraries

# Installation
## Prerequisites
**Client and Server**

Download and install [Java version 1.7](http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase7-521261.html)

**Only Client**

Download and install [MultiMC](https://multimc.org/)

## Client
* Download the latest [version](https://github.com/RygarNelson/OwnersCraft/releases) of the client
* Do not extract the content. You need the entire .zip file
* Open MultiMC
* *(only if you have opened for the first time MultiMC)* Follow on-screen instructions
* Once you are on the main page, click on "*Add instance*" (on top-left of the program window)
* Click on "*Import Modpack (local file or link)*"
* Select the downloaded file (*Ownerscraft v**number***)
* Wait for decompression
* Double click on the created instance
* Log in to your Minecraft account
* *(optional)* Let the program download the libraries for Minecraft 1.6.4
* Now you can play!

## Server
* Download the latest [version](https://github.com/RygarNelson/OwnersCraft/releases) of the server
* Extract the content on a folder
* *(optional)* Modify **server.properties**
* Open the file **ownerscraft_server**
* Now you can play on the server!

# Tree folder
## Client
```
.packignore                           <-- Files for MultiMC
instance.cfg                          <-- Files for MultiMC
mmc-pack.json                         <-- Files for MultiMC

+---minecraft
|   |   options.txt                   <-- Options of Minecraft
|   |   optionsof.txt                 <-- Options of Minecraft
|   |
|   +---config                        <-- Configuration files of the mod
|   +---coremods                      <-- Libraries
|   +---liteconfig                    <-- Configuration files for the libraries
|   +---mods                          <-- All the mods and some libraries
|   +---resourcepacks                 <-- Texture packs for the client (new standard)
|   +---server-resource-packs         <-- Texture packs downloaded from the server
|   +---texturepacks                  <-- Texture packs for the client (old standard)

\---patches                           <-- Patches for MultiMC
```
## Server
```
eula.txt                              <-- Eula of Minecraft
minecraft_server.1.6.4.jar            <-- Standard server of Minecraft
ownerscraft_server.jar                <-- Server of OwnersCraft (launch this one!)
server.properties                     <-- Properties of the server

+---config                            <-- Configuration files of the mod
+---coremods                          <-- Libraries for the mods
+---libraries                         <-- Libraries for the server
+---liteconfig                        <-- Configuration files for the libraries
+---mods                              <-- All the mods and some libraries
```

# Changelog
*In theory, this changelog is useless, but I want you to keep track of changes of older versions*
## Version 1.1 
* Removed Immibis Microblocks mod. The game crashed when you were looking at the "Certius Quartz Ore" (Applied Energistics)
* Removed Herobrine
 
## Version 1.2 
* Fxed CodeChickenCore's file (Singleplayer/Multiplayer)
* Removed NEI and some config file from the server
* Removed Herobrine
 
## Version 1.3 
* Added mods: Millenaire, Dartcraft, EnderIO, Finder Compass, Mekanism, Minefactory Reloaded, Readstone Armory, Readstone Arsenal, Vein Miner
* Improved server stability
* Removed Herobrine

## Version 1.4
* Added mods: EnderStorage, Mystcraft, PowerSuits + addons
* Added 2 addons for Buildcraft
* Added Numina library
* Removed Millenaire: the server wouldn't be capable to load properly the configuration files
* Updated Extra Utilities, ProjectRed
* Improved client and server stability
* Removed Herobrine

## Hotfix 1.4.2
* Removed duplicated mods
* Fixed some server files that prevented to load the mods
* Removed Herobrine
