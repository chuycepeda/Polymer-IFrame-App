##Getting started

1. Clone this repo
2. Go to /app/scripts/app.js and edit the <code>app_domain</code> to the desired iframe.
3. Run <code>$ gulp</code>
4. Go to /dist/ folder and copy all its files and folders.
5. Go to /iframeapp/www/ folder, delete its contents and paste all your copied files.
6. Run <code>$ cd iframeapp </code>
7. Run <code>$ cordova build android</code>
8. Run <code>$ cordova build ios</code>
9. It's done.

	- You can find your Android Studio project at /iframeapp/platforms/android/, where you can change default icon for example. Also .apk is at /polymerapp/platforms/android/build/outputs/apk/.
	- You can find your XCode project at /iframeapp/platforms/ios/.
	
	
---	
For further details on dependencies and how this works please refer to https://github.com/chuycepeda/Polymer-Starter-Apps.
