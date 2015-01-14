####Android with Eclipse.

For 1 week:
usefull link :https://docs.google.com/document/d/1Sp8Ul9x7FO5ad6z7ac7srvM0ga9VBS2149uTyCOut7g/edit?usp=sharing

#####For  Windows computer.


Before download Eclipse we need to have JVM on your computer:

See https://java.com/en/download/help/mac_install.xml. 

And JDK:
 http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
 
 Check version from Terminal: Javac -version, related JDK

#####Getting Android:

See http://developer.android.com/sdk/installing/installing-adt.html

1. click on Eclipse 3.7.2 (Indigo) or greater - http://eclipse.org/mobile/

2. from http://eclipse.org/mobile/ click on Install Guide -       http://wiki.eclipse.org/Eclipse/Installation#Download_Eclipse
See descriptions for Eclipse 4.4 (Luna).
Click  Eclipse Downloads Page. - http://www.eclipse.org/downloads

3. Click Eclipse IDE for Java Developers, 153 MB - http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/luna/SR1/eclipse-java-luna-SR1-macosx-cocoa-x86_64.tar.gz

           Install Eclipse and move it to Applications. Start Eclipse.

4. After start Eclipse see: Download the ADT Plugin
see plgin : https://dl-ssl.google.com/android/eclipse/

5. Android Device.
  Open Device, go setting : General: About device:Android version: 4.4.2
  On that version Developer option by default is hiden , we need to start it: Settings > About device > Build     number.
  Now we are on Development mode.

6. From Eclipse Menu: Run:Run Configuration..:Target:Launch on all compatible devices/AVD's: and select: Active devices and AVD's, then apply and run.
  Have Error: CPU acceleration status: HAX kernel module is not installed: used Eclipse and Android Studio

Also if I run intelhaxm.exe for Eclipse or Android Studio(intelhaxm-android.exe)

We have error message : c:\Documents and Settings\igor\..\Temp\\Intel\HAXM\1.1.1\2015-01-14_11-24-13\setup.exe is not valid win32 application. It looks not supported Windows HP 32-bit OS.
