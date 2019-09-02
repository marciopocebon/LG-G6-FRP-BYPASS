# LG-G6-FRP-BYPASS


_This wiki is for private usage and as a reminder if I will get another LG G6._

This device has been by far the most difficult phone to hack all categories, probably spent over 100 hours to finally break it.
No wiki's out there actually work and they all who made them are kinda idiots and just scammers and some tutorials even may brick your device, not even xda forum have legit tutorial for this device so hopefully someone will enjoy this wiki that have a LG G6 and probably the newer versions aswell.

Also posted this on ![XDA-Developers](https://forum.xda-developers.com/lg-g6/how-to/lg-g6-h870-frp-bypassing-limited-t3963642/post80168797#post80168797)

# HOWTO - ANDROID 7.0 

If you got Android 8.0 Oreo then you must re-flash your firmware to Android 7.0, it wont  matter what firmware you choose from https://lg-firmwares.com/ until we really hacked the device, just pick one and download the file and flash your device with LGUP tool, go grab the tool + dll file from here: https://www.mylgphones.com/download-lg-up-software but for fun, let me provide you how you will be able to install apk files on the limited android 8.0 firmware that has all settings disabled and due permissions you are not allowed to launch them because selinux is enable, but you can install applications by a miss I haven't been able to find anywhere. This is possible cause LG have forgot to disable permissions for install 'un-secured' applications outside playstore:

# INSTALL APKS ON ANDROID 8.0 LOCKED BY FRP

NOTICE: This is NOT allowed on Android 7.0 so don't bother to try, it will just bring you to the limited settings panel with netowrk settings only and you wont be able to move on to developer settings or overide apps settings:

 Start your device

On welcome screen press next button

Press on skip in lower right corner

Turn wifi on and login on your wifi

Go back to welcome screen

Press on Accessibility

Press on settings

Press on Switch Access

Press on settings in down right corner

Press on Help & Feedback

Press on About Switch Access for Android

Touch the youtube video once

Click on the clock icon beside the share icon

Youtube is starting quickly and taking you to google chrome browser

Now click on Accept & Continue

In down left corner click on No Thanks

Now browse to ![Screenshot](https://nr1.nu/i/archive/lg-g6/terminal.apk

Click on update permissions

Click on Allow

Wait until file has been downloaded -) Now to the problem, you won't be able to install this application since the settings and hiddenmenu are disabled and you will just get redirected to the limited settings, it wont help to use quickshortcutmaker or similiar tools for launch development settings, why? Duh! Cause it's not even installed! And cause selinux you wont be able to overide the current settings neither so you are stuck, just give up!

Go back to the youtube screen by pressing arrow back

Start a video, choose the share button

Choose E-mail application provided by LG the white icon with a blue E

 Allow the permissions for access contacts + E-Mail address

Choose to sign in with your email (NOT A GMAIL ACCOUNT IT IS NOT VALID AND WONT WORK AND WILL REDIRECT YOU TO THE LOGIN SCREEN WERE YOU MUST LOGIN WITH THE OLD MAIL ACCOUNT)

Wait until you get's connected and just hit next followed by done

Now you are on "Send Message" in your e-mail application

Choose the the add file button, upper right behind your e-mail address

Now press on the terminal.apk file that you added

You will now be allowed to install the application without enabling any permissions since they forgot to add permission denied on this one

After you installed the application, you can choose to open terminal in lower down corner

Now you will notice EVERYTHING is locked due to selinux enforcing and you wont even be allowed to list applications by pm list applications


# Bypassing FRP!

Sorry for the extremely big pictures, no idea how to fix and I am to lazy to search.

### Press arrow next button:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-28-51.png)

### Press on skip:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-28-55.png)

### As you can see, next button is grayyed out so connect to wifi (you can bypass this if you pressing quick on wifi and pressing next)
![Screenshot]![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-29-01.png)

### Now hit next
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-29-23.png)

### Press Setup as new:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-29-29.png)

### Probably this is what you gonna see, so let's bypass this:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-29-57.png)

### Go back to main screen (wifi must be connected):
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-03.png)

### Press on settings:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-07.png)

### Press on switch access: (This is why wifi connection must be added, otherwise there is no settings here)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-12.png)

### Press on settings:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-15.png)

### Press on Help & Feedback
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-20.png)

### Press on about switch access for Android
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-28.png)

### Press fast on top at the video, now you see the clock and press on it (no need some annoying accesibilitys on with a annoying voice)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-39.png)

### Youtube getting started for 1 second you wont even notice:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-43.png)

### Now you're at google chrome
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-49.png)

### Press on No Thanks:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-30-53.png)

### Download any apk file if you wanna see that settings are limited by your own:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-31-14.png)

