# evive Scratch Extensions
Repository for mBlock Scratch extensions for evive

# Getting Started with Scratch

Scratch is a free programming language where you can create your own innovative and interactive projects, stories, games, and animations. mBlock is based on Scratch 2.0 and let you use evive for your projects through its Arduino plugins.

***Follow the following steps to configure Scratch for use:***

1. Download Arduino IDE from http://arduino.cc and install the latest version of the software.
    1. Go to the Arduino download page (www.arduino.cc) and download the latest version of the Arduino software.
    2. When the download is finished, run arduino-1.8.1-windows.exe (in my case) application. And click on I Agree.
![windows_step1](https://user-images.githubusercontent.com/20287504/29311869-bb1cf0c4-81d0-11e7-9448-3a6d5b4849e8.png)
    3. Choose the components to install (Recommended to install all components).
![windows_step2](https://user-images.githubusercontent.com/20287504/29311893-e20c83ca-81d0-11e7-8529-d0b346a70feb.PNG)
    4. Choose the installation directory (Recommended to keep the default one).
![windows_step3](https://user-images.githubusercontent.com/20287504/29311895-e420df6c-81d0-11e7-9b16-413c84955e96.PNG)
    5. The process will extract and install all the required files to execute properly the Arduino Software (IDE).
![windows_step4](https://user-images.githubusercontent.com/20287504/29311896-e583ff88-81d0-11e7-8fac-ad4b3615914a.PNG)
    6. Close the installation window when it’s complete.
        
        ![windows_step5](https://user-images.githubusercontent.com/20287504/29311897-e7217b7c-81d0-11e7-96c4-155d98853bf8.PNG)

2. Download and install the latest version of mBlock from http://mblock.cc. (Installation of mblock is simple and pretty straight forward. Here we are showing the installation steps for windows user only.)
    1. Go to www.mblock.cc and download the program, by clicking on “Windows Download” buttons.
    2. When the download is finished, unzip the file. In the folder, you will find mBlock application setup file (.exe extension). Run the setup.
        
        ![s1](https://user-images.githubusercontent.com/20287504/29312705-3fde0d90-81d4-11e7-863b-5655628ff6bc.png)
    3. Choose the appropriate language and press “OK”. In our case, we are choosing English.
    
        ![s2](https://user-images.githubusercontent.com/20287504/29312707-4113cff6-81d4-11e7-81c0-e63d4f42e776.PNG)
    4. A new window will popup. Press “Next”.
    
        ![s3](https://user-images.githubusercontent.com/20287504/29312710-42a97ee2-81d4-11e7-88bc-f0bd6652f4d6.PNG)
    5. Choose the installation directory (We suggest you to not change the directory). Then press “Next”.
    
        ![s4](https://user-images.githubusercontent.com/20287504/29312711-43e98d56-81d4-11e7-8f78-ae6fd7eb538b.PNG)
    6. Select start menu folder, where the setup will place the program’s shortcuts. Then press “Next”.
        
        ![s5](https://user-images.githubusercontent.com/20287504/29312714-454f7656-81d4-11e7-9e08-511f304a6050.PNG)
    7. Check the “Create a desktop icon”, if you want to create the desktop icon. Then press “Next”.
        
        ![s6](https://user-images.githubusercontent.com/20287504/29312716-46b895d6-81d4-11e7-8b6a-e3b9fa221182.PNG)
    8. Press “Install”.
    
        ![s7](https://user-images.githubusercontent.com/20287504/29312717-47f62350-81d4-11e7-9751-26183e94a5b0.PNG)
    9. After the installation is finished press “Finish”. You have now installed Scratch in your computer.
    
        ![s8](https://user-images.githubusercontent.com/20287504/29312718-4a088598-81d4-11e7-82c9-1a80090bd8ad.PNG)

3. After installing Arduino IDE and Scratch, go to My Computer > Disk C > Program files. There you will find Arduino folder, where Arduino IDE is installed. Copy that folder.
4. Then, in the same folder (Program Files), you will find mBlock folder. Go into the folder.
5. There you will see another Arduino folder. Delete that folder.
6. Copy the previous Arduino folder here.
7. Install extensions:
    1. Download the extensions (Arduino, evive App, evive Inbuilt Functions, evive TFT Display and evive Tinkering) from here: https://github.com/evivetoolkit/eviveScratchExtensions/tree/master/Extensions.
    2. Open mBlock
    3. Go to Extensions in Toolbar and click Manage Extension
    4. A new window will pop-up with two tabs (available and installed). Click on intalled, and then click on Add Extension.
    5. Change the file type to .zip and select the previously downloaded extensions one by one.
    
        ![2017-08-15 at 14-52-41](https://user-images.githubusercontent.com/20287504/29313203-5fbee24a-81d6-11e7-934f-38b53e6adfed.png)
    6. After adding all the extensions, close the pop-up. In Robots palette, you can see the extension blocks.
8. To work on Scratch mode, you have to upload a firmware to evive. Follow the steps:
    1. Download the firmware from here: https://github.com/evivetoolkit/eviveScratchExtensions/blob/master/Scatch%20Firmware/eviveScratchFirmware.zip
    2. Unzip the folder.
    3. Open eviveScratchFirmware.ino in Arduino IDE.
    4. Upload the code to evive.
    5. Open Srcatch, go to connect, then serial and select COM Port. 
    6. You are all set to work in Scratch mode.
