  ___                               _____          _             
 / __| _  _  ___ _ __   ___  _ _   |_   _|___  ___| |_  ___  _ _ 
 \__ \| || |(_-<| '  \ / _ \| ' \    | | / -_)(_-<|  _|/ -_)| '_|
 |___/ \_, |/__/|_|_|_|\___/|_||_|   |_| \___|/__/ \__|\___||_|  
       |__/                                                      

# Sysmon tester

Script developed in Powershell to test if Sysmon Installation was successful.

I have found that some times Sysmon installations **FAIL** also I found that it's really anoying to check what's go wrong especially if one has no control over the machine's administration or the installation is embebed in other script or source.

So i develop this simple Script to verify 3 things:

1.- Sysmon64.exe it's installed and deployed in \Windows folder.
2.- Ensure that the driver (SysmonDRv.sys) is deployed in \Windows folder.
3.- Log appears available for regiter events.
