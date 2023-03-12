[<<< Back](https://github.com/ayaneotools/info/blob/main/README.md)

# Known issues with the Ayaneo 2

It has been discovered by the community that the Ayaneo 2 with the 2TB SSD 
has seen much higher then expected failure rates as opposed to the 1TB or 
other devices. Thankfully, this only seems to by the fault of the "CingKo" 
brand of SSDs.

Ayaneo *is* aware and has acknowledged the issue, however in the meantime 
and depending on the situation you are in, you might want to continue 
reading.

| Device Model | SSD Size | Device State | What to do |
| --- | --- | --- | --- |
| Ayaneo 2 | 1TB | - | Unaffected |
| Ayaneo 2 | 2TB | Working | [Firmware Upgrade](#upgrading-the-firmware-on-the-2tb-cingko-ssd) |
| Ayaneo 2 | 2TB | Dead SSD | *add support route* |
| Ayaneo 2 | 2TB | Dead SSD | *add diy route* |

# Upgrading the Firmware on the 2TB CingKo SSD

***Before you begin, please ensure all important data is backed up prior to this process, I am not responsible for any data loss or hardware damage following the firmware 
upgrade, if your Ayaneo 2 explodes into a ball of fire following this, it is not my fault, nor is it Ayaneo's fault, continue at your own risk.***

*A majority (all) of this guide is reworded from the official guide released from Ayaneo, it is available [here](https://ayaneo.com/article/247).*

#### Verifying your SSD model:
1. Open `Device Manager`
2. Expand `Disk drives`
3. Confirm that your SSD is `CingKo 2000GB` or similar. (if yours is different at all, please open an issue with a screenshot and information about your device, thanks!)
4. If your device is **not** the same as above, do not continue, feel free to open an issue for more advice :)

#### Upgrading the CingKo Firmware
1. Download the Firmware Upgrade Tool from [here](https://cdn.ayaneo.com/ayaneo/downloads/UpgradeTool%20ver2.0.zip).
2. Extract the .zip file
3. Run `UpgradeTool ver2.0.exe` as Administrator
4. The tool will display the currently installed firmware, this should be `Firmware: 3.W.J.1`, if it is `Firmware: 3.W.J.1t`, this is the version that is already fixed 
and you do **not** need to continue.
5. However, if your SSD Firmware is out of date and is eligible to upgrade, ensure your SSD is selected and press `> Run` to begin the firmware upgrade.
6. Reboot your Ayaneo 2 to ensure you are now running the latest SSD firmware version.
