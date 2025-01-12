[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico)
![Project](https://img.shields.io/badge/Project-Raspberry%20Pi%20Pico-light.svg?style=flat&logo=raspberrypi&logoColor=white&color=%23F7DF1E)

# LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico
<strong>Solo Project: Raspberry Pi Pico-based Reactive Music LED</strong><br><br>

## Project Requirements
| Part | Description |
| --- | --- |
| Development Board | Raspberry Pi Pico |
| Code Editor | Thonny IDE |
| Bootloader | MicroPython UF2 |
| Programming Language | MicroPython |
| Packages | • machine (default)<br>• utime (default) |
| Actuators | LED (x9) |
| Sensor | FC-04: Sound Sensor (x1) |
| Other Components | • Micro USB cable - USB type A (x1)<br>• Jumper cable (1 set)<br>• Breadboard (x1) |

<br><br>

## Download & Install
1. Thonny IDE

   <table><tr><td width="810">

   ```
   https://thonny.org/
   ```

   </td></tr></table><br>

2. MicroPython UF2

   <table><tr><td width="810">

   ```
   https://bit.ly/MicroPython_UF2
   ```

   </td></tr></table>
   
<br><br>

## Project Designs
<table>
<tr>
<th width="280">Block Diagram</th>
<th width="280">Pictorial Diagram</th>
<th width="280">Wiring</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/assets/54527592/bb91d3f4-d02a-4c98-9538-6bf1f0de724f" alt="Block-Diagram"></td>
<td><img src="https://github.com/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/assets/54527592/46697952-d430-432c-94fb-fcea55ab3f8c" alt="Pictorial-Diagram"></td>
<td><img src="https://github.com/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/assets/54527592/10717ed4-ce88-40d7-b2c2-1bae12c23503" alt="Wiring"></td>
</tr>
</table>

<br><br>

## MicroPython Bootloader Setup
1. ``` Upload the firmware ``` :

   <table><tr><td width="810">      

      - Press and hold the ``` BOOTSEL ``` button on the ``` Raspberry Pi Pico ``` board while connecting to the computer via a ``` micro USB ``` cable.
   
      - After the ``` Raspberry Pi Pico ``` is recognized by the computer (connected), then immediately release the ``` BOOTSEL ``` button.
      
      - When successfully connected, a new drive called ``` RPI-RP2 ``` will open.
      
      - ``` Drag -> Drop ``` or ``` Copy -> Paste ``` the ``` MicroPython UF2 ``` firmware file into the ``` RPI-RP2 ``` drive.

   </td></tr></table><br>

2. After the process is successful, the ``` RPI-RP2 ``` drive will automatically close.<br><br>

3. In general, the firmware upload only needs to be done once when you first use the ``` Raspberry Pi Pico ``` board.

<br><br>

## Thonny IDE Setup
1. Open ``` Thonny IDE ``` first.<br><br>

2. Click ``` Tools ``` -> then select ``` Options... ``` -> then select :<br><br>
   
   • ``` Interpreter Menu ```, then change the part :

      <table><tr><td width="810">
      
      - ``` Interpreter ``` -> ``` MicroPython (Raspberry Pi Pico) ```
        
      - ``` Port ``` -> ``` Board CDC @ COM... ```
  
      - ``` Restart interpreter before running a script ``` -> ``` uncheck ```

      </td></tr></table>
   
   • ``` Editor Menu ```, then check all the options except: ``` Indent with tab characters ```.<br><br>

3. If the file view does not exist in ``` Thonny IDE ```, then please click the ``` View ``` -> section and select ``` Files ``` to display it.<br><br>

4. Then look for a file called ``` main.py ``` in directory: ``` LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/Src ```.<br><br>
   
5. Right click on the file -> select ``` Upload to / ```.<br><br>

6. Open the file ``` main.py ``` which is in the ``` Raspberry Pi Pico ``` storage -> then click ``` Run current script (F5) ```.<br><br>

7. Program code executed successfully -> sign: ``` %run -c $EDITOR_CONTENT ```.<br><br>

8. If there is still a problem when uploading the program, then try to check the ``` interpreter ``` / ``` port ``` / ``` others ``` section.

<br><br>

## Get Started
1. Download and extract this repository.<br><br>
   
2. Make sure you have the necessary electronic components.<br><br>
   
3. Make sure your components are designed according to the diagram.<br><br>
   
4. Configure your device according to the settings above.<br><br>

5. Please enjoy [Done].

<br><br>

## Highlights
<table>
<tr>
<th width="420">View-1</th>
<th width="420">View-2</th>
</tr>
<tr>
<td><img width="840" src="https://github.com/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/assets/54527592/6cacee09-4b5c-428f-ace2-0d7d7a1466e6" alt="img-1"></td>
<td><img width="840" src="https://github.com/devancakra/LED-Musik-Reaktif-Berbasis-Raspberry-Pi-Pico/assets/54527592/1757076e-3e19-401a-8afa-c6c6becae9e2" alt="img-2"></td>
</tr>
</table>

<br><br>

## Appreciation
If you find this work useful, please support this work as a token of appreciation to the author by clicking the ``` ⭐Star ``` button.

<br><br>

## LICENSE
MIT License - Copyright © 2024 - Devan C. M. Wijaya, S.Kom

Permission is hereby granted without charge to any person obtaining a copy of this software and the software-related documentation files to deal in them without restriction, including without limitation the right to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons receiving the Software to be furnished therewith on the following terms:

The above copyright notice and this permission notice must accompany all copies or substantial portions of the Software.

IN ANY EVENT, THE AUTHOR OR COPYRIGHT HOLDER HEREIN RETAINS FULL OWNERSHIP RIGHTS. THE SOFTWARE IS PROVIDED AS IS, WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, THEREFORE IF ANY DAMAGE, LOSS, OR OTHERWISE ARISES FROM THE USE OR OTHER DEALINGS IN THE SOFTWARE, THE AUTHOR OR COPYRIGHT HOLDER SHALL NOT BE LIABLE, AS THE USE OF THE SOFTWARE IS NOT COMPELLED AT ALL, SO THE RISK IS YOUR OWN.
