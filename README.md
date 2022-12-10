# The Sterling Wallet.

## Introduction.

This application will enable the authentication of the Sterling Banknote and redemption its value.

When the Banknote is redeemed, its private key is exported to the device 

It contains an Bitcoin wallet which can transact with valu

## Setup.

1. Install nodejs and npm: `sudo dnf install nodejs npm`
2. Install the Android Studio Flatpak: `flatpak install flathub com.google.AndroidStudio`
3. Launch Android Studio.
4. Select the standard components, including the Emulator, for installation (when prompted).
5. Append the following lines to your `~/.bashrc` file:

``export ANDROID_SDK_ROOT=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_SDK_ROOT/emulator
export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools``

6. Restart your terminal.

## Build and Run (Debug)

1. `cd` into this directory.
2. Open two instances of your terminal, preferably two tabs side-by-side.
3. In the first tab, run the following: `npx react-native start`
4. In the second tab, run the following: `npx react-native run-android`

## Build for Release