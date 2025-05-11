# Client

**`Class`**

The base Signal.js client interface

## Hierarchy

* `EventEmitter`.**`Client`**

## Constructors

### constructor()

> **new Client**(config: [`IConfig`](../interfaces/interface.iconfig.md)): [`Client`](class.client.md)

#### Parameters

| Parameter | Type                                            | Description                              |
| --------- | ----------------------------------------------- | ---------------------------------------- |
| config    | [`IConfig`](../interfaces/interface.iconfig.md) | The configuration to use with signal-cli |

#### Returns

[`Client`](class.client.md)

## Properties

### ignoreOldEvents

> **ignoreOldEvents**: `boolean` = `true`

Whether ignoring events sent while the client was offline is enabled

### process

> **process**: `ChildProcess`

The signal-cli process

### stickerPacks

> **stickerPacks**: [`ObjectCache`](class.objectcache.md) = `{}`

An [ObjectCache](class.objectcache.md) for the registered sticker packs

### user

> **user**: [`ClientUser`](class.clientuser.md)

The user configuration for this client

### verbose

> **verbose**: `boolean` = `false`

Whether verbose mode (logging events) should be enabled

## Methods

### addDevice()

> **addDevice**(uri: `string`): `Promise`<[`Device`](class.device.md)>

Associate a new device with this Signal account

#### Parameters

| Parameter | Type     | Description                                        |
| --------- | -------- | -------------------------------------------------- |
| uri       | `string` | The URI corresponding to the QR code on the device |

#### Returns

`Promise`<[`Device`](class.device.md)>

### createGroup()

> **createGroup**(name?: `string`): `Promise`<[`Group`](class.group.md)>

Create a new [Group](class.group.md)

#### Parameters

| Parameter | Type     | Description                        |
| --------- | -------- | ---------------------------------- |
| name?     | `string` | An optional name to give the group |

#### Returns

`Promise`<[`Group`](class.group.md)>

### getContacts()

> **getContacts**(): `Promise`<[`UserProfile`](class.userprofile.md)\[]>

Get a list of [UserProfile](class.userprofile.md)s the client knows about

#### Returns

`Promise`<[`UserProfile`](class.userprofile.md)\[]>

### getDevices()

> **getDevices**(): `Promise`<[`Device`](class.device.md)\[]>

Get a list of [Device](class.device.md)s associated with the client

#### Returns

`Promise`<[`Device`](class.device.md)\[]>

### getGroups()

> **getGroups**(): `Promise`<[`Group`](class.group.md)\[]>

Get a list of [Group](class.group.md)s the client is part of

#### Returns

`Promise`<[`Group`](class.group.md)\[]>

### getIdentities()

> **getIdentities**(): `Promise`<[`Identity`](class.identity.md)\[]>

Get a list of [Identity](class.identity.md) the client knows about

#### Returns

`Promise`<[`Identity`](class.identity.md)\[]>

### getStickerPacks()

> **getStickerPacks**(): `Promise`<[`StickerPack`](class.stickerpack.md)\[]>

Get a list of [StickerPack](class.stickerpack.md)s the client has access to

#### Returns

`Promise`<[`StickerPack`](class.stickerpack.md)\[]>

### isNumberOnSignal()

> **isNumberOnSignal**(number: `string`): `Promise`<`boolean`>

Check if a number is a Signal user

#### Parameters

| Parameter | Type     | Description         |
| --------- | -------- | ------------------- |
| number    | `string` | The number to check |

#### Returns

`Promise`<`boolean`>

### joinGroup()

> **joinGroup**(url: `string`): `Promise`<[`Group`](class.group.md)>

Join a group from an invite link

#### Parameters

| Parameter | Type     | Description                       |
| --------- | -------- | --------------------------------- |
| url       | `string` | The URL of the invite link to use |

#### Returns

`Promise`<[`Group`](class.group.md)>

### setDeviceName()

> **setDeviceName**(name: `string`): `Promise`<`void`>

Change the name of this device on the account

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| name      | `string` |