### Just hit Allow
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-31-18.png)

### Press on Open:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-31-23.png)

### Once done, you will see:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-31-43.png)

Press on Settings (and fuck you scammers, this is what you will get to)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-31-47.png)

### No worries, browse to any site that allowing you to press a number (here is a link to the page I was using)
Feel free here to press on mail and try install your apk as we did on android 8.0 its not possible you will be redirected to the settings above:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-32-18.png)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-32-22.png)

### However, once pressed on the phone number you get into call application, now enter the uusd code for secret menu (this code is ńot accepted on android 8.0, hence why we using android 7.0)
*#546368#*870#

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-32-54.png)

#### And now you're in hidden menu wich you wasnt allowed to open in android 8.0, browse to SVC MENU:

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-32-58.png)

### Followed by pressing on LDB:

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-33-02.png)

# Is the USB debugging button grayed out? 

### This seems to be various for different firmwares have I noticed:

### Don't get panic! Then follow the below part, others can move on to next part:

Turn off your LG device
 Re-do the flash process with LGUP
 Once the installation is complete and your device is erasing itself with the white background and the android logo on screen saying "DO NOT TURN OFF YOUR DEVICE" - That's exactly what you must do so turn off device by hold POWER + VOLUME DOWN (if you will be to late first time, you will succeed second time just press the buttons ~2-3 seconds before you know the screen will popup so you will poweroff the device during installation) - Now let the device be powered off for ~1 minute and then turn it on again and redo the process from step 1 until 22 and you will be enable to enable usb debugging if you wasn't to late when powering off the device, IF it's still inactive then just try again and try again until it will work, actually I figure out this after my third attempt and now I have tried this several times and you must turn it off while it's between 0% and 100% and since POWER + VOL DOWN takes ~7 seconds to power off device and the screen appears for around 4 seconds you must press the buttons few seconds before to turn it off exactly when it's needed.

### Enable usb debugging:
 
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-33-05.png)

### Here is a video what's required to uninstall, uninstall other applications on your own risk - I TAKE NO RESPONSIBILITYS AND I DONT RECOMMENDING THIS SINCE ITS NOT NEEDED AND IT IS JUST A RISK , PLAY WITH THIS WHEN YOU DONE)

![Screenshot](https://nr1.nu/archive/lg/screenshots/lg-g6-bypassing.gif

However, here is the oneliner you can copy and paste if you not wanna watch the video:

    for apps in "com.android.google.gms com.lge.setupwizard com.lge.hiddenmenu com.google.android.setupwizard com.lge.easyhome"; do pm uninstall --user 0 "${apps}"; done; am broadcast -a android.intent.action.MASTER_CLEAR;adb reboot 

### Once you done the step in the video and rebooted your device, then wer'e back to main screen:

### Click next arrow button

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-39-02.png)

### And skip again.

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-39-06.png)

### Connect to wifi and hit next
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-39-25.png)

### Voila! You can accept documents now:

![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-39-49.png)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-02-39-56.png)

And just continue until you will join the HOME screen, voila! :D 

Nah, just kidding. You will get your device formated, don't panic!!!!

### The device will reboot, erase itself and now the magic! Your'e done.

### Setup your device as usual:
Third time hit arrow next button
![Screenshot](https://nr1.nu/archive/lg/after_device_was_reset/Screenshots/Screenshot_2019-09-01-23-58-04.png)

### Hit next:
![Screenshot](https://nr1.nu/archive/lg/after_device_was_reset/Screenshots/Screenshot_2019-09-01-23-58-13.png)

### Now you can continue without wifi connected, just move on to the next step without any wifi or sim-card:
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-01-23-58-19.png)

### Click skip internet connection

### Now you´re at google services, I allways unchecking this shit but this is optional ofc.
![Screenshot](https://nr1.nu/archive/lg/after_device_was_reset/Screenshots/Screenshot_2019-09-01-23-58-30.png)

### Next, setup your fingerprint if you wish I wont use this now during the wiki:
![Screenshot](https://nr1.nu/archive/lg/after_device_was_reset/Screenshots/Screenshot_2019-09-02-00-59-03.png)

### Okey, you're back at were you was started before, don't worry - It will work! ;)
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-59-08.png)

### You will see smart forward
![Screenshot](https://nr1.nu/archive/lg/screenshots/Screenshot_2019-09-02-00-59-15.png)

### Of course, enjoy your fully unlocked LG device with bypassed FRP, feel free to do anything you want now, it's 100% yours.
![Screenshot](https://nr1.nu/archive/lg/after_device_was_reset/Screenshots/Screenshot_2019-09-02-00-59-21.png)

Device will erase itself, but don't worry! We have now reset the permissions for everything so just setup device again and this time it wont reboot again.


# END
