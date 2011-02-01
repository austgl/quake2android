
### automatic way : eclipse integration

install eclipse
install ADT plugin
install CDT plugin
install subclipse plugin

from eclipse :

add SVN repository https://quake2android.googlecode.com/svn

checkout trunk as a project in workspace



### OR manual way :

svn checkout https://quake2android.googlecode.com/svn/trunk/ quake2android

cd quake2android

ndk-build V=1

android update project -t "android-4" -p .

ant install

### other usefull commands

ant debug

adb uninstall com.jeyries.quake2

adb install bin/Quake2-debug.apk



