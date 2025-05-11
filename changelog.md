# Changelog

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
