# steamVR_Driver

This is the driver that connects the server to steamVR.
Take the "example" folder and place it inside your steam folder : 'C:/Program Files (x86)/Steam/steamapps/common/SteamVR/drivers'

Next
Go to 'C:\Program Files (x86)\Steam\config' and open your 'steamvr.vrsettings' file with notepad.
Under the "steamvr" : { section, add this line :
"activateMultipleDrivers" : true,

It should look something like this: 

## Example:
"steamvr" : {
      "activateMultipleDrivers" : true,      
      "installID" : "6491764559652401292",      
      "lastVersionNotice" : "1.18.7",      
      "lastVersionNoticeDate" : "1626220647",      
      "showAdvancedSettings" : true,      
      "showMirrorView" : true      
},
##
