## 1.0.30 [February 15, 2020]

* Fixed an issue causing audio player to re-initialize on widget rebuild even though param 
values haven't changed

## 1.0.29 [February 14, 2020]

* Changed [position] from int to double

## 1.0.28 [February 14, 2020]

* Added [position] param for Video set set/update seek bar position

## 1.0.27 [February 14, 2020]

* Added **preferredAudioLanguage** param to Video to set audio language on player init

## 1.0.26 [February 11, 2020]

* Added support for HLS multi-audio for Android

## 1.0.25 [February 7, 2020]

* Fixed a bug where audio service wasn't being destroyed with player
* Fixed an issue where onTime was not being called after audio player is disposed once and recreated

## 1.0.24 [February 7, 2020]

* Updated example to include media change callback

## 1.0.23 [February 7, 2020]

* Fixed an issue where media change (url change) was not being registered with Android audio player

## 1.0.22 [February 7, 2020]

* Fixed an issue where audio player on Android native side was not being disposed properly

## 1.0.21 [February 7, 2020]

* Changed video platform view dispose to use method channel

## 1.0.20 [February 7, 2020]

* Fixed an issue throwing exception at video platform view dispose

## 1.0.19 [January 29, 2020]

* Merged pull request #15 - Ability to show/hide player controls

## 1.0.18 [January 17, 2020]

* Moved player initialisation outside of build() method fixing issue where the underlying platform view keeps rebuilding whenever widget updates.

## 1.0.17 [January 4, 2020]

* Fixed an issue where audioServiceBinder was being used before initialisation

## 1.0.16 [December 10, 2019]

* Fixed an issue where onDuration wasn't being called after player re-init

## 1.0.15 [December 10, 2019]

* Fixed AVPlayer (iOS) reset issue on dispose

## 1.0.14 [December 10, 2019]

* Fixed an issue where Audio instance wasn't being cleared on dispose

## 1.0.13 [December 10, 2019]

* Implemented audio player as singleton

## 1.0.12 [December 10, 2019]

* Fixed an issue where dispose on iOS was failing because it was trying to remove observers twice

## 1.0.11 [October 27, 2019]

* fixed a bug in example app causing audio player to stop sending events after onComplete

* fixed an issue with iOS audio player implementation causing URLs to not play

## 1.0.10 [October 27, 2019]

* fixed an issue causing audio player to crash on malformed URLs

* added better exception handling for audio player

## 1.0.9 [October 26, 2019]

* Implemented `desiredState` flag in Video widget to play/pause video playback.

## 1.0.8 [October 24, 2019]

* fixed an issue where audio player was not playing new media on url change

## 1.0.7 [October 24, 2019]

* Added onDuration callback & updated example to reflect the change
* Implemented onComplete for Android audio player

## 1.0.6 [October 17, 2019]

* Fixed an issue with audio player where onPlay & onPause were not being fired

## 1.0.5 [October 12, 2019]

* Fixed an issue causing iOS plugin to not respond to dispose

## 1.0.4 [October 12, 2019]

* Updated iOS plugin to use Swift 5 compiler

## 1.0.3 [October 12, 2019]

* Implemented video playback for Android
* Fixed an issue with lock screen controls where subtitle wasn't being displayed correctly

## 1.0.2 [October 9, 2019]

* Implemented video playback for iOS

## 1.0.1
* Updated documentation to include example implementation for the plugin

## 1.0.0

* Play audio for both iOS & Android
* Play audio in background with lock screen controls for both iOS & Android