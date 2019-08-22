
# LG-G6-FRP-BYPASS

_This wiki is for private usage and as a reminder if I will get another LG G6._

This device has been by far the most difficult phone to hack all categories, probably spent over 100 hours to bypass FRP.

*No* wiki's out there actually work the idiots or let us call them scammers (yeah, even dr phone and such programs wont work)  and some tutorials even may brick your device, not even xda forum have legit tutorial for this device so hopefully someone will enjoy this unique and probably only wiki for bypassing FRP protection on LG G6 870 for 100% real.

# HOWTO - ANDROID 7.0 

* If you got Android 8.0 Oreo then you must re-flash your firmware to Android 7.0, it wont  matter what firmware you choose from https://lg-firmwares.com/ until we really hacked the device, just pick one and download the file and flash your device with LGUP tool, go grab the tool + dll file from here: https://www.mylgphones.com/download-lg-up-software.

But before we re-flashing device and you trying to find a way to install the apks since settings is limited to network only let me show you how to install apk files on this firmware since LG techs forgot to set permissions on the email client for install applications outside play store. 

### INSTALL APKS ON ANDROID 8.0 LOCKED BY FRP

##### NOTICE: This is NOT allowed on Android 7.0 so don't bother to try, it will just bring you to the limited settings panel with netowrk settings only and you wont be able to move on to developer settings or overide apps settings: 

1) Start your device

2) On welcome screen press next button

3) Press on skip in lower right corner

4) Turn wifi on and login on your wifi

5) Go back to welcome screen

6) Press on Accessibility

7) Press on settings

8) Press on Switch Access

9) Press on settings in down right corner

10) Press on Help & Feedback

11) Press on About Switch Access for Android

12) Touch the youtube video once

13) Click on the clock icon beside the share icon

14) Youtube is starting quickly and taking you to google chrome browser

15) Now click on Accept & Continue

16) In down left corner click on No Thanks

17) Now browse to https://nr1.nu/i/archive/lg-g6/terminal.apk

18) Click on update permissions

19) Click on Allow

