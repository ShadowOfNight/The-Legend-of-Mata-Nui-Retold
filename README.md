# The Legend of Mata Nui Retold

Description
--------------
Renovation of the beta build through porting the alpha content and performing an overhaul of said content.


Changelog
--------------
v0.00.400
- Restored functionality to Nobua BECH cutscene.
- Added killbox coding back into BECH.
- Moved Nobua in PTV2 to before the push block.
- Added death/spawn sounds for toa.
- More OSI cleanup.
- Changed timer sound effect.
- Removed spid.blk from character assets.
- Removed three old cinematic tracks from Sounds folder.
- Added missing sound slbs into lev7 areas.
- Separated unused textures out of lev7.blk.

v0.00.300
- Fixed turaga vertex color barfing.
- Fixed issues with bull movement sound loop not stopping properly.
- Fixed a problem that caused killboxes in BLR areas to warp you instead of respawning.
- Fixed cutscene skipping/audio issues in BLCV.
- Fixed various texture animation issues for all levels.
- Ported alpha cutscene files.
- Fixed texture transparency issue in VLLG; added coindoor texture (level 6).

v0.00.222
- Various fixes/adjustments/edits to stringtables.
- More osi cleanup; MAZ2 ui disappearance bug fixed.
- Added osi coding for ICMZ.
- Fixed incorrect boolean value in tfsh AIInfo.slb which prevented it from swimming properly.

v0.00.221
- Removed outdated strings from Lev1_eng.slb.
- Removed old lev4c.blk from level 4 assets.
- Some more osi cleanup.
- Added ICMZ area to Kopaka's warp list
- Added slbs to ICMZ blk that were missing.
- Removed disc and glyph models from ICMZ (updated obj slb) and replaced area ocl with a bcl.

v0.00.220
- Set up Lewa to start with just the Akaku, Komau, Rau, and Ruru masks.
- Removed Huna model/textures from Lewa's assets.
- Removed old hutt blks from levels 3, 4, and 6.
- More osi symbols cleanup.

v0.00.219
- Changed meetup text for each Toa to fit changed gameplay.
- Fixed a small typo in the Lev3_eng.slb.

v0.00.218
- Added sign back into L1A1 area; also removed a hive.
- Cleaned up L1A1 blk a bit, along with osi coding.

v0.00.217
- Added BECH area to level 2 (added warp menu entry as well).
- Removed Kau Kau mask textures/models from Kopaka and Tahu blks.
- Removed Kau Kau from Kopaka and Tahu inventories.
- Edited Gali's Kau Kau textures to have translucency.
- Fixed mask transparency issues in character textures blk.
- Changed Vahi mask texture colour to gold.
- Cleaned up some redundant strings in the osi.

v0.00.216
- Added tutorial text into Lev2.
- Inserted Lev3_eng.slb, which was missing for an unknown reason.

v0.00.215
- Added new sign text into Lev1_eng.slb.
- Added conversation slb to TMBL.
- Adjusted ATRM convo slb per totem addition.
- Added sign model to ATRM.
- Set up level 2 so Gali starts with just the Pakari.  

v0.00.214
- Enabled Options menu in the developer menu.
- Fixed Onua right sidestep problem.
- Added fixes for TTUN positioning issues.
- Added air bubbles to ATRM; repositioned tokens; removed two bugs; adjusted grapple box position.
- Fixed water splash sounds from not playing.
- Reorganized Lev1_eng.slb; removed old copies of Fluff_eng.slb and Lev7_eng.slb.
- Disabled grapple box in Ga-Koro.
- Fixed issues with sky, water, and main models in level 2 MTUP.

v0.00.213
- Removed cin4 and cin5 files from lev1 blk.
- Fixed stringtable pointers in cin1_text.slb and cin2_text.slb in lev1.blk.
- Ported alpha ATRM area and made some adjustments to it.
- Updated osi coding for ATRM.
- Added missing osi coding for grapple point in level 4 area CRSS.

v0.00.212
- More osi cleanup; set up MTUP to be loaded first in level 2.
- Ported alpha level 2 MTUP.
- Added Load Game function back to test menu. (courtesy Hexadecimal Mantis)

v0.00.211
- Replaced sky models in BECH and PTV2.
- Removed PTV1 from assets (removed PTV1 string from osi as well).
- Some more osi cleanup (removed a debug string)

v0.00.210
- Some more osi symbol cleanup; removed an unused cheat subroutine for TMBL.
- Fixed L1A6 trigger.

