# Changelog

## 1.0.0-rc.1, 1.0.1-rc.1

Welcome to Signal.js! This is the first release candidate version of Signal.js. This means the API is now stable and the library should be reliable enough to be used in production projects.

However, issues related to stability and intended behavior may arise as this is not a perfectly production-ready release. Should you find any issue with this version, feel free to report it to us [through our bug tracker](https://bugs.equestria.dev/issues/SGJS) or [by email](mailto:hello@equestria.dev).

Here is what is new in this version:

* `IConfig#ignoreOldEvents`, `Client#ignoreOldEvents`: Ignoring events sent while the client was offline is now implemented
* Cleaned up source code
* Added `@equestria.dev/signal-cli` as a dependency to bundle signal-cli directly

## 0.5.0-beta.0

* `ClientUser`: A class for managing information about the client's Signal user is now implemented
* `SharedPreference`: A list of preferences shared across devices is now implemented
* `Client#setSharedPreference`: Updating a preference shared across devices is now implemented
* `Client#setDeviceName`: Changing the device's name is now implemented
* `Client#setRegistrationPin`: Setting a registration lock PIN is now implemented
* `ClientUser#deleteUserName`: Removing a username is now implemented
* `ClientUser#setUserName`: Changing a username is now implemented
* `ClientUser#setFirstName`: Changing the client's first name is now implemented
* `ClientUser#setLastName` Changing the client's last name is now implemented
* `ClientUser#setMobileCoinAddress`: Changing the client's MobileCoin address is now implemented
* `ClientUser#setStatus`: Changing the client's status information is now implemented
* `ClientUser#setAvatar`: Changing the client's avatar is now implemented

## 0.4.0-beta.1

* Fix the readme

## 0.4.0-beta.0

* First changelog
* `Client#isNumberOnSignal`: Checking if a phone number is registered on signal is now implemented
* `Client#getGroups`: Obtaining a list of groups the client is part of is now implemented
* `Device`: A class for devices linked to the Signal account has been added
* `Device#remove`: Removing devices from the Signal account is now implemented
* `Client#addDevice`: Linking a new device to the account is now implemented
* `Client#getDevices`: Obtaining a list of devices associated with the client's Signal account is now implemented
* `UserProfile`: A class for other user profiles has been added
* `IUserProfileStatus`: A type for user status has been added
* `Client#getContacts`: Obtaining a list of user profiles the client knows about is now implemented
* `Identity`: A class for identities and known keys has been added
* `Client#getIdentities`: Obtaining a list of identities and keys the client knows about is now implemented
* `StickerPack#installed`: Sticker packs can now report if they are installed to the Signal account
* `Client#getStickerPacks`: Obtaining a list of available sticker packs is now implemented

## 0.3.2-beta.1

* Documentation update
* `Client#createGroup`: Creating groups is now implemented
* `Client#joinGroup`: Joining groups from an invite link is now implemented
