# dArkOS_Qemu_Manager
Install &amp; Run Qemu x86 On Your R36S!

dArkOS Qemu Manger for the R36S!

**##--How To Use--##**

1) Download and copy "dArkOS_Qemu_Manager.sh" over to your Tools folder. Also copy your 32bit x86 bootable CD\DVD Images over to anywhere on your ROMs SD Card
2) Make sure your r36s is connected to the internet before trying to select the "Install" option inside the utility. Once installed, you no longer need internet access. It takes around 15min to fully install everything so be patient!
3) Select "Browse & Run" from the main menu, navigate to a bootable image and press A!


**##--Controls--##**
up = up
down = down
left = left
right = right

a = backspace
b = space
x = tab
y = esc

l1 = mouse_left
l1_trigger = mouse_left
r1 = mouse_right
r1_trigger = mouse_right
start = enter
select = esc

hotkey = select
hotkey_start = kill
left_analog_up = mouse_movement_up
left_analog_down = mouse_movement_down
left_analog_left = mouse_movement_left
left_analog_right = mouse_movement_right


**##--Additional Notes--##**

Performance is as you would expect - slow!
Have successfully booted Slitaz Linux 4.0, Windows XP "Live", FreeDOS, and kolibriOS.
USB Mouse & Keyboard works as you would expect and passes through automatically - No need to do anything special here!
Currently only supports bootable cd\dvd images since the qemu launch command is hard coded in the script, but you can just edit the script in a simple text editor to change it to floppies or virtual hdds. I may add auto detect in a future update
Also only allocated 256mb RAM for the virtual machine, but again, trivial to change in a text editor.

This was actually super easy to do over ssh, but was a pain to get started on the device itself. Ended up using the same trick from the dArkOS Desktop Environment Project and ran everything as a service... Good enough!


This is only meant to be a bit of fun!
