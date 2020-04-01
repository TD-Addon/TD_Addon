# TD_Addon
This repostiory is an experimental global data-addon for Tamriel_Data (current version 7.1). Using this repository, Tamriel_Data curators can directly comit new assets and plugins directly to the addon, which can then be instantly compiled as a BAIN-aware mod-package for mod developers using Tamriel Data.  

Contributors/users are notified of any new comits to the data addon repository via chatops: when a comit is pushed, a summary is published to a discord channel via webhooks. Notifications are currently pritned here: https://discord.gg/J3AtqMq. Several chanels may use a single webhook.



## New Features:
-Both TR and PT data within a single esp.
-TR and PT data within two seperate folders, but a single archive. This adheres to the seperation of PT and TR's BSAs within Tamriel Data.
-Optional HD asset overrides for both TR and PT. Vanilla-resolution textures and models are the default, with HD versions being optional. This signficantly de-bloats the TR addon folder, which previously contained 2 of every asset between a SD and a HD folder, even when there when there was no disparity between the assets.



## Contributing as an Author:
Via the use of the website and Github desktop, desginated authors can push new/edit assets and new .esp files directly to the repo. Those additions can be pushed either to an indev[WIP] branch, or the master branch (this is a bit situlational, and depends on the intents of the user)

### Current Authors:
Wollirollo
Cheflul



## Contributing Via Push Requests:
None-authors can also contribute new assets/esps. Their comits will not be pushed unless accepted by a designated author. This has the potential to circumnavigate our current review system, and iss therefore sub-optimal. However, it could be useful for pushing small fixes to assets that need not go through the asset browser (fixing a collision, texture path, model topology or mising mip-maps, for example). 



## Compiling and Using the TD_Addon:
Devs using Tamriel Data as a master are able to use this repository to quickly compile the latest addons. By clicking download, the entire repository is downloaded as a BAIN-aware zip file, which can be installed as a package via Wrye Mash or Mod Organiser 2. No manual installation is required. It's as easy as downloading straight to your installers folder, and clicking install.
