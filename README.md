# autoSetProject
auto set project plugin for maya

# Installation
Steps to install auto set project. 
1. Download this repository and copy the `autoSetProject.py` into a folder in your `MAYA_PLUG_IN_PATH`
    - If you're unsure of what folders are in your plugin path the following directory is a good place to save the the plugin:
        - (Linux)`$HOME/maya/<version>/plug-ins`
        - (Mac OS X) `/Users/<username>/Library/Preferences/Autodesk/maya/<version>/plug-ins`
        - (Windows) `C:/Users/<username>/Documents/maya/<version>/plug-ins`

2. Close maya if it is currently open. 
3. Open maya and open the plugin manager. Search for `autoSetProject.py` and check the 'Loaded' checkbox. 
    - For best results check 'Auto Load' checkbox as well to ensure proper loading whenever a new file is opened.

# Usage
After the plugin is loaded everytime a file is opened autoSetProject will attempt to find the workspace root and set the project. 

# Uninstallation
Delete the `autoSetProject.py` file from your plugin path
 
 
# Credits
This plugin is derived from 'mSetProject' (author: Martin Yara www.skymill.co.jp). I've been a user of mSetProject since 2016, 
it had become an important component of my personal pipeline. However when I migrated to Maya 2020 the script was no longer 
compatable and the original author was no longer supporting the script. 

I re-wrote the tool for my personal use to function as a plugin for easier loading and unloading within maya, 
I use it all the time and hope it'll save you a couple seconds too!

Original Script: www.highend3d.com/maya/script/msetproject-for-maya

Modified under the MIT license. 
