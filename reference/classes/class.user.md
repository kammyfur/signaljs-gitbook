# User

**`Class`**

A Signal user

## Constructors

### constructor()

> **new User**( data: `any`, dataType: [`UserDataType`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.UserDataType.md), client: [`Client`](class.client.md)): [`User`](class.user.md)

#### Parameters

| Parameter | Type                                                                                                                          | Description                                               |
| --------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| data      | `any`                                                                                                                         | Sufficient data to create a [User](class.user.md)         |
| dataType  | [`UserDataType`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.UserDataType.md) | The type of data used to create the [User](class.user.md) |
| client    | [`Client`](class.client.md)                                                                                                   |                                                           |

#### Returns

[`User`](class.user.md)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### device

> **device**?: `number` = `null`

The ID of the device the user is on

### nickName

> **nickName**?: `string` = `null`

The user's nickname they set

### number

> **number**?: `string` = `null`

The user's phone number

### uuid

> **uuid**?: `string` = `null`

The user's UUID

## Methods

### addToContacts()

> **addToContacts**(name?: `string`): `Promise`<`void`>

Add the user to the contacts list

#### Parameters

| Parameter | Type     | Description               |
| --------- | -------- | ------------------------- |
| name?     | `string` | The name to give the user |

#### Returns

`Promise`<`void`>

### createDM()

> **createDM**(): [`DM`](class.dm.md)

Create a [DM](class.dm.md) with this user

#### Returns

[`DM`](class.dm.md)

### removeFromContacts()

> **removeFromContacts**(): `Promise`<`void`>

Remove the user from the contact list

#### Returns

`Promise`<`void`>

### setBlocked()

> **setBlocked**(blocked: `boolean`): `Promise`<`void`>

Block or unblock this user

#### Parameters

| Parameter | Type      | Description                               |
| --------- | --------- | ----------------------------------------- |
| blocked   | `boolean` | Whether the user should be blocked or not |

#### Returns

`Promise`<`void`>

### setDisappearingMessagesTime()

> **setDisappearingMessagesTime**(time?: `number`): `Promise`<`void`>

Change the disappearing messages expiration time

#### Parameters

| Parameter | Type     | Description                                                                                           |
| --------- | -------- | ----------------------------------------------------------------------------------------------------- |
| time?     | `number` | <p>The time (in seconds) before a message gets deleted.<br>Use 0 to disable disappearing messages</p> |

#### Returns

`Promise`<`void`>

### verify()

> **verify**(safetyNumber?: `string`): `Promise`<`void`>

Verify the user's safety number

#### Parameters

| Parameter     | Type     | Description                                                                        |
| ------------- | -------- | ---------------------------------------------------------------------------------- |
| safetyNumber? | `string` | <p>The user's safety number.<br>If not present, all known keys will be trusted</p> |

#### Returns

`Promise`<`void`>

### fromNumber()

> `Static` **fromNumber**(number: `string`, client: [`Client`](class.client.md)): [`User`](class.user.md)

Create a new [User](class.user.md) from a phone number

#### Parameters

| Parameter | Type                        | Description             |
| --------- | --------------------------- | ----------------------- |
| number    | `string`                    | The phone number to use |
| client    | [`Client`](class.client.md) |                         |

#### Returns

[`User`](class.user.md)
