<p align="center">
  <img src="https://github.com/user-attachments/assets/297cbc29-4c93-4229-b037-b0ece7978178" width="50%" alt="MicrOreoG Banner">
</p><img 




<img width="800" height="360" alt="6e50d107-b749-408b-8a87-60a6df56" src="https://github.com/user-attachments/assets/a49588f4-baf1-4e5d-8dfc-4d52430b944f" />


# MicroG Port to RestlessOS (MicrOreoG) (UNOFFICIAL)
## Made by OreoCheiroso

This repository provides a functional, ***unofficial*** port of microG for RestlessOS.

It contains only the files required to work around the installation restrictions imposed by ***RestlessOS***, allowing microG to be installed on the system.

> [!NOTE]
> ### Please note that this is an unofficial project and is not affiliated with or endorsed by the RestlessOS or microG developers.

<img width="25" height="25" alt="MicrOreoG" src="https://github.com/user-attachments/assets/53a521c0-02bd-41cb-9934-8ba826912675" />  MicrOreoG

### An unofficial microG port for RestlessOS, developed by Oreo.

> [!IMPORTANT]
> - Root access is mandatory. You need Magisk, KernelSU, APatch, or another compatible root manager.
> - Requirements
> - A device running RestlessOS.
> - Root access.
> - ADB access.

# Installation Guide

### Requirements
Root access is mandatory. A rooted device is required to install microG using this port.
A device running RestlessOS.
A PC with/or Access to ADB

### Step 1: Download and Install the Original microG APKs
Download the original microG APKs from the official microG GmsCore v0.3.17.252432 release page.
- Download the following two APKs:
`com.android.vending` — microG Companion.
`com.google.android.gms` — microG Services.

## Important: Download the standard versions of these APKs, not the Huawei-specific versions.

### Using a terminal with ADB access, navigate to the directory where you downloaded the APKs and install both applications using the following commands:

- Install [microG Services](https://github.com/microg/GmsCore/releases/download/v0.3.17.252432/com.android.vending-84022634.apk):

```bash
adb install com.google.android.gms-250932034.apk
```


- Install [microG Companion](https://github.com/microg/GmsCore/releases/download/v0.3.17.252432/com.google.android.gms-252432034.apk):

```bash
adb install com.android.vending-84022634.apk
```

- Install [FakeGApps](https://github.com/thermatk/FakeGApps/releases/tag/2.0):

```bash
adb install FakeGApps2.apk
```

> [!NOTE]
> If the downloaded APK filenames differ, replace the filenames in the commands with the actual names of your downloaded files.

### Step 2: Install the MicrOreoG Module

After installing both APKs, download the MicrOreoG module from this repository.

Install and enable the module using your preferred root manager, such as KernelSU, APatch, or Magisk.

> [!WARNING]
> Root access is mandatory for this installation method.

### Step 3: Reboot Your Device

Once the module is installed and enabled, reboot your device.

After rebooting, microG should be ready to use on RestlessOS!


> [!WARNING]
> Do not install the Google Play Store or Google Play Services from the App Store. Having these applications installed alongside this setup may cause package conflicts and prevent microG from working correctly.

## Make sure you follow every step carefully for the best results.

> [!IMPORTANT]
> This repository only provides the necessary files for the unofficial port. Please follow the linked tutorial for the complete installation process.
