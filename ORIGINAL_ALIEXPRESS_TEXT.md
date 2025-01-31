https://www.aliexpress.us/item/3256807810769681.html?spm=a2g0o.order_detail.order_detail_item.3.41c0f19cAyRyVQ&gatewayAdapt=glo2usa

##ZMK version corne


Only support ZMK and other wireless solutions do not support QMK wired solutions, suitable for conventional height axis, RGB backlight, hot swap, Bluetooth wired
Dual mode, without shaft, key cap, C-port line. At the request of the buyer, upload a key cap to do the next reference, for reference only.



##Special note:


Changing keys is done using git action, which is a bit cumbersome but not difficult. Tilt Thick shell tilt Angle 5 degrees, large battery. In effect, a tilted battery compartment is added to the bottom of the flat case. The keyboard screen is higher on one side and lower on the other. The new version is already on the way and players who are not urgent can wait for the new version, change, add a knob on the left side, add a joystick on the right side, and replace the screen with nice! The view. So the price went up slightly. The expected delivery date is early August, including nice! view screen two mounted PCB two pieces, housing, battery, knob rocker, not including shaft key cap line.



The QMK solution is not supported. Only the wireless solution such as ZMK is supported
2. Compared with the original corne, the ink screen jack, battery pad and switch are added
3. The key matrix connection is exactly the same as the original corne. corne36 is configured with MX axis hot swap +RGB backlight + ink screen.
4. RGB comparison consumes electricity, care about battery life users can turn off. The linkage between the firmware and the configuration library has been started. When the backlight is turned off, the RGB power supply is automatically cut off, and there is no leakage.

5. Users do not need to pay attention to many functions. The hardware has been assembled well, and users only need to change the keymap part.

6. Tilt the case, tilt 5 degrees, so you can plug the 1200 mah battery under it. The upper part of the structure is a flat shell, and a battery compartment with a tilt Angle of 5 degrees is added below.
It is also possible to install a battery compartment with a 7 degree Angle.
7.corne36 ink screen version key change link, you need to first learn the ZMK the most basic operation can be gitaction key change. That is, modifying the keymap is the key function. https://github.com /a741725193/ zmk -- -- config-zen-2 Please note this link. No screen users can search the corne library of the ZMK scheme themselves, or they can use the above ink screen library, changing display to =n in the parameter is equivalent to turning off the screen function, and then use it.
8. The ink screen is cheap, but it also has its own defects and is slow to refresh.

Hold down and cut to layer1 layer1

Hold down and cut to 2 layers of layer2

Press and hold to cut to Layer 3 layer3 and press Enter

Hold down to cut to Layer 3 layer3 and tap space

Clicking or holding is shift, and pressing twice is capslock


short press and hold on press=shift
quickly press twice=capslock
BT CLR all= Clear Bluetooth connection
BT sel 0 Switch to Bluetooth 0 connection
The RGB switch has been connected to the power output, turning off RGB will automatically cut off the RGB power - save power, so there is no need to use EP_0FF again to turn off the power

Press and hold the 2 layer key and press Q again to enter! The same is true for other symbols
OUTUSB Uses the USB cable channel to output key codes
&trans means the function of the previous layer penetrating down, that is, the function is the same as the previous layer
&none means no function

Long press the thumb keys of both the left and right hands to cut to 3 layers
For example, long press the enter key and press Q to enter F1
&sys_ reset means restart, restart will refresh the screen
&BootLoader Press this key code, the keyboard will jump to the BootLoader mode, that is, incarnation as a U disk, load UF2 firmware to achieve