

# <img width="50" alt="unleasged" src="https://user-images.githubusercontent.com/76073612/224371068-4364b7a5-bb95-4417-a5d0-2e95d5c08cc1.png"> cowboy unleashed
An iOS app to lift the speed limit of your Cowboy Bike. 

# Legal Notice / Disclaimer

   **1. I cannot be held responsible for any damage or harm that may occur to your bike as a result of using this app.**

**2. Please be aware that removing the 25km/h speed limit may render your bike unsuitable for use on public roads and spaces, and as such may be considered illegal. Please only use the app in private areas.**

**3. Using this app may invalidate your warranty. Starting April 2023, Cowboy seems to effectively void warranty of bike using this app, as stated in the [terms of use](https://cowboy.com/fr/pages/terms-of-use) (8.7).**

**4. Please note that the app is still in its beta phase, and although any bugs are not expected to cause harm, they may still exist.**

# Usage

This iOS app enables you to debrid your Cowboy (C1 -> C4) bike, which enhances its riding experience and makes it more enjoyable. Additionally, the app allows you to view some internal bike metrics.

- Compatible with all iPhones iOS 13 -> iOS 16
- Confirmed working on cowboy **firmware 4.17** and lower.

#### Note for users of C4(ST) on 4.17 firmware and AdaptivePower: The app does not alter how the motor power is delivered; it simply removes the speed limit, so it is still fully compatible. However, adjusting your bike to "ECO" mode may override and affect the speed settings.


# Shout out

Please give a lot of credit to [Imaginous](https://github.com/Imaginous) for **[Cowboy Untamed](https://github.com/Imaginous/Cowboy_Untamed)** and [Runerune](https://github.com/runerune) for **[Bronco](https://github.com/runerune/BroncoUnleashed)** (open source! ), without them there wouldn't even be any way to tweak our bikes. You will also find a lot of useful infos about the settings you'll find in the app on their page.


# Donate

Creating this app required several late-night sessions and some headaches, especially since I am new to iOS programming. If you would like to receive future updates and improvements, please provide your feedback and consider supporting me by [**donating**](https://linktr.ee/mmmago).

# Preview


![ezgif-aaaa2-4bd3e1781b](https://user-images.githubusercontent.com/76073612/162585800-dafea821-1c84-4d49-9c47-1e60deb0575c.gif)
 <img width="327" alt="Capture d’écran 2022-03-11 à 13 54 26" src="https://user-images.githubusercontent.com/76073612/157870453-a4b45dd5-9364-4ff6-ba1b-ba5400760c57.png">



# Download / Installation
[**Download the IPA here**](https://github.com/mmmago/cowboyunleashed/releases)!

As this app is not on the appstore, you need to **sideload it** your favourite way. The process is quite easy, [Sideloadly](https://sideloadly.io/) can help you with that, but there are other ways (e.g. [Altstore](https://altstore.io/), [Scarlett](https://usescarlet.com/) ).

**If using Sideloadly or AltStore, be careful that the app will need to be re-installed / re-signed every 7 days in order to work as this is how apple restricts sideloading.** ([things will change soon with iOS 17](https://techcrunch.com/2022/12/14/apple-will-reportedly-allow-sideloading-apps-with-ios-17/) )

##### If your device is compatible (iOS 14.0 - 15.1.1), you can use [Trollstore](https://trollstore.app/) to keep the app indefinitely.

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
- Basic navigation capabilitites using Apple MapKit
- Long press assistance button to disable / enable speed limit
- While disabled, press assistance button to switch between speed modes (customizable in settings).
2. Customize or disable the 25km/h speed limit 
3. Edit the field weakening parameter to increase assistance at higher speeds.
4. Enable *Auto Unlock* on the C1+
5. Edit the Hall Interpolation Transitions (HIT) to resolve motor judder at startup.
6. Edit blinking rear light sensivity when you brake
7.  Reset the PCB (printed circuit board), which might resolve some minor issues with the C1+ and improve connectivity. Note that this won't reset any other settings made with the app.
8. Read other bike values, such as battery cicles

The app automatically scans for Bluetooth devices and prompts you to unlock your bike if it finds it. Set the desired settings, try them out, and if you wish to keep them, press "flash," which will also lock your bike.

### To clarify, you can use both this app and the Cowboy app, but not at the same time, as this might prevent the bike from being detected. Once the settings are flashed into the bike, they are stored and not dependent on this app.

The settings are not stored until you press "flash." If you only want to try some settings or use them for your current ride, apply them without storing (with the "flash" button). Locking the bike will dismiss them. Note that all changes are reversible, and you can set everything to default (speed limit enabled, FW 0%, HIT 1).

Example of settings to apply : 

- Remove speed limit / FW 15% ( / test ) / flash
- Enable speed limit / FW 0% / flash (reset to default)

Enabling speed limit and settings any field weakening values have no effect.


## Quick Actions presets :

<img width="254" alt="Capture d’écran 2022-04-09 à 21 21 52" src="https://user-images.githubusercontent.com/76073612/162588738-6f86eaf2-beef-44be-9550-f0f293b871e0.png">

V1.2 allows you to choose a preset via Quick Action. Currently, you have to make sure the app is already launched and connected to your unlocked bike to select them. These are not stored once you apply them.

- Default Speed : Speed limit enabled / FW 0%
- Speed Mode 1 : Speed limit disabled / FW 15%
- Speed Mode 2 : Speed limit disabled / FW 18%

These are the default values. v4.1 allows to tweak them.