#### Returns

`Promise`<`void`>

### setRegistrationPin()

> **setRegistrationPin**(pin: `number`): `Promise`<`void`>

Set a PIN code to lock account registration

#### Parameters

| Parameter | Type     | Description         |
| --------- | -------- | ------------------- |
| pin       | `number` | The PIN code to set |

#### Returns

`Promise`<`void`>

### setSharedPreference()

> **setSharedPreference**(preference: [`SharedPreference`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.SharedPreference.md), value: `boolean`): `Promise`<`void`>

Change a shared Signal preference

#### Parameters

| Parameter  | Type                                                                                                                                  | Description                          |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| preference | [`SharedPreference`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.SharedPreference.md) | The name of the preference to change |
| value      | `boolean`                                                                                                                             | The new value of that preference     |

#### Returns

`Promise`<`void`>

## Events

### on()

> **on**(event: "cliEvent", listener: `Function`): [`Client`](class.client.md)

Emitted when a Signal event, even if unsupported, is received by signal-cli Client#cliEvent

#### Parameters

| Parameter | Type                                                                   |
| --------- | ---------------------------------------------------------------------- |
| event     | "cliEvent"                                                             |
| listener  | (event: [`ICLIEvent`](../interfaces/interface.iclievent.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "typingMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a typing message is received Client#typingMessage

#### Parameters

| Parameter | Type                                                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| event     | "typingMessage"                                                                                                           |
| listener  | (message: [`DMTypingMessage`](class.dmtypingmessage.md) \| [`GroupTypingMessage`](class.grouptypingmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "message", listener: `Function`): [`Client`](class.client.md)

Emitted when a data (text) message is received Client#message

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "message"                                                                                                         |
| listener  | (message: [`DMDataMessage`](class.dmdatamessage.md) \| [`GroupDataMessage`](class.groupdatamessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "editMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a message is edited Client#editMessage

#### Parameters

| Parameter | Type                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- |
| event     | "editMessage"                                                                                                     |
| listener  | (message: [`DMEditMessage`](class.dmeditmessage.md) \| [`GroupEditMessage`](class.groupeditmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reaction", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is added or removed to/from a message Client#reaction

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reaction"                                                                                                                        |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionAdd", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is added to a message Client#reactionAdd

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionAdd"                                                                                                                     |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "reactionRemove", listener: `Function`): [`Client`](class.client.md)

Emitted when a reaction is removed from a message Client#reactionRemove

#### Parameters

| Parameter | Type                                                                                                                              |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- |
| event     | "reactionRemove"                                                                                                                  |
| listener  | (message: [`GroupReactionMessage`](class.groupreactionmessage.md) \| [`DMReactionMessage`](class.dmreactionmessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "sticker", listener: `Function`): [`Client`](class.client.md)

Emitted when a sticker message is received Client#sticker

#### Parameters

| Parameter | Type                                                                                                                          |
| --------- | ----------------------------------------------------------------------------------------------------------------------------- |
| event     | "sticker"                                                                                                                     |
| listener  | (message: [`GroupStickerMessage`](class.groupstickermessage.md) \| [`DMStickerMessage`](class.dmstickermessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "deleteMessage", listener: `Function`): [`Client`](class.client.md)

Emitted when a message in a channel gets deleted Client#deleteMessage

#### Parameters

| Parameter | Type                                                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| event     | "deleteMessage"                                                                                                           |
| listener  | (message: [`GroupDeleteMessage`](class.groupdeletemessage.md) \| [`DMDeleteMessage`](class.dmdeletemessage.md)) => `void` |

#### Returns

[`Client`](class.client.md)

> **on**(event: "groupUpdate", listener: `Function`): [`Client`](class.client.md)

Emitted when a group's information gets updated Client#groupUpdate

#### Parameters

| Parameter | Type                                         |
| --------- | -------------------------------------------- |
| event     | "groupUpdate"                                |
| listener  | (group: [`Group`](class.group.md)) => `void` |

#### Returns

[`Client`](class.client.md)
