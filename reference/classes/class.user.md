# User

**`Class`**

## Constructors

### constructor()

> **new User**( data: `any`, dataType: [`UserDataType`](broken-reference), client: [`Client`](broken-reference)): [`User`](class.user.md)

#### Parameters

| Parameter | Type                               |
| --------- | ---------------------------------- |
| data      | `any`                              |
| dataType  | [`UserDataType`](broken-reference) |
| client    | [`Client`](broken-reference)       |

#### Returns

[`User`](class.user.md)

## Properties

### client

> `private` **client**: [`Client`](broken-reference)

### device

> **device**?: `number` = `null`

### nickName

> **nickName**?: `string` = `null`

### number

> **number**?: `string` = `null`

### uuid

> **uuid**?: `string` = `null`

## Methods

### addToContacts()

> **addToContacts**(name?: `string`, disappearingMessagesTime?: `number`): `Promise`<`void`>

#### Parameters

| Parameter                 | Type     |
| ------------------------- | -------- |
| name?                     | `string` |
| disappearingMessagesTime? | `number` |

#### Returns

`Promise`<`void`>

### createDM()

> **createDM**(): [`DM`](broken-reference)

#### Returns

[`DM`](broken-reference)

### removeFromContacts()

> **removeFromContacts**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

### setBlocked()

> **setBlocked**(blocked: `boolean`): `Promise`<`void`>

#### Parameters

| Parameter | Type      |
| --------- | --------- |
| blocked   | `boolean` |

#### Returns

`Promise`<`void`>

### setDisappearingMessagesTime()

> **setDisappearingMessagesTime**(time?: `number`): `Promise`<`void`>

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| time?     | `number` |

#### Returns

`Promise`<`void`>

### verify()

> **verify**(safetyNumber?: `string`): `Promise`<`void`>

#### Parameters

| Parameter     | Type     |
| ------------- | -------- |
| safetyNumber? | `string` |

#### Returns

`Promise`<`void`>

### fromNumber()

> `Static` **fromNumber**(number: `string`, client: [`Client`](broken-reference)): [`User`](class.user.md)

#### Parameters

| Parameter | Type                         |
| --------- | ---------------------------- |
| number    | `string`                     |
| client    | [`Client`](broken-reference) |

#### Returns

[`User`](class.user.md)
