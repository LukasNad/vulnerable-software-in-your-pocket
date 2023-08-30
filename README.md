# Vulnerable Software in Your Pocket

This repository is for the seminar and workshop that take place on December 13th 2022 at UPJS Košice.

## Environment Setup

1. Download and install JADX-GUI (<https://github.com/skylot/jadx/releases>).
2. Download and install Android Studio (<https://developer.android.com/studio>) and note down the SDK installation folder.
3. Download the files from this repository.
4. Open the project `InsecureBroadcastReceiverDEMO` (from the `ExploitSources` folder) in Android Studio.
5. Launch the Device Manager and create a new Android Virtual Device with the following properties: Pixel 6, Android 9.0 (Pie) x86_64 **without** Google APIs.
6. Add Android studio SDK `platform-tools` to PATH. Default `platform-tools` location is C:\Users\\<CURRENT_USER>\AppData\Local\Android\Sdk\platform-tools.

### Troubleshooting

If you get an error message saying that "Android Emulator Hypervisor Driver installation failed", enable CPU virtualization in BIOS.

## Useful Links

- Interactsh Web Client: <https://app.interactsh.com/>
- URL Encode/Decode: <https://www.url-encode-decode.com/>
- InsecureShop: <https://www.insecureshopapp.com/>

