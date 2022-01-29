# Legal Notice
**1. I am not responsible to anything worse that could happen to your bike because of this app**

**2. Be careful that lifting the 25km/h limit could make your bike not eligible to ride on streets and public space and therefore make it illegal, please use in private areas**

**3. This app could void your warranty**



# cowboyunleashed
An iOS app to lift the speed limit of your Cowboy Bike. 


![repository-opaaen-graph-template](https://user-images.githubusercontent.com/76073612/149851972-9bbeed50-0823-4da1-b744-0e3f4f4e59ca.png)


This iOS app allows you to debrid your Cowboy (C1 -> C4) bike and make it a bit more fun and easy to ride. I've only tested it on my C3 right now and it is working as intended.

Working on my SE 2020 iOS 14.3, but should be working on all devices >iOS 13.

# Shout out

Please give a lot of credit to [Imaginous](https://github.com/Imaginous) for **[Cowboy Untamed](https://github.com/Imaginous/Cowboy_Untamed)**, without him there wouldn't even be any way to tweak our bikes. You will also find a lot of useful infos about the settings you'll find in the app on his page.

# Donate

This took a few late night works and a bit of headache as someone new to iOS programming. If you're down to receive updates and improvements, please send feedbacks and don't hesitate [**to donate**](https://www.paypal.com/donate/?hosted_button_id=TUH8ECY3KP4BW).

# Download / Installation
[**Download the IPA here**](https://github.com/mmmago/cowboyunleashed/releases)

As this app is not on the appstore, you need to **sideload it** your favourite way. [Sideloadly](https://sideloadly.io/) can help you with that, but there are other way. **Be careful that the app will need to be re-installed / re-signed every 7 days in order to work as this is how apple restricts sideloading.** 

Please see [installation tutorial](https://github.com/mmmago/cowboyunleashed/blob/main/Installation%20tutorial.md).


If you don't know anything about sideloading, [here is a guide](https://www.reddit.com/r/sideloaded/comments/orqzau/guide_a_complete_beginners_guide_to_sideloading/).

If you're jailbroken, you can simply download it on your files and install it through [ReProvision](https://repo.packix.com/package/jp.soh.reprovision) and the auto-resign will do his job. I might create a repo later to install it directly through Sileo / Cydia.

# Preview

 
![Capture d’écran 2022-01-30 à 00 14 07](https://user-images.githubusercontent.com/76073612/151680600-1dc3fd09-9d7d-4ae4-b27e-2990a6fc06f2.png)



# Main features

- Disable the 25km/h speed limit 
- Edit field weakening parameter (increase assistance help in higher speeds)
- Enable *Auto Unlock* on the C1+
- Edit Hall Interpolation Transitions (HIT) (resolve motor judder at startup)
- Reset PCB (printed circuit board). Not resetting any settings made before with the app. Might resolve some light bug on the C1+ and overall connectivity problem.

The app is automatically scanning bluetooth devices around and will unlock your bike if it founds it. Set the settings you need, try them on, then if you want to keep them, press "flash", which will also lock your bike.

The settings are not stored until you don't press "flash", so if you just want to try some settings or use them for your current ride, apply them without storing. Locking the bike will dismiss them. Note that anyway, **all changes are reversible**, as you can set everything to default. (Speed limit enabled, FW 0%, HIT 1).

Exemple of settings to apply : 

- Remove speed limit / FW 15% ( / test ) / flash
- Enable speed limit / FW 0% / flash (reset to default)

## Quick Actions presets :

<img width="240" alt="Capture d’écran 2022-01-24 à 15 40 38" src="https://user-images.githubusercontent.com/76073612/150803966-bf73d02c-f465-47e8-ab08-d86fa688c051.png">

V1.2 allows you to choose a preset via Quick Action. Currently, you have to make sure the app is already launched and connected to your unlocked bike to select them. These are not stored once you apply them.

- Default Speed : Speed limit enabled / FW 0%
- Speed Mode 1 : Speed limit disabled / FW 15%
- Speed Mode 2 : Speed limit disabled / FW 18%
- Speed Mode 3 : Speed limit disabled / FW 20%

