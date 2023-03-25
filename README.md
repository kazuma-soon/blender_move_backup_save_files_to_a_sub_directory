# blender_move_backup_save_files_to_a_sub_directory

## overview
Blender creates files with extensions like blend1, blend2 for backup. 
However, these files are created in the same directory as the blend file you are working with. 
This clutters your working directory. 

So this addon automatically organizes your working directory by saving backup files in a subfolder called "backup.blend".


## Operation verification environment
does not work on Windows.
- Apple M1 Pro, macOS Ventura 13.2.1
- blender 3.4.1


## Usage
- Download source file
  - Download `blender_move_backup_save_files_to_a_sub_directory.py` from here.
- Install addon
  - Open blener and move Edit > Preferences > add-ons.
  - Click "Install an add-on".
  - Select the downloaded `blender_move_backup_save_files_to_a_sub_directory.py`.
  - Check "System: Move Backup Save Files To A Sub Directory" to enable the addon.
  - Press "Save Preferences".

The first time you save a blend file, a subfolder named backup.blend is created in the directory containing the blend file. 
After the second save, blend1, blend2... will be saved in that folder.

Change how many backup files are created in Edit > Preferences > Save & Load > Save Versions.


## Thanks for "Jonathan Stroem" and "Paul Mohr"
I created this addon with reference to [this page](https://blender.stackexchange.com/questions/6940/config-blender-to-save-backup-files-in-subfolder). Thanks to them I am able to create and share this. 
Thank you.
