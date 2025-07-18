# Missing firmware for Intel BE200NGW (iwlwifi-gl-b0-fm-b0-92.ucode and related) on Linux
I’m trying to get the Intel BE200NGW (Wi-Fi 7) wireless card working on my Linux system (PCI ID 8086:272b). The kernel logs indicate the iwlwifi driver is requesting firmware files named like:

    iwlwifi-gl-b0-fm-b0-92.ucode

    iwlwifi-gl-b0-fm-b0-93.ucode

    … up to -96.ucode

However, these firmware files are not available in the official linux-firmware repository or any public mirrors. I’ve searched the git.kernel.org linux-firmware repo and other sources but could not find the gl-b0-fm-b0 firmware binaries.

Could you please advise if these firmwares are released or if there’s an alternative way to obtain them? Also, is there an expected timeline for their public availability?

Thanks a lot!

