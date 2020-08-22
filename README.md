## Custom Chat Wheel Sounds by Vyrium

## Table of Contents
* [Changed sounds](#changed-sounds)
* [Installation](#installation)
* [Folder Structure](#folder-structure)
* [pak_01_dir.vpk](#pak_01_dir.vpk)

## Changed Sounds

'ti10eventgame_reward1' - Friends, let us skirmish! - ISDD

## Installation

 1. `[Download ZIP](https://github.com/Vyrium/DotaCustomChatSounds/archive/master.zip)`
 2. Move 'game' folder to Dota 2 directory (e.g. C:\Program Files (x86)\Steam\steamapps\common\dota 2 beta)

## Folder Structure
***customsounds** folder contains pak_01_dir.vpk this contains overwritten files for changing the chat wheel text/sounds*
***dota** folder contains gameinfo.gi - This includes the following additional lines:*

    Game				customsounds
    Mod					customsounds

## pak_01_dir.vpk

### resource/localization

**dota_english.txt** - Contains modified chat wheel labels and messages

### sounds/misc/soundboard
	
**vsnd_c** - Valve Source 2 sound file - Change wav/mp3 files to this format by creating a new addon using dota 2 workshop tools and placing into addon 'content' folder. Converted file will appear in corresponding 'game' folder