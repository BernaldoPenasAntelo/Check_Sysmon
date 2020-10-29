


```
 _______         _______ _______ _______ _         ________________  _______________________ _______ 
(  ____ \\     /(  ____ (       |  ___  | (    /|  \__   __(  ____ \(  ____ \__   __(  ____ (  ____ )
| (    \( \   / ) (    \/ () () | (   ) |  \  ( |     ) (  | (    \/| (    \/  ) (  | (    \/ (    )|
| (_____ \ (_) /| (_____| || || | |   | |   \ | |     | |  | (__    | (_____   | |  | (__   | (____)|
(_____  ) \   / (_____  ) |(_)| | |   | | (\ \) |     | |  |  __)   (_____  )  | |  |  __)  |     __)
      ) |  ) (        ) | |   | | |   | | | \   |     | |  | (            ) |  | |  | (     | (\ (   
/\____) |  | |  /\____) | )   ( | (___) | )  \  |     | |  | (____/\/\____) |  | |  | (____/\ ) \ \__
\_______)  \_/  \_______)/     \(_______)/    )_)     )_(  (_______/\_______)  )_(  (_______//   \__/
                                                                                                                                                                                                         
```

# Sysmon tester


Script developed in Powershell to test if Sysmon Installation was successful.

I have found that some times Sysmon installations **FAIL** also I found that it's really anoying to check what go wrong especially if one has no control over the machine's administration or the installation is embebed in other script or source.

So i develop this simple Script to verify 3 things:

1.- Sysmon64.exe it's installed and deployed in \Windows folder.

2.- Ensure that the driver (SysmonDRv.sys) is deployed in \Windows folder.

3.- Log appears available for regiter events, and event 4 and 255 gathering.

This script generates a log in **C:\Windows\Temp** called **sysmon.log** with the results of the test
