# GroupEditor

**`Class`**

## Constructors

### constructor()

> **new GroupEditor**( initiator: [`Group`](broken-reference), data: `any`, client: [`Client`](broken-reference)): [`GroupEditor`](class.groupeditor.md)

#### Parameters

| Parameter | Type                         |
| --------- | ---------------------------- |
| initiator | [`Group`](broken-reference)  |
| data      | `any`                        |
| client    | [`Client`](broken-reference) |

#### Returns

[`GroupEditor`](class.groupeditor.md)

## Properties

### admins

> **admins**: [`User`](class.user.md)\[]

### bannedMembers

> **bannedMembers**: [`User`](class.user.md)\[]

### client

> `private` **client**: [`Client`](broken-reference)

### description

> **description**?: `string`

### expirationSeconds

> **expirationSeconds**: `number`

### id

> **id**: `string`

### initiator

> **initiator**: [`Group`](broken-reference)

### inviteLink

> **inviteLink**?: `string`

### isBlocked

> **isBlocked**: `boolean`

### isMember

> **isMember**: `boolean`

### members

> **members**: [`User`](class.user.md)\[]

### name

> **name**: `string`

### pendingMembers

> **pendingMembers**: [`User`](class.user.md)\[]

### permissions

> **permissions**: [`GroupPermissions`](broken-reference)

### requestingMembers

> **requestingMembers**: [`User`](class.user.md)\[]

## Methods

### resetInviteLink()

> **resetInviteLink**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

### setAvatar()

> **setAvatar**(avatar: [`AttachmentBuilder`](class.attachmentbuilder.md)): `Promise`<`void`>

#### Parameters

| Parameter | Type                                              |
| --------- | ------------------------------------------------- |
| avatar    | [`AttachmentBuilder`](class.attachmentbuilder.md) |

#### Returns

`Promise`<`void`>

### setDescription()

> **setDescription**(description: `string`): `Promise`<`void`>

#### Parameters

| Parameter   | Type     |
| ----------- | -------- |
| description | `string` |

#### Returns

`Promise`<`void`>

### setExpirationSeconds()

> **setExpirationSeconds**(seconds: `number`): `Promise`<`void`>

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| seconds   | `number` |

#### Returns

`Promise`<`void`>

### setLinkStatus()

> **setLinkStatus**(status: [`GroupLinkStatus`](../enumerations/enumeration.grouplinkstatus.md)): `Promise`<`void`>

#### Parameters

| Parameter | Type                                                                |
| --------- | ------------------------------------------------------------------- |
| status    | [`GroupLinkStatus`](../enumerations/enumeration.grouplinkstatus.md) |

#### Returns

`Promise`<`void`>

### setName()

> **setName**(name: `string`): `Promise`<`void`>

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| name      | `string` |

#### Returns

`Promise`<`void`>
