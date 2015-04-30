Open-source porting of Quake 2 on Android

Web site : http://www.jeyries.fr/quake2android/

Devellopers Wanted !

Main issues :

  * performance improvement
  * support more phones : Nexus One, Samsung Galaxy S, Motorola Droid X ...

Want to start hacking right now ? try this :

```
svn checkout http://quake2android.googlecode.com/svn/trunk/ quake2android
cd quake2android
ndk-build
android update project -t "android-4" -p .
ant install
```

If you want to join this project and submit patches, contact me at :

jeyries at gmail dot com


