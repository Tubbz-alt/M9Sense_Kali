# Kali Nethunter for the HTC One M9.
![Kali NetHunter](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/images/nethunter-git-logo.png)
HTC One M9, with magic.

This is based on the ElementalX 5 kernel for the One M9, with the additions of 802.11 RAW frame injection support and various device drivers that you'd expect from a Nethunter device (Atheros and Realtek drivers to name a few). A keyboard gadget patch  has also been implemented! So in a gist, this project is fully "Nethunter compliant".

# Issues.
This is perhaps the worst kernel source I've ever had to work with. Plagued with compilation issues and took a lot of time to figure out workarounds to get the piece of crap to compile properly (which also takes forever to complete, whereas my previous HTC device kernels compile within 5 minutes or less!).

On the bright side, I've got it to build!

# Kernel sources.

Source code for the modified kernel(s) can be found [here](https://github.com/lavanoid/ElementalX-m9)

Currently the only supported ROM is 7.0 Nougat Sense, though there may be support for other ROMs in the future.


# Compiling.

I've only managed to get this to compile on Manjaro Linux/Arch. Just run the build script and you should soon have a Kali Nethunter installer.

    bash ./build.sh


If the script is ran successfully, you should have an installer zip file that will allow you to flash Kali Nethunter onto your device through the recovery menu (TWRP is recommended). To find out where the installer is located, use your eyes and the terminal output should tell you where it is.

 I DO NOT take responsibility for whatever the outcome that may occur when you fiddle around with this and your device.

# My other projects
- Kali Nethunter for the One M8: https://github.com/lavanoid/M8GPE_Kali
- Kali Nethunter for the One M7: https://github.com/lavanoid/M7GPE_Kali