v0.00.209
- Fixed triggers in L1A6 and TMBL.
- Moved exit door function from osi into TMBL trigger slb for simplicity.

v0.00.208
- Ported alpha L1A2 area; activated osi code for it.
- Ported alpha L1A6 area; activated osi code for it.
- Ported alpha TMBL area; activated osi code for it.

v0.00.207
- Improved PTV2 a bit; updated tree collisions, added hive, fixed improper culling with tree model, adjusted lighting (though it's still broken), adjusted start positions slightly.
- Removed coding for PTV1 area in OSI.
- Removed duplicate MusicOnuaAmbience strings; changed all references to match casing of string.
- Fixed bridges in CLF1 from being out sometimes upon entering.
- Ported alpha MOSH for level 1.

v0.00.206
- Added alpha CONVO_slbs for SHRN and BOSS blks in lev2 through lev6.
- Fixed small typo in lang_eng.blk that caused Matau's SHRN and BOSS dialogue to not display properly.

v0.00.205
- Moved block back in PTV2 due to it being too far forward to hit trigger plane.
- Activated PTV2 area code with slight cleanup.
- Partially reordered Onua debug warp list.

v0.00.204
- Fixed falltodeath sound from not playing.
- Removed old ghut.blk from level 2 assets.
- Ported alpha BECH area.
- Ported alpha PTV2 area.
- Removed whirlpool from lev2 Shrn.blk (updated obj.slb).

v0.00.203
- Fixed ice bat movelist typos.
- Increased mud texture animation speed for mud monster.
- Compressed and cleaned up textures blk.

v0.00.202
- Added texture animations to water elemental.
- Fixed texture transparency on air and water elementals.
- Added weak point textures for water and ice elementals; also edited textures (and subsequently for the earth elemental).

v0.00.201
- Ported alpha stringtables.

v0.00.200
- Added JrMasterModelBuilder's fixes for character sandprints.
- Fixed Gali melee crash by temporarily using jump sound in place of non-existent kick sound.
- Fixed Gali backstep issues in animevents.slb.
- Ported alpha animations for cutscenes for characters.
- Removed old language test screen code from OSI.
- Removed Names slbs from some character folders; animation ID lists will be made to replace them.
- Changed grass texture in front end.
- Fixed Nui-Rama broken animations.
- Added Hexadecimal Mantis' fix for Lewa jump sound.

v0.00.103
- Added cleaned up version of Art.blk.
- Compressed lang_eng.blk.

v0.00.102
- Removed LEGO and Saffire intros (both files and osi coding).
- Compressed lev0 blk and recompressed frnt.blk with newer blk script.

v0.00.101
- Removed some outdated symbols from base.osi.
- Updated gitignore file.

v0.00.100
- Cleaned up lev0.blk so it has only the textures it needs.
- Fixed material.slb in lev0.blk from causing front end bcl from using incorrect footstep sounds. Also stripped slb of unneeded materials.
- Removed unneeded texture references from textures.slb in lev0.blk.
- Ported jamesster's fixes for the various issues with frnt.blk models.

v0.00.005
- Fixed the Kanohi Kaukau being called the "Mask of Water" instead of the "Mask of Water Breathing" in both the glossary and MWAT
- Fixed the throwing disk in Lev2 being called the "Gali throwing disk"
- Added the name "Taniwa-Nui" into the Lev2 text for the boss
- Replaced beta HYDR dialogue with the alpha lines

v0.00.004
- Added areas ILLU and GLY2 to levels\lev5 and added entries to debug warp list for Lewa.
- Removed blank debug menu entries under Abilities menu.
- Ported alpha version of Ga-Kini (SHRN) and performed edited osi slightly to make it functional. 

v0.00.003
- Removed data\Art\hud folder as contents are not used.
- Removed empty haka.blk from data\levels\lev4

v0.00.002
- Removed all language blks save the one for English.  New ones will be generated once English text has been finalized.
- Removed two mp3s from data\Sounds that were duplicates and therefore unused.

v0.00.001
- Removed everything save BionicleFont.col from data\Art\Fonts.
- Removed everything but LUKE.col from data\Art\MenuArt.
- Removed shoefitter and slider folders from data\Art directory.
- Removed an unused text file from data\Art directory.
- Removed two unused tgas from main data directory (these appear to be the result of a screenshot feature).
- Removed old and unused data\levels\fren directory and the two blks within.

v0.00.000	
- Initial build.


Credits
--------------

