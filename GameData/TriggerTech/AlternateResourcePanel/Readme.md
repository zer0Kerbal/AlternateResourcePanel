<!-- Readme.md v1.1.4.0
Alternate Resource Panel (ARP)
created: 01 Oct 19
updated: 2020 04 10 -->
## Download on [SpaceDock][MOD:spacedock] or [Github][MOD:github] or [Curseforge][MOD:curseforge]. Also available on [CKAN][thread:ckan].  
***  
# ***A***lternative ***R***esource ***P***anel (ARP) by TriggerTech
## An alternate view of vessel resources plugin for [Kerbal Space Program][KSP:website]  
#### Adopted by [@zer0Kerbal][LINK:zer0kerbal], originally by [@TriggerAu][LINK:TriggerAu]  
![Mod Version][shield:mod:latest] 
![KSP version][shield:ksp] ![KSP-AVC][shield:kspavc] ![License MIT][shield:license] ![][LOGO:license]   
  
![SpaceDock][shield:spacedock] ![CKAN][shield:ckan] ![GitHub][shield:github] ![Curseforge][shield:curseforge]  
  
![Code][shield:code] ![Validate AVC .version files][shield:avcvalid]  
***
# Do not bother [@TriggerAu][LINK:triggerau] with anything concerning this.
  
