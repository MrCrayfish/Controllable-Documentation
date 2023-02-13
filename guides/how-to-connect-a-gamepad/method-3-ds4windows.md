---
description: >-
  DS4Windows is an open source tool that adds support for Playstation and
  Nintendo controllers. It creates an emulated gamepad that is available
  system-wide and is detectable by Controllable.
---

# Method 3: DS4Windows

{% hint style="info" %}
DS4Windows is only available for Windows. This method will not work on Mac or Linux
{% endhint %}

{% hint style="warning" %}
DS4Windows is no longer supported on Windows 8.1 and below. If you have issues with the software, it will not be fixed.
{% endhint %}

#### Pros

* Connect using USB or Bluetooth
* Compatible with games like Minecraft Dungeons
* Supports PS4/PS5, Switch Pro Controller, Joycons and more!
* Portable application. Doesn't need to be installed.
* Doesn't need Steam (when compared to [GlosSI](method-2-glossi.md))

#### Cons

* Windows only
* Requires additonal drivers and libraries to be installed
* Limited amount of supported gamepads. See DS4Windows' [Supported Controllers](https://ds4-windows.com/supported-controllers/) for a full list.

## Installation

### Prerequisites <a href="#prerequisites" id="prerequisites"></a>

**DS4Windows** requires `.NET 6.0 Desktop Runtime` to be installed. This library is developed by Microsoft for building desktop windows applications.

You can download and install the library by clicking the link below.&#x20;

[https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.10-windows-x64-installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.10-windows-x64-installer)

After you've installed `.NET` you can continue to the next step.

### Setting up DS4Windows

Head to [DS4Windows releases page](https://github.com/Ryochan7/DS4Windows/releases) and download the latest version.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption><p>The version shown in the image may no longer be the latest version.</p></figcaption></figure>

Extract the contents of the ZIP to an empty directory. This directory is where **DS4Windows** files will live, so create it somewhere that it won't get deleted. Open the directory where the files were extracted and launch the file `DS4Windows.exe`

On the first load of the application, you will be required to install `ViGEmBus` driver. This driver is responsible for creating an emulated gamepad, which is detectable by Controllable. **DS4Windows** will also give you the option to install `HidHide`, which is highly recommended. This driver hides your real controller so it doesn't appear twice on your system.

{% hint style="warning" %}
You will need to restart your system after the installing these drivers
{% endhint %}

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

After you've restarted your system, open **DS4Windows** again and plug in your controller. It should automatically detect your controller and start. If it doesn't, you can simply click the `Start` button in the bottom right.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption><p>Click the start button in the bottom right if it doesn't automatically start</p></figcaption></figure>

Once started, your controller will appear in the list.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

You can test if **DS4Windows** is working by using [Gamepad Tester](https://gamepad-tester.com/). It should appear as an Xbox Controller by default, which means **DS4Windows** is working correctly.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

### Hiding Your Real Device

Unlike [GlosSI](method-2-glossi.md), **DS4Windows** will not hide your real controller by default. This means that when you select your controller from the Controllable selection list, you may see two entries. One being your real controller and the other is the emulated version provided by **DS4Windows**. This may be an issue because Controllable selects the first controller when Auto Select is enabled.&#x20;

You will need to have the `HidHide` driver installed. If you didn't install this on the first load, the installation setup can be accessed again by going to the `Settings` tab and clicking `Controller/Driver Setup` in the `Utils` section. You will need to restart your system if you didn't have it installed.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

You can hide you real controller in **DS4Windows** by navigating to the `Settings` tab and clicking `HidHide Configuration Client` in the `Utils` secotion. Next click the `Devices` tab and tick the `Enable device hiding` option.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

You can now close the window. If your controller was connected, you'll need to disconnect and reconnect your controller for the option to take effect.

You are now ready to play Minecraft with Controllable!

## More Information

DS4Windows Troubleshooting: [https://docs.ds4windows.app/troubleshooting/](https://docs.ds4windows.app/troubleshooting/)

DS4Windows GitHub: [https://github.com/Ryochan7/DS4Windows](https://github.com/Ryochan7/DS4Windows)

Supported Controllers: [https://docs.ds4windows.app/about/supported-gamepads/](https://docs.ds4windows.app/about/supported-gamepads/)
