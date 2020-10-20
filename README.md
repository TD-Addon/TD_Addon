# TD_Addon
This repository serves as a single location for progressively aggregating new assets as an extention of the 'Tamriel_Data' database (current version 7.1). Using this repository, Tamriel_Data curators can directly commit new assets and plugins directly to the addon, compling new data and assets in prepertion for the next Tamriel_Data version (currently v9). This repository can also be instantly compiled as a BAIN-aware mod-package for developers use in conjuction with Tamriel Data in order to access new addon-only components.

Tamriel Data is available on the Nexus-> https://www.nexusmods.com/morrowind/mods/44537

Contributors/users are notified of any new commits to the data addon repository via chatops: when a commit is pushed, a summary is published to the Tamriel_Data discord channel. Notifications are currently printed here: https://discord.gg/J3AtqMq. Several channels may use a single webhook. 



## New Advantages:
- Both TR and PT data within a single esp.
- TR and PT data within two separate folders, but a single archive. This adheres to the separation of PT and TR's BSAs within Tamriel Data.
- Optional HD asset overrides for both TR and PT. Vanilla-resolution textures and models are the default, with HD versions being optional. This significantly de-bloats the TR addon folder, which previously contained 2 of every asset between a SD and a HD folder, even when there when there was no disparity between the assets.
- Wolli's incrementally updated TR deprecated asset .esp, which reassigns several assets a new placeholder/deprecated marker models, indicating to devs that the asset needs removing from the worldspace/section files. A full list of assets can be found here: https://docs.google.com/spreadsheets/d/1D4R_OZ-d0BARNkwyif1W5j03O4-AuajVV9LIFHaXwqI/edit?usp=sharing



## Contributing as an Author:
Via the use of the website and Github desktop, designated authors can push new/edit assets and new .esp files directly to the repo. Those additions can be pushed either to an indev[WIP] branch, or the master branch (this is a bit situational, and depends on the intents of the user)

### Current Authors:
- Wollirollo
- Cheflul
- Atrayonis
- Cicero
- Evil Eye



## Contributing Via Push Requests:
Non-authors can also contribute new assets/esps. Their commits will not be pushed unless accepted by a designated reviewer. This has the potential to completely circumnavigate our current asset browser review system, and is therefore something we really, REALLY do not want to use. However, it could be useful for pushing small fixes to assets that need not go through the asset browser (fixing a collision, texture path, model topology or missing mip-maps, for example). 



## Compiling and Using the TD_Addon:
Devs using Tamriel Data as a master are able to use this repository to quickly compile the latest addons. By clicking download, the entire repository is downloaded as a BAIN-aware zip file, which can be installed as a package via Wrye Mash or Mod Organiser 2. No manual installation is required. It's as easy as downloading straight to your installers folder, and clicking install.


## Mods using Tamriel Data:
- Tamriel Rebuilt -> https://www.nexusmods.com/morrowind/mods/42145
- Skyrim Home of the Nords -> https://www.nexusmods.com/morrowind/mods/44921
- Province: Cyrodiil -> https://www.nexusmods.com/morrowind/mods/44922
- Solstheim: Tomb of the Snow Prince -> https://www.nexusmods.com/morrowind/mods/46810



**Wolli**
