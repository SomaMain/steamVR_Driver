# steamVR_Driver
This driver is made by Ju1ce from AprilTags: https://github.com/ju1ce/April-Tag-VR-FullBody-Tracker#installing-the-steamvr-driver
It may be an older version, but it should work fine.

This is the driver that connects the server to steamVR.

#Setup
- Unzip the file
- Drag the 'apriltagtrackers' folder into your steamVR driver folder

`C:/Program Files (x86)/Steam/steamapps/common/SteamVR/drivers`

- Go to `C:\Program Files (x86)\Steam\config` and open your `steamvr.vrsettings` file with notepad.
-Under the "steamvr" : { section, add this line :
`"activateMultipleDrivers" : true,`

It should look something like this: 

## Example:
```
"steamvr" : {
      "activateMultipleDrivers" : true,      
      "installID" : "6929191912233415209",      
      "lastVersionNotice" : "1.18.7",      
      "lastVersionNoticeDate" : "1626220647",      
      "showAdvancedSettings" : true,      
      "showMirrorView" : true      
},
```
