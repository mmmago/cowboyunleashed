# Legal Notice / Disclaimer
**1. I am not responsible to anything worse that could happen to your bike because of this app**

**2. Be careful that lifting the 25km/h limit could make your bike not eligible to ride on streets and public space and therefore make it illegal, please use in private areas**

**3. This app could void your warranty**

**4. The app is still in beta phase, bugs might be sneaking around (nothing harmful).**



# cowboyunleashed
An iOS app to lift the speed limit of your Cowboy Bike. 


![repository-opaaen-graph-template](https://user-images.githubusercontent.com/76073612/149851972-9bbeed50-0823-4da1-b744-0e3f4f4e59ca.png)


This iOS app allows you to debrid your Cowboy (C1 -> C4) bike and make it a bit more fun and easy to ride, and allows you to read some internal bike values.

- App compatible with all iPhones iOS 13 -> iOS 15
- Confirmed working on cowboy **firmware 4.15** and lower.



# Shout out

Please give a lot of credit to [Imaginous](https://github.com/Imaginous) for **[Cowboy Untamed](https://github.com/Imaginous/Cowboy_Untamed)** and [Runerune](https://github.com/runerune) for **[Bronco](https://github.com/runerune/BroncoUnleashed)** (open source! ), without them there wouldn't even be any way to tweak our bikes. You will also find a lot of useful infos about the settings you'll find in the app on their page.


# Donate

This took a few late night works and a bit of headache as someone new to iOS programming. If you're down to receive updates and improvements, please send feedbacks and don't hesitate [**to donate**](https://linktr.ee/mmmago).

# Preview


![ezgif-aaaa2-4bd3e1781b](https://user-images.githubusercontent.com/76073612/162585800-dafea821-1c84-4d49-9c47-1e60deb0575c.gif)
 <img width="327" alt="Capture d’écran 2022-03-11 à 13 54 26" src="https://user-images.githubusercontent.com/76073612/157870453-a4b45dd5-9364-4ff6-ba1b-ba5400760c57.png">



# Download / Installation
[**Download the IPA here**](https://github.com/mmmago/cowboyunleashed/releases)!


### You don't need to be jailbroken and don't need an apple developper account to install it.

As this app is not on the appstore (yet ?), you need to **sideload it** your favourite way. [Sideloadly](https://sideloadly.io/) can help you with that, but there are other ways (e.g. [Altstore](https://altstore.io/) ). **Be careful that the app will need to be re-installed / re-signed every 7 days in order to work as this is how apple restricts sideloading.** ([things might change soon](https://www.macrumors.com/2022/03/17/eu-sideloading-bill-coming-soon/))

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

If you're jailbroken, you can simply add https://mmmago.github.io/repo/ to your Sileo / Cydia sources and install the app from there.

###### *Tip for jailbroken users : you can combine Bakgrunnur, Activator, and settings in Unleashed to automate lock / unlock the way you want, I did with a volume down + sleep button press to unlock the bike.* 


# Main features

1. Alternative dashboard 
- Basic navigation capabilitites using Apple MapKit
- Long press assistance button to disable / enable speed limit
- While disabled, press assistance button to switch between speed modes (customizable in settings).
2. Customize or disable the 25km/h speed limit 
3. Edit field weakening parameter (increase assistance help in higher speeds)
4. Enable *Auto Unlock* on the C1+
5. Edit Hall Interpolation Transitions (HIT) (resolve motor judder at startup)
6. Edit blinking rear light sensivity when you brake
7.  Reset PCB (printed circuit board). Not resetting any settings made before with the app. Might resolve some light bug on the C1+ and overall connectivity problem.


The app is automatically scanning bluetooth devices around and will ask you to unlock your bike if it founds it. Set the settings you need, try them on, then if you want to keep them, press "flash", which will also lock your bike.

The settings are not stored until you don't press "flash", so if you just want to try some settings or use them for your current ride, apply them without storing. Locking the bike will dismiss them. Note that anyway, **all changes are reversible**, as you can set everything to default. (Speed limit enabled, FW 0%, HIT 1).

Exemple of settings to apply : 

- Remove speed limit / FW 15% ( / test ) / flash
- Enable speed limit / FW 0% / flash (reset to default)


## Quick Actions presets :

<img width="254" alt="Capture d’écran 2022-04-09 à 21 21 52" src="https://user-images.githubusercontent.com/76073612/162588738-6f86eaf2-beef-44be-9550-f0f293b871e0.png">

V1.2 allows you to choose a preset via Quick Action. Currently, you have to make sure the app is already launched and connected to your unlocked bike to select them. These are not stored once you apply them.

- Default Speed : Speed limit enabled / FW 0%
- Speed Mode 1 : Speed limit disabled / FW 15%
- Speed Mode 2 : Speed limit disabled / FW 18%

These are the default values. v4.1 allows to tweak them.

