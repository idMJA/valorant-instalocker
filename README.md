# valorant-instalocker
Automatically picks a selected agent as soon as possible.

![](https://i.imgur.com/0nYAqMg.png)

------------

### DOWNLOAD OPTIONS
⚠️Please, PLEASE READ the [FAQ](#faq) before download this app

- #### [❶.EXE](https://github.com/pintoso/Agent-Picker/releases/latest/download/AgentPicker.exe)
**extra protection for vanguard not to detect AgentPicker as an ahk**
>✔️Make an exception for the `InstaLock.exe` if your antivirus does not like the file, this is a FALSE positive. 
([VIRUSTOTAL](https://www.virustotal.com/gui/file/b16bab869527ccafd8c885928012ffbef102175358ce744e751495029da1ce34/detection) scan)


- #### [❷.AHK](https://github.com/pintoso/Agent-Picker/archive/refs/heads/master.zip)
**need to install [AutoHotkey](https://www.autohotkey.com/download/ahk-v2.exe), extract the Agent Picker files and run `AgentPicker.ahk` as admin**

you can also [compile it yourself](#compiling)

## How to use
1. Download & run executable
2. Run VALORANT
3. Choose a agent via the dropdown
4. Start a queue
5. Press F4 to toggle on the script
6. After Done Press F4 Again
7. Then Press F9 To close Quickly This App
8. Profit

# How to configure for your resolution

1. ScreenShoot Your Screen On Agent Selector In Custom Game Or Whatever (please read this. EVERY USERS OR MONITORS ITS NOT SAME SO PLEASE DONT STEAL OTHER IMAGES OR UR PC WILL GOT ERROR CANNOT FIXED)
2. Go To [This](http://image-coordinates.mj1532.us.to/) Website and select the file that you screenshot in the agent selector to get X and Y
3. Fill [[X]Agent List.txt]([X]Agent%20List.txt) = X Agents position
4. Fill [[Y]Agent List.txt]([Y]Agent%20List.txt) = Y Agents position
5. Fill This [Continue Button.ini](Continue%20Button.ini) = XY Continue Button position

Need A Tutorial?
Comming Soon

## Compiling
if you want to compile by yourself for security reasons, follow this step by step to compile correctly in `.exe`

(step 7 and 8 are optional)

1. Install [AHK](https://www.autohotkey.com/download/)
2. Download/clone the [github repository](https://github.com/pintoso/Agent-Picker)
3. Download [Ahk2Exe Beta](https://github.com/AutoHotkey/Ahk2Exe/releases/tag/Ahk2Exe_v1.1.34.00_Beta_1)
4. Install Ahk2Exe Beta following these [instructions](https://www.autohotkey.com/boards/viewtopic.php?f=6&t=65095)
5. Download, compile and install [BinMod.ahk](https://github.com/AutoHotkey/Ahk2Exe/blob/master/BinMod.ahk) (follow the instructions on line 15)
6. Compile `AgentPicker.ahk` using Ahk2Exe using these [settings](https://i.imgur.com/Od8XPH7.png)
7. Download [imageCFG](https://robpol86.com/imagecfg.html) and place it in the same `AgentPicker.exe` folder
8. open CMD in that folder and run `imagecfg -u AgentPicker.exe`

## FAQ
- Why is my antivirus blocking Agent Picker?
> the executable(.exe) version was compiled in a way that your antivirus doesn't like(?), but yes it is safe, you can review the source code and compile it yourself, you will get the same result.

- What is this *"extra protection"* ? and why?
> The extra protection basically makes the anticheat(Vanguard) not know that the Agent Picker is an AHK.
This is a prevention if at some point Vanguard starts to realize that players who pick agents too quickly have AHK open in the background.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[![forthebadge](https://670fa656-01df-442c-9c0a-94011a63f1bf.id.repl.co/svg/build-for-valorant.svg)](https://playvalorant.com/)

Credits: [Pintoso](github.com/pintoso)

Repository: [Agent Picker](https://github.com/pintoso/Agent-Picker)
