# How-to-Fix-Cannot-Install-Windows-11-on-VirtualBox-
How to Fix Cannot Install Windows 11 on VirtualBox 

1)This PC can't run Windows 11 -> window

![Screenshot (436)](https://user-images.githubusercontent.com/47558327/136683284-93234dd0-619d-4745-b611-4ece7068d190.png)

    Press -> Shift + F10
  open up windows commend

2). Type 

![Capture2](https://user-images.githubusercontent.com/47558327/136683355-81287abf-43fe-4292-a1ce-a2d80d3b6ec8.PNG)

    regedit
    
3).Opening Registry Editer and Expand
  
  HKEY_LOCAL_MACHINE -> SYSTEM -> Setup
 
 ![Capture3](https://user-images.githubusercontent.com/47558327/136683573-f3fce7ae-7ec0-489a-84d3-971ba29c2e02.PNG)
 
 and Right Click on setup -> Create New Key -> Keyname -> LabConfig
 
 ![Capture4](https://user-images.githubusercontent.com/47558327/136683596-a10e6804-e28e-4a34-9868-1833273a8c9f.PNG)
  
4).Create 4 New DWORD (32-bit) Value

  ![Capture5](https://user-images.githubusercontent.com/47558327/136683796-87c9722c-439e-4c13-b5e2-59341f954ad8.PNG)
   
  ![Capture6](https://user-images.githubusercontent.com/47558327/136683811-deb310cc-be73-46b7-a25c-72b829287b15.PNG)
        
        1).BypassTPMCheck 
        2).BypassCPUCheck
        3).BypassRAMCheck
        4).BypassSecureBootCheck 
        
  double click
  
  ![Capture7](https://user-images.githubusercontent.com/47558327/136683813-7ee6a1bf-8885-4626-a766-e939785bc5de.PNG)
        
and  Set all Value 1    
    
close Registry Editer , Windows Commend and Windows Setup window and Click Install now -----> Done

![Capture9](https://user-images.githubusercontent.com/47558327/136683935-87942943-c55b-4975-a14c-3f84220172f4.PNG)

![Capture10](https://user-images.githubusercontent.com/47558327/136683937-4721e571-2c9f-4ba1-a66b-2ef66f651f6d.PNG)




