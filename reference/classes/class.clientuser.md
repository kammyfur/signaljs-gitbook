# ClientUser

**`Class`**

A Signal user to associate with a [Client](class.client.md)

## Constructors

### constructor()

> **new ClientUser**(client: [`Client`](class.client.md)): [`ClientUser`](class.clientuser.md)

#### Parameters

| Parameter | Type                        |
| --------- | --------------------------- |
| client    | [`Client`](class.client.md) |

#### Returns

[`ClientUser`](class.clientuser.md)

## Properties

### client

> **client**: `any`

## Methods

### deleteUserName()

> **deleteUserName**(): `Promise`<`void`>

Remove the currently set username

#### Returns

`Promise`<`void`>

### setAvatar()

> **setAvatar**(url: `string` | [`AttachmentBuilder`](class.attachmentbuilder.md)): `Promise`<`void`>

Change the avatar used by this user

#### Parameters

| Parameter | Type                                                          | Description                                                                             |
| --------- | ------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| url       | `string` \| [`AttachmentBuilder`](class.attachmentbuilder.md) | Either an [AttachmentBuilder](class.attachmentbuilder.md), or a path/data URI to a file |

#### Returns

`Promise`<`void`>

### setFirstName()

> **setFirstName**(name: `string`): `Promise`<`void`>

Change the user's first name, cannot be empty

#### Parameters

| Parameter | Type     | Description               |
| --------- | -------- | ------------------------- |
| name      | `string` | The new first name to use |

#### Returns

`Promise`<`void`>

### setLastName()

> **setLastName**(name: `string`): `Promise`<`void`>

Change the user's last name, can also be an empty string

#### Parameters

| Parameter | Type     | Description              |
| --------- | -------- | ------------------------ |
| name      | `string` | The new last name to use |

#### Returns

`Promise`<`void`>

### setMobileCoinAddress()

> **setMobileCoinAddress**(address?: `string`): `Promise`<`void`>

Change the user's MobileCoin address, can also be an empty string

#### Parameters

| Parameter | Type     | Description                       |
| --------- | -------- | --------------------------------- |
| address?  | `string` | The new MobileCoin address to use |

#### Returns

`Promise`<`void`>

### setStatus()

> **setStatus**(message?: `string`, emoji?: [`Emoji`](class.emoji.md)): `Promise`<`void`>

Change the status message for this user, can also be an empty string

#### Parameters

| Parameter | Type                      | Description               |
| --------- | ------------------------- | ------------------------- |
| message?  | `string`                  | The status message to use |
| emoji?    | [`Emoji`](class.emoji.md) | The status emoji to use   |

#### Returns

`Promise`<`void`>

### setUserName()

> **setUserName**(userName: `string`): `Promise`<`void`>

Change the username used by this account

#### Parameters

| Parameter | Type     | Description             |
| --------- | -------- | ----------------------- |
| userName  | `string` | The new username to use |

#### Returns

`Promise`<`void`>