***  
### Documentation / Manual
[Documentation Manual](
https://sites.google.com/site/kspalternateresourcepanel/home)  
### Preamble by [@TriggerAu][LINK:TriggerAu]: 
#### About
> Basically the Alternate Resource panel displays a view of resources in the current vessel with a bit more clarity. It also lets you see the remaining value  in the currently active stage for fuels as you fly - which is useful for asparagus staging.  
  
> It also has some Staging capabilities added so you can stage from map view and also have autostaging on ascent (tied it in because of the resources/last stage tie in)  
  
 The KSP Alternate Resource Panel is a plugin to the Kerbal Space program game and was created to provide me an alternate view of the resources list and also add some staging functionality to the map view.  
  
Basically installing this gives you an extra button labelled "Alternate" next to the Resources button in the top right corner. When you hover over it it will keep the panel displayed while the mouse is over any part of the panel, or if you click it it will be toggled on.  
  
It displays a list of all the resources that are present on your vessel with a bar graph of the amount on vessel and the amount remaining. It also has the following additional capabilities:   
![AlternateResourcePanel][IMG:hero:0]

- Displays stage amount/usage - so you can see how much fuel is left in your current stage, esp in an asparagus configuration - Now configure which side the stage is displayed on (*New in 2.4.1.0)
- Adjust the order and Grouping of the Resources so they display how you like - some can even be set to only show up when a threshold is passed - Now with Drag And Drop and Separator Inserts (*New in 2.3.0.0)
- Optionally displays the change rate (or instant consumption) values
- Optionally displays time till empty/full (*New in 2.2.0.0)
- Optionally hide a resource on empty (*New in 2.1.0.0) or on Full (*New in 2.2.0.0)
- Select Resources to see part windows and look at individual components
- Transfer Resources between parts - like the standard part windows (*New in 2.1.0.0)
- Add Alarms to get visual and Audio queues for what needs attention - even add your own sounds
- Maintains settings and visibility between vessel switches/restarts
- KAC style update checker added
- Movable and lockable panel
- Option of the KSP or Unity styles
- Ability to add icons by simply placing files in the right folder
- Ability for Modders to provide icons with their mod and have them display in KSPARP
- Ability to configure the order of preference for icon sets
- Ability to configure resources to hide on full/empty as well as cater to disabled flows for full vessel resources
- Ability to configure non-staging resources to show Active/Reserve values using the green/blue bars (*New in 2.2.2.0)
- Optional Staging facility with Ability to Activate Stages in Map View, and
- Ability to use Space Bar in Map view to activate stages - like in standard flight mode
- Autostaging Controller to activate stages on engine flameout (*New in 2.1.0.0)
- Now contains icons for resources from: Kethane, Deadly Reentry, Extra Planetary Launchpads, KSP Interstellar, Life Support By Bobcat, RealFues, Near Future, TAC Life Support
- API for information reading and alarm acknowledgement (*New in 2.1.0.0)

#### Currently is Feature Complete

### Heres some vision of the ARP in use - updated for 2.1   
  
[![][UTUBE:img:2]][UTUBE:url:2]  
  
[![][UTUBE:img:0]][UTUBE:url:0]  
  
[![][UTUBE:img:1]][UTUBE:url:1]  
  
https://youtu.be/7Zxh4SNLrBs  

Hopefully [@TriggerAu][LINK:triggerau] has built this simple enough that the pic below explains all you need... OK, we've moved past that point :) . The below will give you an eyeball at the main screen, but you will find the details on rest of the settings on the Documentation site linked below 
![AlternateResourcePanel][IMG:hero:1]

#### Player Created Icon Sets
-  [Icons by Olympic1 by Olympic1][thread:ARPI]
-  [Icon Set by pheonix_ca] and [IMGUR Gallery][IMGUR:url]  

# Network Connectivity Details

This Mod contains a version checker which can be managed and triggered from the About tab of the settings. It is configured to check once a day by default, and this check also can be disabled. The technical details of it are as follows:

- It will once a day download this page https://sites.google.com/site/kspalternateresourcepanel/latestversion to read the current up to date version number.
- It issues an HTTP GET - and sends no data
- It parses the response for the version tag and then notifies you if there is a more recent version is available
### Installation Directions:
- Use CKAN  
![][image:ckan]
### Changelog Summary
- *See [ChangeLog][MOD:changelog] for full details of mod changes*
### Known Issues
- *See [Known Issues][MOD:issues] for full details of feature requests, and known issues*
### Dependencies
- [x]  [Kerbal Space Program][KSP:website] [![][shield:ksp]][KSP:website] ***may*** work on other versions ]/YMMV/
### Recommends  
- [x]  [ARPIcons by @Olympic1][thread:ARPI]  
### Suggests
**By [zer0Kerbal][LINK:zer0Kerbal]**  
- [x]  [On Demand Fuel Cells {ODFC)}][thread:ODFC]  
- [x]  [Field Training Facility (FTF)][thread:FTF]  
- [x]  [Field Training Lab (FTL)][thread:FTL]  
- [x]  [Docking Port Descriptions(DPD)][thread:DPD]  
- [x]  [PicoPort Shielded (PPS)][thread:PPS]  
- [x]  [Transparent Command Pods Repressurized(TCP)][thread:TCP]  
- [x]  [Stork Delivery System (SDS)][thread:SDS]  
- [x]  [Biomatic][thread:BIO]  
- [x]  [B9 Stock Switches (B9S)][thread:B9S]  
- [x]  [*K*er*G*uise *E*ngineering e*X*perimental (KGX)][thread:KGX]  
- [x]  [Oh Scrap!][thread:OHS]  
- [x]  [ScrapYard][thread:SYD]  
- [x]  [DaMichel's AeroRadial][thread:DAR]  
- [x]  [DaMichel's CargoBays][thread:DCB]  
- [x]  [DaMichel's Fuselage][thread:DMF]  
- [x]  [DaMichel's Spherical Tanks][thread:DST]  
- [x]  [Stork Delivery System (SDS)][thread:SDS]  
- [x]  [SimpleConstructon!][thread:SC!]  
- [x]  [Not So SimpleConstructon!][thread:NSSC]  
- [x]  [Stack Inline Lights][thread:SIL]  
- [x]  [Stack Inline Light Patches][thread:SILP]  
- [x]  [KaboOom!][thread:BOOM]  
- [x]  [More Hitchhikers][thread:MHH]  
**Under construction**  
- [x]  [SimpleLife!][thread:SLF]  
- [x]  [SimpleDeadly!][thread:SDR]  
- [x]  [MoarKerbals!][thread:MK]  
- [x]  [Nuke Tiny Parts][thread:NUK]  
**Other wonderful mods**  
- [x]  [TweakScale][thread:twk]  
- [x]  [Module Manager][thread:mm]  
- [x]  [Community Resource Pack][thread:crp]  
### Supported Mods  
- [x]  [TweakScale][thread:twk]  
- [x]  [Kerbal Changelog][thread:kcl]  
### Conflicts
- [x]  none known
### Replaces
- [x]  [Alternate Resource Panel (original)][thread:arp]
### Tags
 - resource, skin, mod, ksp, plugin, mit, addon
### Downloads  
You can download the icons pack by clicking on one of the links:  
[![][image:github]][MOD:github] [![][image:spacedock]][MOD:spacedock] [![][image:curseforge]][MOD:curseforge]  
***  
*red box below is a link to forum post on how to get support*  
[![How to get support][image:getsupport]][thread:getsupport]
***  
### License
#### aka Legal Mumbo Jumbo
Source: [GitHub][MOD:github:repo]  
License: ![License MIT][shield:license] ![][LOGO:license]    
> *** All bundled mods are distributed under their own licenses***  
> *** All art assets (textures, models, animations) are distributed under their own licenses***   
### Original
Author: [@TriggerAu][LINK:TriggerAu]  
[Thread][MOD:original:thread]  
[Download][MOD:original:download]  
Source: [GitHub][MOD:original:source]  
License: ![License MIT][shield:license:original] ![][LOGO:mit] 
***
*Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date*

###### v2.9.5.0 original: 01 Oct 2019 zed'K | updated: 16 Mar 2020 zed'K

[MOD:license]:      https://github.com/zer0Kerbal/AlternateResourcePanel/blob/master/LICENSE
[MOD:contributing]: https://github.com/zer0Kerbal/AlternateResourcePanel/blob/master/.github/CONTRIBUTING.md
[MOD:wiki]:         https://github.com/zer0Kerbal/AlternateResourcePanel/
[MOD:issues]:       https://github.com/zer0Kerbal/AlternateResourcePanel/issues
[MOD:known]:        https://github.com/zer0Kerbal/AlternateResourcePanel/wiki/Known-Issues
[MOD:forum]:        https://forum.kerbalspaceprogram.com/index.php?/topic/192456-*
[MOD:github:repo]:  https://github.com/zer0Kerbal/AlternateResourcePanel/
[MOD:changelog]:    https://raw.githubusercontent.com/zer0Kerbal/AlternateResourcePanel/master/Changelog.cfg
[KSP:website]:      https://kerbalspaceprogram.com/ "Kerbal Space Program"  

[MOD:github]:    https://github.com/zer0Kerbal/AlternateResourcePanel/releases/latest "GitHub"  
[MOD:spacedock]: https://spacedock.info/mod/2403 "SpaceDock"  
[MOD:curseforge]: https://www.curseforge.com/kerbal/ksp-mods/alternateresourcepanel "CurseForge"  

<!--- original mod stuff -->
[MOD:original:source]:     https://github.com/TriggerAu/AlternateResourcePanel
[MOD:original:thread]:     https://forum.kerbalspaceprogram.com/threads/60227-* "ARP thread"  
[MOD:original:download]:   https://github.com/TriggerAU/AlternateResourcePanel/releases/latest
[shield:license:original]: https://img.shields.io/badge/license-MIT-red?style=plastic&labelColor=black "MIT"

<!--- license logo urls -->
[LOGO:license]:   https://i.postimg.cc/bvjfsMP5/MIT-17x17.png "MIT"  
[MOD:original:license:shield]: https://i.postimg.cc/bvjfsMP5/MIT-17x17.png "MIT"  
 
[image:github]:     https://i.imgur.com/RE4Ppr9.png "github"  
[image:spacedock]:  https://i.imgur.com/m0a7tn2.png "spacedock"  
[image:curseforge]: https://i.postimg.cc/RZNyB5vP/Download-On-Curse.png "curseforge"  
[image:dropbox]:    https:// "dropbox"  

[image:github:sm]:     https://i.postimg.cc/1XXy5yfD/github.png "github (small)"  
[image:spacedock:sm]:  https://i.postimg.cc/DZ22Hrhj/spacedock.png "spacedock (small)"  
[image:curseforge:sm]: https://i.postimg.cc/ZRVTSWKT/UVVt0OP.png "curseforge (small)"  

[shield:mod:latest]: https://img.shields.io/github/v/release/zer0Kerbal/AlternateResourcePanel?include_prereleases?style=plastic
[shield:mod]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/AlternateResourcePanel/master/json/mod.json
[shield:ksp]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/AlternateResourcePanel/master/json/ksp.json
[shield:license]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/AlternateResourcePanel/master/json/license.json

[shield:code]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/AlternateResourcePanel/master/json/code.json
[shield:kspavc]:     https://img.shields.io/badge/KSP-AVC--supported-brightgreen.svg?style=plastic
[shield:spacedock]:  https://img.shields.io/badge/SpaceDock-listed-blue.svg?style=plastic
[shield:ckan]:       https://img.shields.io/badge/CKAN-Indexed-blue.svg?style=plastic
[shield:github]:     https://img.shields.io/badge/Github-Indexed-blue.svg?style=plastic&logo=github
[shield:curseforge]: https://img.shields.io/badge/CurseForge-listed-blue.svg?style=plastic
[shield:avcvalid]:    https://github.com/zer0Kerbal/AlternateResourcePanel/workflows/Validate%20AVC%20.version%20files/badge.svg

[thread:mm]:  https://forum.kerbalspaceprogram.com/index.php?/topic/50533-* "Module Manager"   
[thread:kcl]: https://forum.kerbalspaceprogram.com/index.php?/topic/179207-* "Kerbal Changelog"  
[thread:twk]: https://forum.kerbalspaceprogram.com/index.php?/topic/179030-* "TweakScale"  
[thread:crp]: https://forum.kerbalspaceprogram.com/index.php?/topic/83007-* "Community Resource Pack"  

[thread:getsupport]: https://forum.kerbalspaceprogram.com/index.php?/topic/83212-* "Link to how to get support"
[image:getsupport]:    https://i.postimg.cc/vHP6zmrw/image.png "get support"  

[image:ckan]:  https://i.postimg.cc/x8XSVg4R/sj507JC.png "CKAN"  
[thread:ckan]: https://forum.kerbalspaceprogram.com/index.php?/topic/90246-* "CKAN"  
[image:ckan:sm]: https:// "CKAN (small)"  

[LINK:zer0Kerbal]:     https://forum.kerbalspaceprogram.com/index.php?/profile/190933-zer0kerbal/ "zed'K"  
[LINK:olympic1]: https://forum.kerbalspaceprogram.com/index.php?/profile/79730-olympic1/ "Olympic1"  
[LINK:triggerau]: https://forum.kerbalspaceprogram.com/index.php?/profile/57838-triggerau/ "TriggerAu"  
  
[UTube:img:0]: https://img.youtube.com/vi/mrWzFdsQBwY/0.jpg "click to watch"  
[UTube:url:0]: https://youtu.be/mrWzFdsQBwY "2.1.0.0 Panels"  

[UTube:img:1]: https://img.youtube.com/vi/7Zxh4SNLrBs/0.jpg "click to watch"  
[UTube:url:1]: https://youtu.be/7Zxh4SNLrBs "2.3.0.0 Drag and Drop"  

[UTube:img:2]: https://img.youtube.com/vi/i6aeXKR0YQ0/0.jpg "click to watch"  
[UTube:url:2]: https://youtu.be/i6aeXKR0YQ0 "Demo"  

[IMG:hero:0]: https://sites.google.com/site/kspalternateresourcepanel/images/PluginPic.png "ARP Hero"  
[IMG:hero:1]: https://sites.google.com/site/kspalternateresourcepanel/images/KSPARPMap.png "ARP Explained"  

<!-- zer0Kerbal mods -->
[thread:arp]: https://forum.kerbalspaceprogram.com/index.php?/topic/54876-* "Alternate Resource Panel"  
[thread:MK]:  https://forum.kerbalspaceprogram.com/index.php?/topic/191525-* "MoarKerbals!"   
[thread:BIO]: https://forum.kerbalspaceprogram.com/index.php?/topic/191426-* "Biomatic"  
[thread:B9S]: https://forum.kerbalspaceprogram.com/index.php?/topic/190870-* "B9 Stock Patches"   
[thread:DST]: https://forum.kerbalspaceprogram.com/index.php?/topic/191719-* "DaMichel's Spherical Tanks"  
[thread:DAR]: https://forum.kerbalspaceprogram.com/index.php?/topic/191719-* "DaMichel's AeroRadial"  
[thread:DCB]: https://forum.kerbalspaceprogram.com/index.php?/topic/191719-* "DaMichel's CargoBays"  
[thread:DMF]: https://forum.kerbalspaceprogram.com/index.php?/topic/191719-* "DaMichel's Fuselage"  
[thread:DPD]: https://forum.kerbalspaceprogram.com/index.php?/topic/192184-* "Docking Port Descriptions"
[thread:FTF]: https://forum.kerbalspaceprogram.com/index.php?/topic/188841-* "Field Training Facility"  
[thread:FTL]: https://forum.kerbalspaceprogram.com/index.php?/topic/188841-* "Field Training Lab"  
[thread:KGX]: https://forum.kerbalspaceprogram.com/index.php?/topic/192696-* "KGEx"  
[thread:MHH]: https://forum.kerbalspaceprogram.com/index.php?/topic/188246-* "More Hitchhikers"  
[thread:NUK]: https://forum.kerbalspaceprogram.com/index.php?/topic/21466-*  "Nuke Tiny Parts"
[thread:OHS]: https://forum.kerbalspaceprogram.com/index.php?/topic/192360-* "Oh Scrap!"  
[thread:PPS]: https://forum.kerbalspaceprogram.com/index.php?/topic/192187-* "Shielded PicoPort"  
[thread:SC!]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-* "SimpleConstructon!"  
[thread:SDS]: https://forum.kerbalspaceprogram.com/index.php?/topic/191719-* "Stork Delivery System (SDS)"    
[thread:SDR]: https:// "SimpleDeadly!"  
[thread:SL!]: https://forum.kerbalspaceprogram.com/index.php?/topic/191045-* "SimpleLogistics!"  
[thread:SLF]: https://forum.kerbalspaceprogram.com/index.php?/topic/191526-* "SimpleLife!"  
[thread:SIL]:  https://forum.kerbalspaceprogram.com/index.php?/topic/193050-* "Stock Inline Lights"  
[thread:SYD]: https://forum.kerbalspaceprogram.com/index.php?/topic/192360-* "ScrapYard"  
[thread:TCP]: https://forum.kerbalspaceprogram.com/index.php?/topic/187495-* "Transparent Command Pods"  
[thread:ARPI]: https://forum.kerbalspaceprogram.com/index.php?/topic/193078-* "ARPIcons"  
[thread:SILP]: https://forum.kerbalspaceprogram.com/index.php?/topic/193051-* "Stock Inline Lights Patches"
[thread:ODFC]: https://forum.kerbalspaceprogram.com/index.php?/topic/187625-* "On Demand Fuel Cells"  
[thread:NSSC]:  https://forum.kerbalspaceprogram.com/index.php?/topic/191504-* "Not So SimpleConstructon!"  
[thread:BOOM]: https://forum.kerbalspaceprogram.com/index.php?/topic/192938-* "KaboOom!"
<!--
this file: GPLv2
zer0Kerbal-->
