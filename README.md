#Heads-up notifications#
With this app, any device can get the heads-up notifications introduced in the new Android 5.0 “L Developer Preview”, no root required. And the popups actually look like those in Android L.
But according to Addictivetips (and a lot of the users), this app “has done more than just replicate a feature of Android L. Even if you aren’t dying to try Android L and some of its new features, this app is worth a try“.

## Features ##
- Displays notifications as a floating popup
- Easily control which notifications to display
- Quick actions: mark messages as read in one tap (Android 4.1+, doesn't work with all devices and apps)
- Display the heads-up on lock screen as well
- Battery friendly! (Email me if you notice significant battery consumption after installing)
- Choose how long you want the notifications to display
- Pocket detection / active display (causes a tiny increase in battery usage if you get a ton of notifications)
- Display notifications on the lock screen until dismissed
- Privacy on the lock screen
- Multiple themes
- Choose popup positioning and opacity
- Don't display heads-up while using certain apps
- Display a popup for the currently playing song
- Compact/expandable mode
- Full notification

## So... why is this app on GitHub? ##
As of now, the app has over 100,000 downloads on the Play store, and a 4.5 average rating. And that's really awesome! Honestly, I never thought this thing would make it past 50 downloads, so I'm still recovering after seeing the statistics page on the Play store.

Unfortunately, I don't have time to work on Heads-up, so I decided to open-source it. I'll keep updating the app every now and then, but I just can't keep up with all those great suggestions for new features. And that's where you come in: if you're a developer, designer, translator, or just "some guy", feel free to download the code, make as many changes as you wish, and be sure to send a pull request when you're finished, so everyone else gets to enjoy your improvements. 

### Popular feature requests ###
- Answer SMS directly from the popup
- Multiple notifications
- Incoming call handling 
- Reminder after X minutes
- User-submitted themes
- More customization options

I ran a poll on my [website](http://simen.codes/stuff/future-of-heads-up/) a while ago, where over 1,000 users voted.

- Roughly 50% of the users wanted support for multiple notifications. Among those, half wanted them horizontally, while the other half wanted them vertically (this option should probably be implemented in a separate app as it kills the whole point of non-intrusive notifications).
- Then, 25% voted for quick reply to messages. While I specified reply to SMS, many asked for the same feature for other apps as well. AFAIK, most other apps doesn't allow this. If you know how to do this, please share!
- About 10% wanted more advanced theming and customisation. Choosing colors, crating themes, sharing them with friends through the app, etc. Also, some people ask for a separate position on the lock screen.
- The remaining users opted for something else, or keeping the app as it is.


##Common issues##
####If no popups appear:####
Please make sure that Heads-up shows up in the list of running services. If it doesn't, make sure you have enabled the service, and then reboot the phone.
If your device is running Android 4.2 or earlier, and you have other accessibility services running (such as Pushbullet), they might block Heads-up from receiving your notifications. Please try to disable them if Heads-up doesn't work.

####Huawei, XIAOMI and MIUI users:####
Please allow Heads-up to display popups under Settings > Apps > Downloaded > Heads-up. It might also be necessary to reset the app data/settings.

####Uninstalling:####
If you find that the uninstall button is disabled, go to Settings > Security > Device administrators > Heads-up, and tap Disable.

##Contact##
Problems, feature requests or questions? Feel free to contact me at [sb@simen.codes](mailto:sb@simen.codes), or open an issue on [GitHub](https://github.com/SimenCodes/heads-up/issues/).