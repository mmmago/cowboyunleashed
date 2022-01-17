# Legal Notice
**1. I am not resposible to anything worse that could happen to your bike because of this app**

**2. Be careful that lifting the 25km/h limit could make your bike not eligible to ride on streets and public space and therefore make it illegal, please use in private areas**

**3. This app could void your warranty**



# cowboyunleashed
An iOS app to lift the speed limit of your Cowboy Bike. 


<img width="394" alt="Capture d’écran 2022-01-17 à 21 06 42" src="https://user-images.githubusercontent.com/76073612/149831377-677a01df-8d1a-452c-806d-9cf25513941a.png">


This iOS app allows you to debrid your Cowboy (C1 -> C4) bike and make it a bit more fun and easy to ride. I've only tested it on my C3 right now and it is working as intended.

Working on my SE 2020 iOS 14.3, but should be working on all devices >iOS 13.

# Shout out

Please give a lot of credit to [Imaginous](https://github.com/Imaginous) for **[Cowboy Untamed](https://github.com/Imaginous/Cowboy_Untamed)**, without him there wouldn't even be any way to tweak our bikes. You will also find a lot of useful infos about the settings you'll find in the app on his page.

# Donate

This took a few late night works and a bit of headache as someone new to iOS programming. If you're down to receive updates and improvements, please send feedbacks and don't hesitate [**to donate**](https://www.paypal.com/donate/?hosted_button_id=TUH8ECY3KP4BW).

# Download / Installation
[**Download the IPA here**](https://github.com/mmmago/cowboyunleashed/releases)

As this app is not on the appstore, you need to **sideload it** your favourite way. [Altstore](https://altstore.io/) can help you with that, but there are other way. **Be careful that the app will need to be re-installed / re-signed every 7 days in order to work as this is how apple restricts sideloading.** If you don't know anything about sideloading, [here is a guide](https://www.reddit.com/r/sideloaded/comments/orqzau/guide_a_complete_beginners_guide_to_sideloading/).

If you're jailbroken, you can simply download it on your files and install it through [ReProvision](https://repo.packix.com/package/jp.soh.reprovision) and the auto-resign will do his job. I might create a repo later to install it directly through Sileo / Cydia.

# Preview

![Capture d’écran 2022-01-17 à 20 32 10](https://user-images.githubusercontent.com/76073612/149828122-4ccde1ff-5591-415c-aecc-c83679ed73a7.png)
<img width="390" alt="Capture d’écran 2022-01-17 à 20 34 13" src="https://user-images.githubusercontent.com/76073612/149828134-3fbf8652-812a-467b-b3b3-44cc7801623a.png">


(Buttons UI are only showing on iOS 15+)


# Main features

- Disable the 25km/h speed limit 
- Edit field weakening parameter (increase assistance help in higher speeds)
- Enable *Auto Unlock* on the C1+
- Edit Hall Interpolation Transitions (HIT) (resolve motor judder at startup)
- Reset PCB (printed circuit board). Not resetting any settings made before with the app. Might resolve some light bug on the C1+.

The app is automatically scanning bluetooth devices around and will unlock your bike if it founds it. Set the settings you need, try them on, then if you want to keep them, press "store flash", then "close flash", which will also lock your bike.

The settings are not stored until you don't press "store" and "close", so if you just want to try some settings, apply them without storing. Locking the bike will dismiss them.
