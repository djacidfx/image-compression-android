# image-compression-android
 Android app for image compression and convert
Documentation About App
Thank you for purchasing our app. If you have any questions that are beyond the scope of this help
file, please feel free to email via my user page contact form here : Elvee Infotech .
Change Package Name Video Link
https://www.youtube.com/watch?v=uVPTmjuLGb0
1) Reskin and Installation Instruction Video
https://drive.google.com/open?id=12xzt7sWCz-jnEGNGr4bhcoJWkqOcAgWB
App Setup :
1) Download and Install Android Studio
Link - https://developer.android.com/studio/

2) Import Project
Process - Main.zip you download, you will see some file and folder. You can found project in “Code”
Folder.
When your Android Studio ready you can open it
i) select “Open an existing Android Studio Project“.
ii) Browse location Project and press “OK” button.
iii) Wait for few minutes until all process import has finished.
3) Change Package Name
You can change the package name by following these steps. Click link to view steps
Video URL
https://www.youtube.com/watch?v=uVPTmjuLGb0
or
https://stackoverflow.com/a/29092698
Note :- You Package Name Should be unique and different.


4) Admob Ad Setup
- Login to your AdMob account, create an app and generate your ad unit id
- Open project in Android Studio
- The go to find “AdAdmob.java” in main package
- Now Open that “AdAdmob.java”
- In this file you can find below code
- Where you show red colour code ID which you have to replace with your real Id
before publishing on Google Play Store
-
-
String BannerAdID = "/6499/example/banner", FullscreenAdID = "/6499/example/interstitial";
-
5) Change App Name and other string resources for language :
i) res/value/string.xml Locate this
ii) You can change App Name and other string resources from this file
<string name="app_name">All in one status saver</string>
6) Change App Logo : Please refer screenshot-1.1
i) Go to the res folder in app Launcher icon from mipmap or drawable folder.
● Change App Color
i)For Changes of app color, you can see on the res/values/colors.xml
7) Generate Signed APK
To sign your app in release mode in Android Studio, follow these steps :
i) On the menu bar, click Build → Generate Signed Bundle / APK → APK
ii) If you already have a keystore, go to step v.
iii) On the Generate Signed APK Wizard window, click Create new to create a new keystore.
iv) On the New Key Store window, provide the required information, your key should be valid for at
least 25 years, so you can sign app updates with the same key through the lifespan of your app.
v) On the Generate Signed APK Wizard window, select a keystore, a private key, and enter the
passwords for both. Then click Next
vi) On the next window, select a destination for the signed APK and Signature Versions.
vii) Select Signature Version : V1 (Jar Signature)
viii) click Finish and the signed apk will generated
If you like our app, we will highly appreciate if you can provide us a rating of 5.
Once again, thank you so much for purchasing this app. As I said at the beginning, I'd be glad to
help you if you have any questions relating to this app. No guarantees, but I'll do my best to assist.
please feel free to email via our user page contact form or email support on :
elveeinfotech@gmail.com


Change Ad Units:-
- Open project in Android Studio
- The go to find “AdAdmob.java” in main package
- Now Open that “AdAdmob.java”
- In this file you can find below code
- Where you show red colour code ID which you have to replace with your real Id
before publishing on Google Play Store
-
-
String BannerAdID = "/6499/example/banner", FullscreenAdID = "/6499/example/interstitial";
-
