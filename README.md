# <img width="50" alt="unleashed" src="https://files.catbox.moe/zhuu6x.png"> cowboy unleashed

An iOS app to lift the speed limit of your Cowboy Bike — now rebuilt in SwiftUI.

# Legal Notice / Disclaimer 

**1. I cannot be held responsible for any parts damage or harm that may occur to your bike as a result of using this app.**

**2. Please be aware that removing the 25km/h speed limit may render your bike unsuitable for use on public roads and spaces, and as such may be considered illegal. Please only use the app in private areas.**

**3. Using this app may invalidate your warranty. Starting April 2023, Cowboy seems to effectively void warranty of users that have made usage of this app, as stated in the [terms of use](https://cowboy.com/pages/terms-of-use).**

**4. Unlike others applications charging you by trying to mimic the behaviour of this app with some fancy UI, this one will remain available to download for free, and won't be removed of any app store. :-)**

# Usage

This iOS app enables you to debrid your Cowboy (C1 -> Cross) bike, which enhances its riding experience and makes it more enjoyable. Additionally, the app allows you to view some internal bike metrics.

- Compatible with all iOS devices
- Confirmed working on cowboy **firmware 4.21.X** and lower.

#### Note for AdaptivePower 2.0 : [It looks like there is some issue with Adaptive Power 2.0 on some Cowboy C4](https://github.com/Imaginous/Cowboy_Untamed/issues/41), so please avoid the latest firmwares for now if you can.

# Shout out

Please give a lot of credit to [Imaginous](https://github.com/Imaginous) for **[Cowboy Untamed](https://github.com/Imaginous/Cowboy_Untamed)** and [Runerune](https://github.com/runerune) for **[Bronco](https://github.com/runerune/BroncoUnleashed)** (open source! ), without them there wouldn't even be any way to tweak our bikes. You will also find a lot of useful infos about the settings you'll find in the app on their page.

# Donate

Creating this app required several late-night sessions and some headaches, especially since I am new to iOS programming. If you would like to receive future updates and improvements, please provide your feedback and consider supporting me by [**donating**](https://linktr.ee/mmmago).

<p align="center"> <a href="https://www.buymeacoffee.com/unleashedapp" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a> <p>

# Preview

<p align="center">
  <img width="220" alt="Home - locked (dark)" src="https://files.catbox.moe/80ae94.PNG">
  <img width="220" alt="Home - searching (light)" src="https://files.catbox.moe/jxwfgv.PNG">
  <img width="220" alt="Diagnostics" src="https://files.catbox.moe/iam1j8.PNG">
  <img width="220" alt="Assistance" src="https://files.catbox.moe/6ml9rj.PNG">
</p>

# Download / Installation

An IPA build is available in the [release tab](https://github.com/mmmago/cowboyunleashed/releases/tag/v5.0).

As this app is not on the appstore, you need to **sideload it** your favourite way. The process is quite easy, [Sideloadly](https://sideloadly.io/) can help you with that, but there are other ways (e.g. [Altstore](https://altstore.io/), buying a cheap certificate on [Flarestore](https://flarestore.vip/) to sideload, ... ).

**If using Sideloadly or AltStore, be careful that the app will need to be re-installed / re-signed every 7 days in order to work as this is how apple restricts sideloading. I am not planning to release this on the AppStore or any alternative store if they need to be review by Apple.**

##### If your device is compatible, you can use [Trollstore](https://trollstore.app/) to keep the app indefinitely.

## Installation tutorial

### Sideloadly

- [Simply install sideloadly](https://sideloadly.io/) (mac/win), log your Apple ID email, and drag the IPA inside the app to install it on your phone.
- Then, on your phone, you might have to go under Settings -> General -> Profiles and authorize the app by clicking on it.
- Profit

### AltStore

- [Installation process can be found here](https://altstore.io/faq/)
- Download the .ipa directly via your iphone
- Go through your file, select the app and "Install with AltStore"
- Profit (you can re-sign the app every 7 days directly via AltStore)

##### If you don't know anything about sideloading, [here is a guide](https://www.reddit.com/r/sideloaded/comments/orqzau/guide_a_complete_beginners_guide_to_sideloading/).

# Main features

1. Alternative dashboard
   - Live speed and battery readout, with a bike render that reflects connection and unlock state.
   - Tap Light / Assist to toggle them directly from the home screen.
2. Customize or disable the 25km/h speed limit
3. Edit the field weakening parameter to increase assistance at higher speeds.
4. Edit the Hall Interpolation Transitions (HIT) to resolve motor judder at startup.
5. Reset the PCB (printed circuit board), which might resolve some minor issues with the C1+ and improve connectivity. Note that this won't reset any other settings made with the app.
6. Reset every setting back to its safe default (speed limit on at 27km/h, field weakening 0%) in one confirmed action.
7. Read other bike values, such as battery cycles and field weakening, plus a manual register reader for advanced diagnostics.

The app automatically scans for Bluetooth devices and prompts you to unlock your bike if it finds it. Set the desired settings, try them out, and if you wish to keep them, press "Flash settings to bike," which will also lock your bike.

### To clarify, you can use both this app and the Cowboy app, but not at the same time, as this might prevent the bike from being detected. Once the settings are flashed into the bike, they are stored and not dependent on this app.

The settings are not stored until you press "Flash settings to bike." If you only want to try some settings or use them for your current ride, apply them without storing. Locking the bike will dismiss them. Note that all changes are reversible, and "Reset to defaults" will set everything back to a known-safe state (speed limit enabled, FW 0%) and flash it for you.

Example of settings to apply:

- Remove speed limit / FW 15% ( / test ) / flash
- Enable speed limit / FW 0% / flash (reset to default)

