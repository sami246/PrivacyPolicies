## Foodi Privacy policy

This is a solo made Android app developed by Sami Rahman, with the app intended to be available on Google Play Stores.

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme, etc.) and alarms) created by the you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

https://github.com/WrichikBasu/ShakeAlarmClock/blob/1031bad5edd2e73eda091cd1e84746f4710c7528/app/src/main/AndroidManifest.xml#L7-L15

<br/>


| Permission | Why it is required |
| :---: | --- |
| `android:name=android.permission.INTERNET` | Used to retrieve user data from Firebase. Permission automatically granted by the system, can't be revoked by user |
| `android:name=android.permission.READ_EXTERNAL_STORAGE` | Required to upload images from camera to application. User can choose to allow | 
| `android:name=android.permission.SYSTEM_ALERT_WINDOW` | Required for notifications. User can choose to allow | 
| `android:name=android.permission.VIBRATE` | Permission automatically granted by the system, can't be revoked by user  | 
| `android:name=android.permission.WRITE_EXTERNAL_STORAGE` | Required to upload images from camera to application. User can choose to allow | 
| `android:name=android.permission.ACCESS_FINE_LOCATION` | Required to show users current location on App. User can choose to allow | 
| `android:name=android.permission.ACCESS_BACKGROUND_LOCATION` | Required to show users current location on App. User can choose to allow | 
| `android:name=android.permission.ACCESS_COARSE_LOCATION` | Required to show users current location on App. User can choose to allow | 
| `android:name=android.permission.CAMERA` | Required to upload images to the application for use. User can choose to allow | 


 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
Sami Rahman.  
Kolkata, India.  
thefoodiofficial@gmail.com
