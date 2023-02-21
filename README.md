# ClassicUO_MapIcons_UOAlive
These are the icons that show on your mini map in ClassicUO

Notes from Avernal (creator)
Latest map marker pack - there have been significant changes to this one, every icon has been reworked and all the unused/bollocks ones that accumulated from several people just pasting their junk in together have been deleted. So you will need to remove any older versions and delete the 'MapIcons' folder entirely. Screenshot explains what is a clean client folder so use that as reference. Icons shouldn't change much from this point and if I add any new ones it'll just be as simple as adding them to the MapIcons folder.

Labels are still not 100% - I know for a fact there are certain dungeon markers that are in the 'Common' file, only way for me to fix those is to be sat in the respective facet, dragging the map around, toggling markers on and off and then searching for them in the text files to move them around. There are likely also mislabeled ones still too (things that are stairs that are marked as a point, or named monsters marked as an NPC), but it's a night and day difference of improvement over the original outdated files.

- Every icon has been either tuned or outright redrawn to be both clearer and occupy a bit less space so they don't cover stuff up as much (better contrast, significant attention paid to shades, in the case of the Tanner sign I've made new art because an orange splodge means nothing)
- New markers and icons added for things like Traps, Stealables (smaller and clearer now), Quest/NPC
- Labels have been tidied up, moved around to relevant files/categories and in some cases nudged around a bit to prevent overlapping
![unknown](https://user-images.githubusercontent.com/3319999/220403874-f4d07f47-8f54-413f-9eef-9e6f648430a3.png)


Just an update, guys - this now works for the Orion client too. You'd delete the default contents of this folder Orion Launcher\OrionData\WorldMapExternalMarkers\ (don't worry, it's just the janky data dump of all the outdated map markers they grabbed from the Outlands gang and Github) and then place the contents of the cuo-markers-new ZIP file in that folder instead. It should look like this if done correctly:![image](https://user-images.githubusercontent.com/3319999/220403740-133a71e5-f7fb-4806-adfa-60a3f2c7f384.png)
