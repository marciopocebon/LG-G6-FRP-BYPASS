
# LG-G6-FRP-BYPASS

This wiki is for private usage and as a reminder if I will get another LG G6.

This device has been by far the most difficult phone to hack all categories, probably spent over 100 hours to finally break it.
No wiki's out there actually work and they all who made them are kinda idiots and just scammers and some tutorials even may brick your device, not even xda forum have legit tutorial for this device so hopefully someone will enjoy this wiki that have a LG G6 and probably the newer versions aswell.

# HOWTO - ANDROID 7.0 

* If you got Android 8.0 Oreo then you must re-flash your firmware to Android 7.0, it wont  matter what firmware you choose from https://lg-firmwares.com/ until we really hacked the device, just pick one and download the file and flash your device with LGUP tool, go grab the tool + dll file from here: https://www.mylgphones.com/download-lg-up-software 

.. Flashing is another process, its pretty simple so I wont go deep into this cause there is legit guides for this at least out there: 
 - 1) Start LGUP Tool
 - 2) Reboot your device to recovery mode
 - 3) Power off device and enter recovery mode by hold VOLUME UP while you plug in the usb cable while its still off
 - 4) Now choose your firmware file in LGUP tool and flash the firmware, simple. Thats it.

### HOW TO BYPASS FIRMWARE: 

After you downgraded your firwmare to Android 7.0 then do as following: 

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

13) Click on the clock icon beside the share icong

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
    quickshortcutmaker or a similiar tool for bypass this, this is the mess, however
    let's hack the device on my unique way.

21) Go back to the youtube screen by pressing arrow back

22) Start a video, choose the share button

23) Choose E-mail application

24) Allow the permissions for access contacts + E-Mail address

25) Choose to sign in with your email (NOT A GMAIL ACCOUNT IT IS NOT VALID AND WONT WORK AND WILL REDIRECT YOU TO THE LOGIN SCREEN WERE YOU MUST LOGIN WITH THE OLD MAIL ACCOUNT)

26) Wait until you get's connected and just hit next followed by done

27) Now you are on "Send Message" in your e-mail application

28) Choose the the add file button, upper right behind your e-mail address

29) And voila! You are now allowed to choose a file, browse to the terminal.apk we downloaded earlier and add it

30) Now press on the terminal.apk file that you added

31) You will now be allowed to install the application without enabling any permissions since they forgot to add permission denied on this one

32) After you installed the application, you can choose to open terminal in lower down corner

33) Now you will notice EVERYTHING is locked due to selinux enforcing and you wont even be allowed to list applications by pm list applications

34) What you wanna do now is to browse back to youtube screen in accessibility screen and press on the clock to start google chrome again

35) Once google chrome has been started, go to a page that allowing you to press on a phone number, for example on Telia.se - You can press ![here](https://www.telia.se/privat/kontakt/butikerochaterforsaljare/borlange) for get redirected to telia.se and here you can press on a phone number, your phone application will be started (it's not possible to start any applications, use any logcat, dumplog or anything similiar, everything is limited due to selinux) however, now do as following when your phone app has been started:

36) Enter UUSD: *#546368#*870# where 870 is the device model, since we have a LG G6 870 we entering 870, you are now in HiddenMenu

37) The HiddeMenu is disabled by default, for get this to work you has to crash the device (See Here) (HiddenMenu is _NOT_ allowed to join in Android 8.0 Application - It toke long time before I actually figured this out that it's allowed in 7.0 only and downgraded the firmware since I was on 8.0 as default and I think I have tried EVERY method that is possible to bypass FRP on 8.0 withotu succeed still due to limited settings and you cant even overide the settings apk by installing default application due permission denied by selinux)

38) Howeveer when you have crashed the application you will be allowed to enable the usb debugging by following steps:
- Device Menu 
- LDB
- USB Debugging - Turn on debug mode when usb is connected


39) You are now allowed enter USB Debugging but this wont help much due to the permissions issues, now to the secret: 
-) Reflash your device with LGUP Tool
-) Wait until it's done, when device is booting and saying DO NOT TURN OFF THE DEVICE then you must turn off the device, wait for ~2minutes
-) Boot device and your device has been reset until default again and we're back to 0
-) Now while you pressing on next button on welcome screen and joined the page where you must turn on mobile traffic or wifi traffic do like this since you are required to have a internet connection for oving on:


-) First connect to a wifi
-) When you're connected do like this: 
-) https://www.facebook.com/Haha 
 # A window will popup and tell you that encryption was unsuccessfull just press reset phone and wait until it has reboot
