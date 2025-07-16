# flutter_push_notifications

1. Create an project on fcm console.
2. https://console.firebase.google.com/
3. copy the package from android/app/build.gradle file.
4. and paste into(Clicked the project on fcm and select the android icon and paste the copied package)
5. After configuration
6. Run this command to add the firebase lib in flutter .
7. flutter pub add firebase_core and this flutter pub add firebase_messaging
8. For sending notification.
9. go to dashboard, left side click on Run->Messaging->Create Campaign and select Firebase notification message.

This is the example of the background push notification means app should be in the background by default for foreground push notification we will check later


There are three way to send the notification
1. By simple way(create campaign and send the notification))
2. By creating the channel and send the notification
3. through fcm token.

For foregroud push notification please visit this youtube video
https://www.youtube.com/watch?v=vR2q7at97Cs&t=873s
