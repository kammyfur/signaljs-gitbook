# GroupEditor

**`Class`**

A collector and editor of information related to the group

## Constructors

### constructor()

> **new GroupEditor**( initiator: [`Group`](class.group.md), data: `any`, client: [`Client`](class.client.md)): [`GroupEditor`](class.groupeditor.md)

#### Parameters

| Parameter | Type                        | Description               |
| --------- | --------------------------- | ------------------------- |
| initiator | [`Group`](class.group.md)   | The group being worked on |
| data      | `any`                       | Data from signal-cli      |
| client    | [`Client`](class.client.md) |                           |

#### Returns

[`GroupEditor`](class.groupeditor.md)

## Properties

### admins

> **admins**: [`User`](class.user.md)\[]

List of admins

### bannedMembers

> **bannedMembers**: [`User`](class.user.md)\[]

List of members banned from the group

### client

> `private` **client**: [`Client`](class.client.md)

### description

> **description**?: `string`

Optional description for the group

### expirationSeconds

> **expirationSeconds**: `number`

If disappearing messages are enabled, amount of seconds before a message disappears

### id

> **id**: `string`

ID of the group

### initiator

> **initiator**: [`Group`](class.group.md)

[Group](class.group.md) being worked on

### inviteLink

> **inviteLink**?: `string`

If enabled, link to the group

### isBlocked

> **isBlocked**: `boolean`

Whether this client has blocked the group or not

### isMember

> **isMember**: `boolean`

Whether this client is a member of the group or not

### members

> **members**: [`User`](class.user.md)\[]

List of members in the group

### name

> **name**: `string`

Name of the group

### pendingMembers

> **pendingMembers**: [`User`](class.user.md)\[]

List of members pending acceptance

### permissions

> **permissions**: [`GroupPermissions`](class.grouppermissions.md)

Permission information

### requestingMembers

> **requestingMembers**: [`User`](class.user.md)\[]

List of members pending admin approval

## Methods

### resetInviteLink()

> **resetInviteLink**(): `Promise`<`void`>

Reset the group invite link and create a new one

#### Returns

`Promise`<`void`>

### setAvatar()

> **setAvatar**(avatar: [`AttachmentBuilder`](class.attachmentbuilder.md)): `Promise`<`void`>

Update the avatar of the group

#### Parameters

| Parameter | Type                                              | Description          |
| --------- | ------------------------------------------------- | -------------------- |
| avatar    | [`AttachmentBuilder`](class.attachmentbuilder.md) | The new group avatar |

#### Returns

`Promise`<`void`>

### setDescription()

> **setDescription**(description: `string`): `Promise`<`void`>

Update the description of the group

#### Parameters

| Parameter   | Type     | Description               |
| ----------- | -------- | ------------------------- |
| description | `string` | The new group description |

#### Returns

`Promise`<`void`>

### setExpirationSeconds()

> **setExpirationSeconds**(seconds: `number`): `Promise`<`void`>

Update the disappearing messages setting for the group

#### Parameters

| Parameter | Type     | Description                                                                                           |
| --------- | -------- | ----------------------------------------------------------------------------------------------------- |
| seconds   | `number` | <p>The time (in seconds) before a message gets deleted.<br>Use 0 to disable disappearing messages</p> |

#### Returns

`Promise`<`void`>

### setLinkStatus()

> **setLinkStatus**(status: [`GroupLinkStatus`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupLinkStatus.md)): `Promise`<`void`>

Change the status of the group invite link

#### Parameters

| Parameter | Type                                                                                                                                | Description                      |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- |
| status    | [`GroupLinkStatus`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupLinkStatus.md) | The new group invite link status |

#### Returns

`Promise`<`void`>

### setName()

> **setName**(name: `string`): `Promise`<`void`>

Update the name of the group

#### Parameters

| Parameter | Type     | Description        |
| --------- | -------- | ------------------ |
| name      | `string` | The new group name |

#### Returns

`Promise`<`void`>