20) Wait until file has been downloaded
-)  Now to the problem, you won't be able to install this application
    since the settings and hiddenmenu are disabled and you will just
    get redirected to the limited settings, it wont help to use
    quickshortcutmaker or a similiar tools fortry launch development settings, why?`Duh! Cause it's not even installed!
    And just for saying, NO you wont be allowed to download an apk file and install dev settings and bypassing the limited network settings, there is no way to do this, for real! However, let's move on:

21) Go back to the youtube screen by pressing arrow back

22) Start a video, choose the share button

23) Choose E-mail application provided by LG the white icon with a blue E

24) Allow the permissions for access contacts + E-Mail address

25) Choose to sign in with your email (NOT A GMAIL ACCOUNT IT IS NOT VALID AND WONT WORK AND WILL REDIRECT YOU TO THE LOGIN SCREEN WERE YOU MUST LOGIN WITH THE OLD MAIL ACCOUNT)

26) Wait until you get's connected and just hit next followed by done

27) Now you are on "Send Message" in your e-mail application

28) Choose the the add file button, upper right behind your e-mail address

30) Now press on the terminal.apk file that you added

31) You will now be allowed to install the application without enabling any permissions since they forgot to add permission denied on this one

32) After you installed the application, you can choose to open terminal in lower down corner

33) Now you will notice EVERYTHING is locked due to selinux enforcing and you wont even be allowed to list applications by pm list applications

34) What you wanna do now is to browse back to youtube screen in accessibility screen and press on the clock to start google chrome again and feel free to download and install ALMOST any apk file.

34) It wont help to install lgsetupwizard.apk, settings.ak or anything that you got in mind for bypassing the FRP protection and hiddenmenu.apk from will also be denied due permissions and you are not even allowed to use UUSD for open hidden menu, BUT this will work on Android 7.0 so you must downgrade to Android 7.0

# FOR BYPASS FRP

If you're on Android 8.0 and need reflash your device you can browse to lg's homepage and see how this can be done, since this is another process I wont go deeper in this topic but the main process is: 
 - 1) Start LGUP Tool
 - 2) Reboot your device to recovery mode by:
 - 3) Power off device and enter recovery mode by hold VOLUME UP while you plug in the usb cable while its still off
 - 4) Now choose your firmware file in LGUP tool and flash the firmware. Thats it.

Just for saying, when you downgrading from android 8.0 to android 7.0 your device will be wiped and if you installed any apks by above method you wont be able to use the applications on android 7.0 since its fully erased. If you are on Android 7.0 and upgrading to 8.0 instead your device wont be erased but this does not really matter since you wont be allowed to install applciations the same way as on android 8.0 cause this bug is only on android 8.0 AFAIK! Howerver, let us bypassing FRP now: 

1) Start your device after you installed Android 7.0

2) On welcome screen press next button

3) Press on skip in lower right corner

4) Turn wifi on and login on your wifi

5) Go back to welcome screen

6) Press on Accessibility

7) Press on settings

8) Press on Switch Access

9) Press on settings in down right corner

10) Press on Help & Feedback

11) Press on About Switch Access for Android

12) Touch the youtube video once

13) Click on the clock icon beside the share icon

14) Youtube is starting quickly and taking you to google chrome browser

15) Now click on Accept & Continue

16) In down left corner click on No Thanks

17) Now browse to https://nr1.nu/i/archive/lg-g6/terminal.apk

18) Click on update permissions

19) Click on Allow

20) Once google chrome has been started, go to a page that allowing you to press on a phone number, for example on Telia.se - You can press ![here](https://www.telia.se/privat/kontakt/butikerochaterforsaljare/borlange) for get redirected to telia.se and here you can press on a phone number, your phone application will be started.

21) Enter UUSD: *#546368#*870# where 870 is the device model, since we have a LG G6 870 we entering 870, you are now in HiddenMenu

### Don't get panic if  USB Debugging is inactive and youre not allowed to enable usb debugging! For users that not have this issue can jump over part:

   - Turn off your LG device
   - Re-do the flash process with LGUP
   - Once the installation is complete and your device is erasing itself with the white background and the android logo on screen saying "DO NOT TURN OFF YOUR DEVICE" - That's exactly what you must do so turn off device by hold POWER + VOLUME DOWN (if you will be to late first time, you will succeed second time just press the buttons ~2-3 seconds before you know the screen will popup so you will poweroff the device during installation) - Now let the device be powered off for ~1 minute and then turn it on again and redo the process from step 1 until 22 and you will be enable to enable usb debugging if you wasn't to late when powering off the device, IF it's still inactive then just try again and try again until it will work, actually I figure out this after my third attempt and now I have tried this several times and you must turn it off while it's between 0% and 100% and since POWER + VOL DOWN takes ~7 seconds to power off device and the screen appears for around 4 seconds you must press the buttons few seconds before to turn it off exactly when it's needed.

22) Once you got into Hidden Menu, press on:
     - Device Menu 
     - LDB
     - USB Debugging - Turn on debug mode when usb is connected


23) You are now allowed enter USB Debugging but this wont help much due to the permissions issues BUT now you are allowed to list application wich means you are allowed to uninstall them aswell (still not allowed to start any application or do anything almost since / is mounted as ro): Now do exactly as below and don't install other apps if you don't know exactly what you doing then you might be stuck and have a softbricked device, just follow this and you're safe!

![Screenshot](https://nr1.nu/archive/lg-g6/lg-remove-apps.gif)

     adb shell pm uninstall --user 0 com.android.google.gms
     adb shell pm uninstall --user 0 com.lge.setupwizard
     adb shell pm uninstall --user 0 com.lge.hiddenmenu
     adb shell pm uninstall --user 0 com.google.android.setupwizard
     adb shell pm uninstall --user 0 com.lge.easyhome
     adb shell am broadcast -a android.intent.action.MASTER_CLEAR
     adb reboot 
     
* Once device rebooted after you ran reboot, turn off the device while its installing with the white background and android logo on screen and let the device be turned off for ~1 minute and then powering off your device - When you are abck back to welcome screen (It's safe to turn off device during install, did it several times for trying)

1) Press on next button 
2) On wifi settings do NOT have a sim card or connect to a wifi
3) Just press skip down in right corner, and just move on until you enter HOME SCREEN and your done! Google can't connect to their servers due we removed the gms package and lgsetupwizard is gone so frp protection can't be triggered, reinstall applications from /system application and enjoy your fully unlocked LG G6 870S device!

Enjoy your fully unlocked LG G6 870 - If you're smart, download LG Bridge and put your device into download mode and upgrade your device to a proper firmware for you country.

### Other bugs I found while trying bypassing the FRP

When you are at wifi settings and the next button is inactive because you are forced to connect to a network then do as following to move further, exactly the same second as you turning off the device then press on next button before the button getting inactive/grayed out and you will be asked if you wanna continue to the next step, you will now be allowed to take over the fingerpring and pin code and erase the old owners lock setting, but don't be to excited once this step is done and when you was allowed to enter the username you will be redirected back to the wifi screen and you wont be able to go further. In some tutorials out there some claims you can take over lockscreen settings by entering the phone application and go to settings and setup new certificates and then be allowed to install your own fingerprint, this is waste of time and it's much easier to use this bug to take over the pin code (it wont help in any way to bypass FRP even if some wikis out there claims that)



#### REQUIREMENTS

A running Windows 10 Pro, works for any version you will find your keys from Microsoft here: https://docs.microsoft.com/sv-se/windows-server/get-started/kmsclientkeys

#### CONTACT 

If you have problems, questions, ideas or suggestions please contact
us by posting to wuseman@nr1.nu

#### WEB SITE

Visit our homepage for the latest info and updated tools

https://github.com/wuseman

#### END!

