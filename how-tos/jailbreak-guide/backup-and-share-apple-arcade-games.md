# Backup & Share Apple Arcade Games

## Requirements

* Jailbroken iOS device
* Valid Apple Arcade subscription
* `noappthinning` via the following repo: [https://n3d1117.github.io/](https://n3d1117.github.io/)
* `CrackerXI+` from the following repo: [https://cydia.iphonecake.com/](https://cydia.iphonecake.com)

## Instructions

1. Get a valid subscription of Apple Arcade
2. Download the game/s you want
3. Open CrackerXI+ and enable the options CrackerXI Hook, Remove UISupportedDevices and Fakesign IPA.
4. On CrackerXI+, choose the game you want to crack.
5. Transfer the IPA of the game/s to your computer
   1. Install a plist editor if you are on Windows (For example [https://www.icopybot.com/plist-editor.htm\\](https://www.icopybot.com/plist-editor.htm/))
6. Extract the cracked Arcade app by renaming AppName.ipa to AppName**.zip**
7. Inside the Payload folder, navigate into the Appname.app folder
8. Edit the `Info.plist` file and change the value of "`NSApplicationRequiresArcade`" from true to false.&#x20;
9. Compress the Payload folder, and rename from AppName.zip to AppName**.ipa**
10. Test by uninstalling the original game and installing the modified one

### References

* Backup & Share Apple Arcade Games by /u/Sergio\_Prado \[[link](https://www.reddit.com/r/sideloaded/comments/h0nejw/guide\_backup\_share\_apple\_arcade\_games/)]
