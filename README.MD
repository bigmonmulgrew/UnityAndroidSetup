This repo was created to solve a problem setting up Unity Game engine in an enterpeise environment.

In almost all cases you are better using the Unity Hub to manage installs.

For typical users
1. Open Unity Hub
2. Find your relevant installs
3. Click manage
4. Click Add modules
5. Make sure the Android build tools are selected
6. Make sure OpenJDK is selected
7. Make sure Android SDK & NDK tools is slected.
8. Press installs

If for some reason this doesnt work, continue reading. In our environment the android build tools are installed, but the SDK, JDK, NDK are not installed. We were having problems with using different versions on the system and for a list of complex reasons couldn't install through the hub.

This repo uses the versions from Unity 6000.2.8f1 as an example but you can switch these out with any version to meet your needs.