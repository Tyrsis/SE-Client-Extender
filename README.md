# Space Engineers Client Extender

### Automatic Plugin Install

In order to automatically install the SE Client Extender plugin, please download the executable at the following location: https://github.com/Tyrsis/SE-Client-Extender/releases/download/1.0.0.0/SEClientExtender_Inst.exe

Then follow these steps:

* Run the executable.
* Follow prompts. 
* Run the game with the shortcut created.

### Manual Plugin Install


In order to install the SE Client extender plugin manually, please download the zip that contains the applicible DLLs at the following location: https://github.com/Tyrsis/SE-Client-Extender/releases/download/1.0.0.0/SEClientExtender.zip

Then follow these steps:

* Extract the contents of the .zip into your Space Engineers Bin64 directory (Usually located at \Steam\SteamApps\common\SpaceEngineers\Bin64)
* Right click on the SpaceEngineers.exe file in that Bin64 directory and select "Create Shortcut"
* Right click the shortcut that is created and modify the "Target" field.  Go to the end of the field, hit space and type in: -plugin SEClientExtender.dll
* Launch the game with the shortcut created.  You may copy the shortcut to your desktop to easily run.

### Launching the plugin automatically from steam

After you install the plugin, you can have steam launch the game all the time, without needing to use the shortcut created.  Just do the following:

* Open your steam library
* Right click on Space Engineers and click Properties
* In the General tab, at the bottm click on "Set Launch Options"
* Type in -plugin SEClientExtender.dll
