You can find the source code under [the "A36Plus" branch of my fork of OpenRTX:](https://github.com/Tunas1337/OpenRTX/tree/A36Plus)

Building a .kdhx is done with the rtxflash utility, which currently has a pending pull request for A36Plus support in both wrapping (creating a .kdhx) and flashing the binary, in a separate branch. That can be found [here.](https://github.com/OpenRTX/rtxflash/tree/a36plus)
Alternatively, you can use [the encrypt.c utility in amoxu's repository.](https://github.com/amoxu/Baofeng-UV-5RM-5RH-RE/blob/main/reverse_engineering/encrypt.c) That only creates a kdhx file, and you can use the TalkpodBootloader to flash it.

Please make sure you checkout the specific branches for the A36plus, as this work isn't mainlined quite yet in either case.
