#### Find Classes for YTBP faster

# YTBP IDA Scripts
# How to use
- Download `find_classes.py` or `find_classes.idc` script file
  - for YTM, use `find_classes_music.py` or `find_classes_music.idc`
- Decompile YT/YTM .apk file using [apktool](https://ibotpeaches.github.io/Apktool/) (using `apktool d -s <apk file>` command)
- Open `classes.dex` and `classes3.dex` files in IDA Pro
  - for YTM, open `classes2.dex` and `classes3.dex`
- After initial auto-analysis, load downloaded script in IDA in `File > Script file...` (default `Alt+F7`)
- When loaded correctly, it should show new classes to hook in output window at the bottom

### Note: 
- For YT, **Class 1** and **Class 3** are in `classes.dex`, **Class 2** should be in `classes3.dex`
- For YTM, **Class 1** is in `classes3.dex` and **Classes 2, 3 and 4** are in `classes2.dex`
###### Make sure all classes have proper structure and they are indeed correct and hookable...
###### Just open previous version of YT .apk and compare them...
