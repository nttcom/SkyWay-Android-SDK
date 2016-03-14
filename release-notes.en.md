SkyWay Android SDK release notes
=============================

[日本語](./release-notes.md)

###　New features
--------------------------

Version 0.2.2

* Fixed a bug in the metadata option of MediaConnection.

Version 0.2.1

* Changed the default value to ```YES``` on *turn* property of SKWPeerOption Class.

Version 0.2.0

* Added methods to MediaStream Class.
	- switchCamera

*　Fixed bug that caused the mediaConnection to fail on some devices.

* Fixed bug that disconnected existing P2P connections when `peer.disconnect()` was called.

* Fixed bug that caused sending large files from Android to JS to fail.



Version 0.1.1

* Added XHR Support

* Fixed an issue where the screen orientation may unexpectedly change during video chat.


Version 0.1.0

* first release
