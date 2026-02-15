If these tools or dats help save you time or assist in your own preservation efforts, consider supporting the work:

<a href="https://buymeacoffee.com/eggmansworld">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" height="45" alt="Buy Me a Coffee">
</a>


# Eggman’s Arcade Repository 
Current Archive Size: ~20.5TB  
Number of files: 39,594,092

## Overview
Eggman’s Arcade Repository is a **preservation project** that archives arcade games to ensure their long-term retention. There are still thousands of games not yet emulated, but have been made available and are just floating around out there in the digital world. The goal is to provide a central archive where the files can survive long-term, even as forums, websites, and chatrooms disappear. 

⚠️ **Disclaimer:**  
This repository is for archival and preservation purposes only.  
No guarantees are made regarding playability, accuracy, or completeness.  
Use at your own discretion.  
Datfiles are only designed and tested for use with [RomVault](https://www.romvault.com). These dats may not work in other rom managers.

---

## Features
- A wide variety of arcade game dumps, old and new.
- Games in mixed states:
  - Some with pre-existing loaders.
  - Some in a playable state.
  - Many as raw dumps, system restore discs or hard drive file copies without emulator support.
- Proprietary hard drive formats (e.g., `.mrimg`) converted where possible into generic `.img` files. (Some conversions may still be pending, such as .GHO)
- Content inherited from older abandoned collections (e.g., Yori’s).
- Heavy representation of **rhythm/Bemani games**, though completeness is not guaranteed.

---

## Exclusions
This collection tries very hard not to include duplicate arcade-related materials already included in sets from:
- **Redump**
- **No-Intro**  
- **Sega ALL.Net** (DataMonster/datjohn)  
- **TeknoParrot**  
- **MAME** 

These projects already have their own maintainers and these other sets should be collected separately. 

---

## ⚠️BEFORE LOADING THESE DATS IN ROMVAULT⚠️

This arcade repo is large and resource-intensive. **It is not intended for low-memory systems.**

## If you are planning on loading the ENTIRE arcade repo collection into RomVault, please note the following:

This is an example showing only the repo dats fully loaded into an RV instance (no other dats included):

<img width="608" height="76" alt="image" src="https://github.com/user-attachments/assets/4d2c8cc7-c786-40a9-befc-a552064a0e7d" />


You should have at least 48GB of RAM to use these DAT files properly. RomVault loads the entire DAT cache into memory, and a scan or fix operation can drive the RAM usage up even higher. If your system does not have enough physical RAM available, Windows will move part of that data to the pagefile (virtual memory on disk). The pagefile is significantly slower than real RAM — even on fast NVMe drives. When this happens, you may notice:
- Slower cache updates
- Slower "Find Fixes" operations
- General performance degradation

If your RAM usage is regularly hitting 90% or higher during RomVault operations, you do not have sufficient headroom, and performance will suffer.

In short: this collection expects workstation-class memory, not casual desktop specs.

---

## EXTRAS Folder Overview
Why the heck is it so large? Well, this folder is designed to separate out content that would otherwise clutter up the core game repository, such as:
- **Artworks** - bezels, flyers, magazines, marquees, stuff for LaunchBox and MAME
- **Loaders** - various game loaders used to run some of the repo content
- **Manuals**
- **Manufacturers** - various items such as artwork, tools/utilities, executables
- **Patches** - sorted by game - quite a bit pertains to TeknoParrot but there is a good amount of other loader content
- **PC Collections** - collections based on arcade games with a frontend
- **PC Related Works** - game derivatives based on or part of a game series that were only released on the PC platform
- **PC Related Works Rhythm** - PC games based on rhythm-style arcade gameplay
- **Rhythm Community** - beatoraja and BMS community-based collections.
- **TeknoParrot** - content pertaining to TPUI content and settings
- **Touchscreen** - PC-based touchscreen content
- **Tutorials** - knowledge-based stuff
- **Utilities** - apps and tools related to arcade games
- **Vending, Kiosks** - why not.

---

## Current Status
- **Testing:** None of the dumps here are guaranteed tested or working, other than the ones indicated as "working" via a loader or emulator.  
- **Duplicates:** Efforts are made to bring dupes down to a bare minimum.  
- **Ongoing Work:** This repository is *always* a work in progress. Files may change, be replaced, or reorganized over time.  

---

## Goals
- Preserve arcade data in a sorted and curated condition.  
- Reduce the risk of rare dumps disappearing as communities shut down or contributors disappear.  
- Provide a base for others to build on (e.g., loaders, fixes, and emulation work).  

---

## File Legend
(w) = Working. A game can be setup with a loader, tested and working up to in-game play (if possible).  
(nw) = Not Working. A loader exists and I attempted to setup and test the game, and the game is not working. Does not mean the game could be working at a later date. I do not recheck games very often.  
(S2x) = Spice2x, a maintained and updated derivative of Spicetools.  
(standalone) = the game has its own unique loader, or can be run by its own exe.  
(SRD) = System Restore Disc  
(vhd) = vhd containers, some are browsable with 7zip or mountable. some may be encrypted and non-browsable.  
(exe) = game executables  
(opt) = option files (Sega ALLS)  
(app) = application files (Sega ALLS)  

## (unpacked) vs (extracted)
These two tags were the toughest to initially assign. The terms "unpacked" and "extracted" describe completely separate methods of how the game files were accessed on the original media they were contained in. The tags do NOT describe the state of the files themselves.

The tags, from my point of view, mean this:

**unpacked** = the file contents were unpacked from their original container/drive/image/dump and required intervention by 3rd party tools via:
	- decryption at the drive/partition layer
	- de-enveloping of executables
	- deobfuscation of game files
	- HASP or dongle information to perform any of the aforementioned tasks

**extracted** = the physical game files can be extracted out of its container without the need for 3rd party intervention. An example would be extracting the contents of an unprotected hard drive image. This does NOT mean the game files are usable. A typical scenario would be the game vendor uses a physical security dongle as its method of run-time protection and without it, the game will not function.

At this point in the early stages of the repo's life, I've made the general assumption that a "folder of game files" are tagged with "unpacked" until it can be determined what method was used to obtain the files. It will take considerable time to dig into each game and figure out exactly what tag category the archives belong in. If you're an expert on this sort of thing and want to submit corrections in this regard, I would be more than happy to receive your help!

To many of you, the use of either "unpacked" or "extracted" tags simply means the archive contains only game files, and not the original media they came from (most likely SRD or HDD images).

---

## How to Contribute
Contributions are always welcome! Ways you can help:
- **Cleanup & Curation** – Identify broken/useless files and suggest removals.  
- **Rhythm/Bemani Expertise** – These are notoriously painful to manage. If you’re knowledgeable, please share your insight.  
- **New Dumps** – Share material to grow the collection for future preservation.  
- **Playability** – Share loaders, tools, or guides that make certain games playable.  

👉 If you have something to add, feel free to open an issue, submit a pull request, or reach out directly.  

---

## Direct notes to the arcade community:
- This repo will **never be finished**.  
- This repo will get updated when I feel it deserves an update.
- There is still a massive amount of arcade material out there that isn’t included. If you have access to it—**don’t sit on it. Share it. Preserve it.**  
- this is MY repo, so I do things how I like them to be done.
- If you don't like something that is included in it, ignore it.
- I do not judge what gets added to the repo. If you don't like rhythm or redemption games, nobody's forcing you.
- If you think something is broken, provide a solution on how to fix it.
- If you think something needs to be changed in the repo (game in wrong place, wrongly tagged files, etc), submit an issue on github and validate your claim with details and proof.
- DO NOT BOTHER ME ABOUT TEMP FILES. For this repo, it is NOT about cleaning up games. Especially log and temp files! These files could provide valuable running details about the system before the power plug was pulled on it.
- There are empty placeholder folders for some games. Find me something to put in them!
- Game dumps are provided AS-IS, and almost always exactly AS-FOUND.
- don't bother me about "You don't you have XX game" or "do you have YY game" or "how do I setup ZZ game". 
	- If it's not in the dats, it's not in the repo. If games are not made available to me, I can't add them.
	- I'm not your tour guide - games are separated by manufacturer, system and game.
	- Do your own setup homework, join communities, use search engines and AI. Explore and learn.

---

## Acknowledgments
Thanks to the following for their indirect contributions (with or without permission):  
- **Archive.org**  
- **TFK**  
- Arcade Freaks (touchscreen content)  
- **Yori Yoshizuki**  
- nameless websites, forums and trackers
- anonymous benefactors
- numerous individuals who have provided continued assistance from the shadows.

---

## Licensing

Original source code, scripts, tooling, and hand-authored documentation and
metadata in this repository are licensed under the MIT License.

Archived game data, binaries, firmware, media assets, and other third-party
materials are **not** covered by the MIT License and remain the property of
their respective copyright holders.

See the `LICENSE` and `NOTICE` files for full details and scope clarification.
