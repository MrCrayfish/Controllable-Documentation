---
description: >-
  GlosSi is an open source tool that enables the ability to use Steam Input with
  incompatible games (like Minecraft). It creates a emulated gamepad that is
  available system-wide.
---

# Method 2: GlosSI

{% hint style="info" %}
GlosSi is only available for Windows. As such, this method will not work on Mac or Linux.
{% endhint %}

#### Pros

* Connect using USB or Bluetooth
* Supports a huge varity of gamepads. See [Steam Input documentation](https://partner.steamgames.com/doc/features/steam\_controller/device)
* Compatible with non-steam games like Minecraft Dungeons
* Full access to the controller configuration options and layout settings in Steam

#### Cons

* Windows only
* Steam must be installed on your system
* Requires additonal drivers and libraries to be installed

## Installation

{% hint style="warning" %}
Ensure Steam is installed on your system before continuing with installation.
{% endhint %}

### Method 1: Using the Installer <mark style="color:green;">(Recommended)</mark>

Head to the [GlosSI downloads page](https://glossi.flatspot.pictures/#downloads) and download the Installer.&#x20;

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>The version shown in the image may no longer be the latest version.</p></figcaption></figure>

After the installer has finished downloading, simply run the file and it'll guide you through the steps to install **GlosSI**. It is important that when it allows you select which components to install, that every component is ticked otherwise **GlosSI** will not work. After the installation is complete, untick `Run GlosiSI` and click `Finish`.

{% hint style="warning" %}
You will need to restart your system after the installing GlosSI
{% endhint %}

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Ensure all components are ticked in order to GlosSI to operate correctly</p></figcaption></figure>

After you've restarted your system, open Steam and turn on **Xbox Configuration** in Controller settings. This can be accessed from `Steam > Settings > Controller > General Controller Settings` then tick `Xbox Configuration Support`.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Tick Xbox Configuration Support otherwise GlosSI will not work correctly</p></figcaption></figure>

Next you'll need to add **GlosSI** as a non-steam game. You can Add a Game by clicking `Games > Add a Non-Steam Game to My Library`. This will bring up a window and you want to tick `GlosSI-Target` as the game to add. **Do not tick the other GlosSI file.** Finally click `Add Selected Programs` and it will be added to your Steam library.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Tick GlosSI-Target only</p></figcaption></figure>

Finally find `GlosSI-Target` in your library and hit `Play`. You can test if **GlosSI** is working by using [Gamepad Tester](https://gamepad-tester.com/). It should appear as an Xbox Controller, which means **GlosSI** is working correctly.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Your controller should appear as an Xbox Contoller if GlosSI is working correctly</p></figcaption></figure>

You are now ready to play Minecraft with Controllable!

### Method 2: Installing Manually

Head to the [GlosSI downloads page](https://glossi.flatspot.pictures/#downloads) and download the ZIP.&#x20;

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Extract the contents of the ZIP to an empty directory. This directory is where **GlosSI** files will live, so create it somewhere that it won't get deleted.&#x20;

Open the directory you just extracted the files into and run the following files in this order. _Make sure you complete the installation of a file before running the next one._

1. vc\_redist\_x64.msi  <mark style="color:orange;">(A library for GlosSI)</mark>
2. ViGEmBusSetup\_x64.exe <mark style="color:orange;">(Kernal-mode driver to emulate a controller)</mark>
3. HidHideSetup.exe <mark style="color:orange;">(A tool that hides devices so you controller doesn't appear twice)</mark>

{% hint style="warning" %}
You will need to restart your system after the installing the files
{% endhint %}

After you've restarted your system, open Steam and turn on **Xbox Configuration** in Controller settings. This can be accessed from `Steam > Settings > Controller > General Controller Settings` then tick `Xbox Configuration Support`.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Tick Xbox Configuration Support otherwise GlosSI will not work correctly</p></figcaption></figure>

Next you'll need to add **GlosSI** as a non-steam game. You can Add a Game by clicking `Games > Add a Non-Steam Game to My Library`. Click `Browse` and locate the file `GlosSITarget.exe` in the directory you extracted the files. Finally click `Add Selected Programs` and it will be added to your Steam library.

Finally find `GlosSITarget` in your library and hit `Play`. You can test if **GlosSI** is working by using [Gamepad Tester](https://gamepad-tester.com/). It should appear as an Xbox Controller, which means **GlosSI** is working correctly.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Your controller should appear as an Xbox Contoller if GlosSI is working correctly</p></figcaption></figure>

You are now ready to play Minecraft with Controllable!

## More Information

GlosSI Homepage: [https://glossi.flatspot.pictures/](https://glossi.flatspot.pictures/)

GlosSI GitHub: [https://github.com/Alia5/GlosSI](https://github.com/Alia5/GlosSI)
