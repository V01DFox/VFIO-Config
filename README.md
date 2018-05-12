# V 0 1 D's VFIO Config
This is the config for my personal VFIO setup.
The hardware used is as follows:
* Intel I7-5960X
* Nvidia GTX 980Ti (Host), Nvidia GTX 1080Ti (Guest)
* 4K 60Hz Display (Host), 1440p 144Hz Display (Guest)
* 32GB RAM
* 1 Mouse, 1 Keyboard

Here's some features of the setup:
* Manjaro Host, Windows 10 Guest
* 1 Socket, 4 cores isolated for guest, 1 thread per core
* 16GB Huge pages for the guest machine
* evdev setup for the mouse and keyboard input
* PulseAudio ac97 for audio passed back to the host
* Avoiding Nvidia Error 43 on the drivers

Drawbacks
* Refresh rate can only reach 120hz, not 144hz.
