# ReactNativeApp
I'm adding features to this app as learning purposes.

## Dev environment
- Linux
- Visual Studio Code with React Native Tools
- Android Emulator 30.7.4, Pixel 5 API 30, Play Store, Android 11.0 (R) Revision 3, CPU x86
- Java 16 (jdk-adoptopenjdk 16.0.1.u9-1)
- Gradle 7.1

## Setting up the development environment
https://reactnative.dev/docs/environment-setup

My .bash_profile for Linux:
```
# for React Native development
export ANDROID_HOME=$HOME/.Android/Sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
export JAVA_HOME=/usr/lib/jvm/default
export PATH="$HOME/.npm-packages/bin:$PATH"
```