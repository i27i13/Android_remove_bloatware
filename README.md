READ EVERYTHING BEFORE DOING ANYTHING!

No root needed!

Samsung Phone:
Settings - About Phone - Software Information
Keep tapping on:
Build number
Until you get a message telling you that you have unlocked:
Developer mode


Settings - Developer options
Enable:
USB debugging


Sony Phone:
Settings - About phone - "scroll down"
Keep tapping on:
Build number
Until you get a message telling you that you have unlocked:
Developer mode

Settings - Developer options
Enable:
USB debugging


--------------
Creade a folder in for example;
C:\Users\YOUR USERNAME\Portable\-_Android\remove_bloatware

Download the following then extract to that folder!
Download SDK Platform-Tools for Windows
https://developer.android.com/studio/releases/platform-tools

In C:\Users\YOUR USERNAME\Portable\-_Android\remove_bloatware

you should have a lot of files and folders

-------------

Install the app:
App Manager
by: Webserveis

1. In the app "App Manager" select/tap for example:
Bixby service
2. Tap:
Delete
3. You get a message:

Samsung: App Manager Pro version

<img src="https://github.com/i27i13/Android_remove_bloatware/blob/master/Samsung.jpg" data-canonical-src="https://github.com/i27i13/Android_remove_bloatware/blob/master/Samsung.jpg" width="720" height="636" />



IT IS BEST THAT ONE DOES NOT DELETE APPS! JUST DISABLE THEM!


Sony:     Lite version

<img src="https://github.com/i27i13/Android_remove_bloatware/blob/master/Sony.png" data-canonical-src="https://github.com/i27i13/Android_remove_bloatware/blob/master/Sony.png" width="720" height="1272" />


IT IS BEST THAT ONE DOES NOT DELETE APPS! JUST DISABLE THEM!


-------------

WARNING!
I disabled samsung pay and had MY DEVICE LOCKED UP!
Could not access ANYTHING IN IT!!!!

Had to reset and delete EVERYTHING!
Careful with what you disable!

-------------

This is how I do it;

1. Find a package that I want to disable.
2. Copy the package name

Bixby service:
has a package name:
com.samsung.android.bixby.agent

rename it to:
pm disable-user --user 0 com.samsung.android.bixby.agent

Now find all the packages you want to disable and do the same!

-------------

Found all the packages?

Unlock phone

Connect your phone via USB to the PC


A message appears:
Allow USB debugging?

choose:
ok/Always allow from this computer



Sony:
Open notification pannel

Tap the notification:

Android System
USB charging this device
Tap for more options

Tap that notification and choose:
Transfer files


Samsung:
Open notification pannel

Tap the notification:

Android System
USB charging this device
Tap for other USB options.

Tap that notification and choose:

USB Controlled by:
This Phone

Use USB for:
Transfer files / Android Auto

-------------



start cmd.exe as Admin:

Press the Windows button then type: cmd "Yes, just start typing!"

Right click on "Command Prompt" and Run as Administrator

type:

cd C:\Users\YOUR USERNAME\Portable\-_Android\remove_bloatware

then type:

adb shell

to disable Bixby service:

Copy:
pm disable-user --user 0 com.samsung.android.bixby.agent

and paste it in the "cmd" window then press enter!

Now if you navigate to the service in the settings - Apps - Bixby Service; you will find it to be disabled!

If you want to enable the service:

pm enable --user 0 com.samsung.android.bixby.agent

------------------------------------------------------
------------------------------------------------------
-------------

WARNING!
I disabled samsung pay and had MY DEVICE LOCKED UP!
Could not access ANYTHING IN IT!!!!

Had to reset and delete EVERYTHING!
Careful with what you disable!

-------------
-------------

WARNING!
I disabled samsung pay and had MY DEVICE LOCKED UP!
Could not access ANYTHING IN IT!!!!

Had to reset and delete EVERYTHING!
Careful with what you disable!

-------------
-------------

WARNING!
I disabled samsung pay and had MY DEVICE LOCKED UP!
Could not access ANYTHING IN IT!!!!

Had to reset and delete EVERYTHING!
Careful with what you disable!

-------------


I have a note 9 and this is what I had disabled:

pm disable-user --user 0 com.google.android.projection.gearhead
pm disable-user --user 0 com.samsung.android.samsungpassautofill
pm disable-user --user 0 com.samsung.android.app.watchmanagerstub
pm disable-user --user 0 com.samsung.android.smartmirroring
pm disable-user --user 0 com.android.bookmarkprovider
pm disable-user --user 0 com.google.android.apps.turbo
pm disable-user --user 0 com.google.android.gms.location.history
pm disable-user --user 0 com.samsung.android.app.spage
pm disable-user --user 0 com.sec.android.desktopmode.uiservice
pm disable-user --user 0 com.samsung.ims.smk
pm disable-user --user 0 com.sec.android.widgetapp.webmanual
pm disable-user --user 0 com.samsung.android.bixby.service
pm disable-user --user 0 com.samsung.android.bixby.agent
pm disable-user --user 0 com.samsung.android.bixby.agent.dummy
pm disable-user --user 0 com.samsung.android.bixby.wakeup
pm disable-user --user 0 com.samsung.android.visionintelligence
pm disable-user --user 0 com.samsung.android.calendar
pm disable-user --user 0 com.android.calllogbackup
pm disable-user --user 0 com.samsung.android.drivelink.stub
pm disable-user --user 0 com.samsung.android.app.contacts
pm disable-user --user 0 com.samsung.android.rubin.app
pm disable-user --user 0 com.sec.android.app.dexonpc
pm disable-user --user 0 com.sec.android.app.desktoplauncher
pm disable-user --user 0 com.samsung.android.lool
pm disable-user --user 0 com.diotek.sec.lookup.dictionary
pm disable-user --user 0 com.samsung.android.forest
pm disable-user --user 0 com.facebook.system
pm disable-user --user 0 com.facebook.appmanager
pm disable-user --user 0 com.facebook.services
pm disable-user --user 0 com.facebook.katana
pm disable-user --user 0 com.samsung.android.fmm
pm disable-user --user 0 com.sec.android.widgetapp.samsungapps
pm disable-user --user 0 com.samsung.android.themestore
pm disable-user --user 0 com.samsung.android.themecenter
pm disable-user --user 0 com.sec.android.gallery3d
pm disable-user --user 0 com.samsung.storyservice
pm disable-user --user 0 com.samsung.android.game.gametools
pm disable-user --user 0 com.samsung.android.game.gos
pm disable-user --user 0 com.google.android.googlequicksearchbox
pm disable-user --user 0 com.google.android.syncadapters.calendar
pm disable-user --user 0 com.google.android.syncadapters.contacts
pm disable-user --user 0 com.google.android.tts
pm disable-user --user 0 com.samsung.android.ipsgeofence
pm disable-user --user 0 com.samsung.android.keyguardwallpaperupdator
pm disable-user --user 0 com.samsung.android.kidsinstaller
pm disable-user --user 0 com.samsung.android.knox.analytics.uploader
pm disable-user --user 0 com.samsung.android.app.simplesharing
pm disable-user --user 0 com.samsung.android.mdx
pm disable-user --user 0 com.samsung.android.visionarapps
pm disable-user --user 0 com.google.android.apps.maps
pm disable-user --user 0 com.google.android.feedback
pm disable-user --user 0 com.samsung.android.allshare.service.mediashare
pm disable-user --user 0 com.samsung.android.easysetup
pm disable-user --user 0 com.android.hotwordenrollment.okgoogle
pm disable-user --user 0 com.samsung.android.app.reminder
pm disable-user --user 0 com.sec.android.app.apex 
pm disable-user --user 0 com.sec.android.app.billing
pm disable-user --user 0 com.samsung.android.scloud
pm disable-user --user 0 com.samsung.android.mobileservice
pm disable-user --user 0 com.samsung.android.mateagent
pm disable-user --user 0 com.samsung.android.app.mirrorlink
pm disable-user --user 0 com.samsung.android.app.notes
pm disable-user --user 0 com.samsung.android.authfw
pm disable-user --user 0 com.samsung.android.samsungpass
pm disable-user --user 0 com.sec.spp.push
pm disable-user --user 0 com.samsung.SMT
pm disable-user --user 0 com.samsung.android.fast
pm disable-user --user 0 com.sec.android.easyMover
pm disable-user --user 0 com.sec.android.easyMover.Agent
pm disable-user --user 0 com.samsung.android.beaconmanager
pm disable-user --user 0 com.samsung.android.app.advsounddetector
pm disable-user --user 0 com.samsung.android.app.tips
pm disable-user --user 0 com.samsung.android.service.airviewdictionary
pm disable-user --user 0 com.samsung.android.app.talkback
pm disable-user --user 0 com.samsung.android.dynamiclock
pm disable-user --user 0 com.sec.android.daemonapp
pm disable-user --user 0 com.samsung.android.app.social
pm disable-user --user 0 com.samsung.android.net.wifi.wifiguider
pm disable-user --user 0 com.android.hotwordenrollment.xgoogle
pm disable-user --user 0 com.microsoft.appmanager
pm disable-user --user 0 de.axelspringer.yana.zeropage
pm disable-user --user 0 com.google.android.apps.tachyon
pm disable-user --user 0 com.google.android.apps.photos
pm disable-user --user 0 com.google.android.youtube
pm disable-user --user 0 com.google.android.gm
pm disable-user --user 0 com.google.android.videos
pm disable-user --user 0 com.google.android.music
pm disable-user --user 0 com.google.ar.core
pm disable-user --user 0 com.samsung.android.aremoji
pm disable-user --user 0 com.samsung.android.game.gamehome
pm disable-user --user 0 com.samsung.android.app.ledcoverdream
pm disable-user --user 0 com.linkedin.android
pm disable-user --user 0 com.microsoft.office.excel
pm disable-user --user 0 com.microsoft.skydrive
pm disable-user --user 0 com.microsoft.office.powerpoint
pm disable-user --user 0 com.microsoft.office.word
pm disable-user --user 0 com.samsung.android.ardrawing
pm disable-user --user 0 com.samsung.android.arzone











