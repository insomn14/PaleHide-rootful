# PaleHide-Rootful Guide
---
**Supported Devices:** A8–A11 (iPhone 6s through iPhone X)
**Supported iOS:** 15.0 – 18.x

**Prerequisites:** Connect your supported iPhone device to your computer/laptop via USB to Lightning cable.

## Phase 1: Creating the Rootful Filesystem (FakeFS)
1. **Enter DFU Mode:** Put your iPhone into DFU (Device Firmware Update) Mode. (You will need to follow the on-screen instructions from palera1n to do this.)

2. **Setup FakeFS:**
Run this command to create the necessary rootful partition.

```Bash
./palera1n-macos-universal -cf
```
_(Wait for this process to complete. It may take a long time.)_


## Phase 2: Jailbreak and First Boot
3. **Initiate PaleHide Rootful Boot:**
Run your custom script to boot the device with the custom PaleHide rootful environment.

```Bash
./palehide-rootful.sh
```
_(The device will reboot into a jailbroken state.)_

## Phase 3: Post-Jailbreak Setup
4. **Install Package Manager:** On your iPhone, open the palera1n Loader app and select your preferred package manager (e.g., Sileo or Zebra) to install it.

5. **Install TrollStore:** Using the package manager you just installed, find and install the TrollStore helper (or follow the standard TrollStore installation method for your iOS version).

6. **Install PaleHide Loader:** Use TrollStore to install the Jailbreak.tipa file.

7. **Finalize Jailbreak:** Open the app you installed in the previous step (which is the actual PaleHide loader/Dopamine variant) and run the final jailbreak action to enable tweaks.
