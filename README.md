#### Find Classes for YTBP faster

# YTBP IDA Scripts
# How to use
- Download `find_classes.py` or `find_classes.idc` script file
- Decompile YT .apk file using [apktool](https://ibotpeaches.github.io/Apktool/) (using `apktool d -s <apk file>` command)
- Open `classes.dex` and `classes3.dex` files in IDA Pro
- After initial auto-analysis, load downloaded script in IDA in `File > Script file...` (default `Alt+F7`)
- When loaded correctly, it should show new classes to hook in output window at the bottom

###### Note: Classes 1 and 3 are in `classes.dex` and class 2 should be in `classes3.dex` - ensure they have proper structure and they are indeed correct and hookable...
###### Just open previous version of YT .apk and compare the classes...
