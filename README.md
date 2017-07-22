# [Loopin](https://loopin.cloud) Android app

Forked from https://github.com/nextcloud/android.

Soon available on Play Store.

**Original License:** [GPLv2](https://github.com/nextcloud/android/blob/master/LICENSE.txt)

New contributions are added under [AGPLv3](https://www.gnu.org/licenses/agpl.txt).

### Common software dependencies.

There are some tools needed, no matter what is your specific IDE or build tool of preference.

[git][1] is used to access to the different versions of the Nextcloud's source code. Download and install the version appropriate for your operating system from [here][2]. Add the full path to the 'bin/' directory from your git installation into the PATH variable of your environment so that it can be used from any location.

The [Android SDK][3] is necessary to build the app. There are different options to install it in your system, depending of the IDE you decide to use. Check Google documentation about [installation][4] for more details on these options. After installing it, add the full path to the directories 'tools/' and 'platform-tools/' from your Android SDK installation into the PATH variable of your environment.

Open a terminal and type 'android' to start the Android SDK Manager. To build the Nextcloud/Loopin for Android app you will need to install at least the next SDK packages:

* Android SDK Tools and Android SDK Platform-tools (already installed); upgrade to their last versions is usually a good idea.
* Android SDK Build-Tools 24.0.2.
* Android 7.0 (API 24), SDK Platform; needed to build the app.

Install any other package you consider interesting, such as emulators.

For other software dependencies check the details in the section corresponding to your preferred IDE or build system.

## For more info, please read [SETUP.md](https://github.com/LoopinCloud/android-client/blob/master/SETUP.md)
