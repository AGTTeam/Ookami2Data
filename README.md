# Ookami 2 Data
This repository contains all the strings and assets for the game's patch.  
If you're looking for the English patch, click [here](https://github.com/AGTTeam/Ookami2Data/releases).  
If you're looking for the game's tool, click [here](https://github.com/AGTTeam/OokamiTranslation).  

Add translations for each line after the `=` sign.  
Line breaks are represented by a `|`.  
Comments can be added at the end of lines by using `#`.  
## wsb_input.txt
Main script file.  
The text is automatically wordwrapped, but a `|` can be used to force a line break.  
New textboxes can be added by appending `>>` followed by the new text.  
Lines can be automatically centered by putting a `<<` at the beginning of the line.  
To blank out a line, use a single `!`. If just left empty, the line will be left untranslated.  
The COMMON section at the beginning contains some system lines that are repeated a lot of times in different files, including character names.  
## dat_input.txt
Miscellaneous text used for item descriptions, rumors, etc.  
The text in the "goods.dat" and "gossip.dat" files is automatically wordwrapped.  
## bin_input.txt
System text.  
Control codes are specified as `<XX>` or `UNK(XXXX)`, they should usually be kept.  
## images.txt
A list of text contained in the images in the work_IMG folder.  
## opening.ass
At the bottom of the files, the opening theme lyrics and special message text should be translated.  
If needed, use Aegisub to split or merge the lines.  
