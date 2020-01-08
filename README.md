# Flutter Firebase Instagram Tutorial

Guys, this is Animated Social Instagram Android and IOS App tutorials are creating by Marcus NG and me details it for more learning by using the #Login_Signup_withFirebase database for learning and seeking education, therefore, I've not uploaded the code so that you can practice as video follow. thanx for watching any further questions you can ask in comments.

Be sure to ask for help in the comments if you need any help. Suggestions for future #Flutter tutorials are also very welcome! :D

Flutter is an SDK owned by Google to create applications for #AndroidandIOS using a single codebase. Flutter uses the Dart programming language (also owned by Google). Flutter was in alpha when I released this video, so things might still change a bit. But the SDK is already mature enough to write some cool apps!

1-  Login and Signup ui design ->(2)
3-  Firebase Connectivity Android + IOS
4-  Login and Signup with Firebase ->(5)
6-  Bottom Navigation Bar Styling ->(7)
8-  Styling Profile Activity ->(9)
10- Editing Profile Activity ->(11,12)
13- Change Profile Picture ->(14)
15- Save Profile Picture in Firebase ->(16)
17- Create Search Bar ->(18)
19- Create Profile Search Bar 
20- Create Post Activity ->(21,22)
23- Create Text Edit Post Activity ->(24)
25- Code For Follow & Unfollow Profile ->(26,27)
28- Setup Node.js for follow/unfollow ->(29)
30- Follower Post Activity wall ->(31)
32- Follower Profile Activity wall ->(33)
34- Post a Comment on Posts 
35- Liking Posts Widget create
36- News Feed Activity for Posts

#### 3. Setup the firebase app

1. You'll need to create a Firebase instance. Follow the instructions at https://console.firebase.google.com.
2. Once your Firebase instance is created, you'll need to enable anonymous authentication.

* Go to the Firebase Console for your new instance.
* Click "Authentication" in the left-hand menu
* Click the "sign-in method" tab
* Click "Google" and enable it


4. Enable the Firebase Database
* Go to the Firebase Console
* Click "Database" in the left-hand menu
* Click the Cloudstore "Create Database" button
* Select "Start in test mode" and "Enable"

5. (skip if not running on Android)

* Create an app within your Firebase instance for Android,
* Run the following command to get your SHA-1 key:

* In the Firebase console, in the settings of your Android app, add your SHA-1 key by clicking "Add Fingerprint".
* Follow instructions to download google-services.json
* place `google-services.json` into `/android/app/`.

6. (skip if not running on iOS)

* Create an app within your Firebase instance for iOS, with your app package name
* Follow instructions to download GoogleService-Info.plist
* Open XCode, right click the Runner folder, select the "Add Files to 'Runner'" menu, and select the GoogleService-Info.plist file to add it to /ios/Runner in XCode
* Open /ios/Runner/Info.plist in a text editor. Locate the CFBundleURLSchemes key. The second item in the array value of this key is specific to the Firebase instance. Replace it with the value for REVERSED_CLIENT_ID from GoogleService-Info.plist

Double check install instructions for both
   - Google Auth Plugin
     - https://pub.dartlang.org/packages/firebase_auth
   - Firestore Plugin
     -  https://pub.dartlang.org/packages/cloud_firestore
 
 ## Questions?🤔

## How to Contribute
1. Fork the the project
2. Create your feature branch (git checkout -b my-new-feature)
3. Make required changes and commit (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request
