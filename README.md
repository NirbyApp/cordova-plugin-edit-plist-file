# Edit Plist File plugin
by Haythem OUEDERNI - <a href="https://github.com/haythemOUE">@haythemOUE</a>

# Platforms

iOS only

# 1 - Description
A cordova "plugin" that helps you indicate the modifications on the iOS's *-info.plist file.<br/>
So it avoids you to directly edit the *-info.plist file.<br/>
For example it is used to whitelist some schemes for ios9.<br/>
This plugin was initially created to avoid iOS 9 problems that prevent opening other apps from your own app because some used plugins aren't updated to take into consideration the new specification for iOS 9.

# 2 - How to use

This plugins come with already some whitelisted apps :<br/>
- Twitter<br/>
- Facebook<br/>
- Whatsapp<br/>
- itm-apps<br/>
- Youtube<br/>
- Soundcloud<br/>

If you don't need to add other apps you can add it directly to your project by running <br/><br/>

```
cordova plugin add cordova-plugin-edit-plist-file
```

or

```
cordova plugin add https://github.com/NirbyApp/cordova-plugin-edit-plist-file.git
```

If you want to custumize the plugin so that you can edit extra tags on the *-info.plist file you can :
- download the plugin in a local repo
- edit the plugin.xml file of the plugin
- add the local plugin to your project by running :

```
cordova plugin add /your-repo/cordova-plugin-edit-plist-file
```
