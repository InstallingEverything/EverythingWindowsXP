![MSN Messanger](Images/MSN.png)

# MSN Messanger Removal

To remove MSN Messenger from Windows XP due to service being long retired.

We have created a script to efficently remove from Windows XP without patching or modding Windows.

    RunDll32 advpack.dll,LaunchINFSection %windir%INFmsmsgs.inf,BLC.Remove

This will remove the product from Windows,

