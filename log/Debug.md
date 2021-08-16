##Bug: Gradle project sync failed.

######option 1:

Goto File -> Invalidate caches / Restart
Shutdown Android Studio
Rename/remove .gradle folder in the user home directory
Restart Android Studio (It will download gradle metadata and data)
Gradle build succeed
Rebuild project. Done.

reference
https://stackoverflow.com/questions/29808199/error-running-android-gradle-project-sync-failed-please-fix-your-project-and-t
# Android-app

无法创建FileHasher类型的服务 问题


######option 2:
delete .lock file

reference
https://blog.csdn.net/dengmengxin/article/details/106353229


######option 3: (work in this way)
check the version match

Gradle	7.0.2	7.0.2	To learn more, see updating Gradle.
SDK Build Tools	30.0.2	30.0.2	Install or configure SDK Build Tools.

-reference: 
https://developer.android.com/studio/releases/gradle-plugin#updating-gradle

-outcome:

Starting Gradle Daemon...
Gradle Daemon started in 3 s 317 ms
Checking the license for package Android SDK Build-Tools 30.0.2 in /Users/zhangyanni/Library/Android/sdk/licenses
License for package Android SDK Build-Tools 30.0.2 accepted.
Preparing "Install Android SDK Build-Tools 30.0.2 (revision: 30.0.2)".
"Install Android SDK Build-Tools 30.0.2 (revision: 30.0.2)" ready.
Installing Android SDK Build-Tools 30.0.2 in /Users/zhangyanni/Library/Android/sdk/build-tools/30.0.2
"Install Android SDK Build-Tools 30.0.2 (revision: 30.0.2)" complete.
"Install Android SDK Build-Tools 30.0.2 (revision: 30.0.2)" finished.