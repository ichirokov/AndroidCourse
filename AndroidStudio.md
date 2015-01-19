####Android Studio with java code

Week 1 and 2

Down load from http://developer.android.com/sdk/index.html#top
After installing have error: Java not found

Android Studio was unable to find a valid JVM.

Solution:

in Applications\Android Studio\Contents\Info.plist

We need to change :

For quick and dirty solution, Follow the answer by Mgamerz; open Android Studio in Finder (CTRL+Click > Show Package Contests > Contents > info.plist) and edit Key JVMOptions>JVMVersion from "1.6*" to "1.6+"

Migration from Eclipse to Android Studio, see : https://developer.android.com/sdk/installing/migrate.html

Migrating to Android Studio

SEE ALSO

IntelliJ FAQ on migrating to IntelliJ IDEA
Eclipse Compatibility Mode
FAQ on Migrating
If you have been using Eclipse with ADT, be aware that Android Studio is now the official IDE for Android, so you should migrate to Android Studio to receive all the latest IDE updates.

To migrate existing Android projects, simply import them using Android Studio:

1.In Android Studio, close any projects currently open. You should see the Welcome to Android Studio window.
2.Click Import Non-Android Studio project.
3.Locate the project you exported from Eclipse, expand it, select the build.gradle file and click OK.
In the following dialog, leave Use gradle wrapper selected and click OK. (You do not need to specify the Gradle home.)
4.Android Studio properly updates the project structure and creates the appropriate Gradle build file.

For more help getting started with Android Studio and the IntelliJ user experience, learn more about Android Studio and read FAQ on Migrating to IntelliJ IDEA.
