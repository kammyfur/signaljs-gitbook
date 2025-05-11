# Group

**`Class`**

A Signal group

## Hierarchy

* [`Channel`](class.channel.md).**`Group`**

## Constructors

### constructor()

> **new Group**(groupId: `string`, client: [`Client`](class.client.md)): [`Group`](class.group.md)

#### Parameters

| Parameter | Type                        | Description         |
| --------- | --------------------------- | ------------------- |
| groupId   | `string`                    | The ID of the group |
| client    | [`Client`](class.client.md) |                     |

#### Returns

[`Group`](class.group.md)

#### Overrides

[`Channel`](class.channel.md).[`constructor`](class.channel.md#constructor)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### group

> **group**: `boolean` = `true`

Whether the channel is a group chat

#### Overrides

[`Channel`](class.channel.md).[`group`](class.channel.md#group)

### id

> **id**: `string`

Channel (DM or group) ID

#### Inherited from

[`Channel`](class.channel.md).[`id`](class.channel.md#id)

## Methods

### addAdmin()

> **addAdmin**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Add one or more admins to the group

#### Parameters

| Parameter | Type                       | Description         |
| --------- | -------------------------- | ------------------- |
| ...users  | [`User`](class.user.md)\[] | The admin(s) to add |

#### Returns

`Promise`<`void`>

### addMember()

> **addMember**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Add one or more members to the group

#### Parameters

| Parameter | Type                       | Description          |
| --------- | -------------------------- | -------------------- |
| ...users  | [`User`](class.user.md)\[] | The member(s) to add |

#### Returns

`Promise`<`void`>

### banMember()

> **banMember**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Permanently ban one or more members from the group

#### Parameters

| Parameter | Type                       | Description          |
| --------- | -------------------------- | -------------------- |
| ...users  | [`User`](class.user.md)\[] | The member(s) to ban |

#### Returns

`Promise`<`void`>

### editor()

> **editor**(): `Promise`<[`GroupEditor`](class.groupeditor.md)>

Edit the group's information

#### Returns

`Promise`<[`GroupEditor`](class.groupeditor.md)>

### leave()

> **leave**(deleteLocalData: `boolean` = `false`, successorAdmins?: [`User`](class.user.md)\[]): `Promise`<`void`>

Leave the group

If the client is an administrator of the group, `successorAdmins` has to be set

#### Parameters

| Parameter        | Type                       | Default value | Description                                                                                                                   |
| ---------------- | -------------------------- | ------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| deleteLocalData  | `boolean`                  | false         | Whether local client data about the group should be deleted                                                                   |
| successorAdmins? | [`User`](class.user.md)\[] | undefined     | <p>One or more member(s) to make group admins after the client<br>leaves the group, in case this client is the only admin</p> |

#### Returns

`Promise`<`void`>

### removeAdmin()

> **removeAdmin**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Remove one or more admins

#### Parameters

| Parameter | Type                       | Description            |
| --------- | -------------------------- | ---------------------- |
| ...users  | [`User`](class.user.md)\[] | The admin(s) to remove |

#### Returns

`Promise`<`void`>

### removeMember()

> **removeMember**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Remove (kick) one or more members from the group

#### Parameters

| Parameter | Type                       | Description             |
| --------- | -------------------------- | ----------------------- |
| ...users  | [`User`](class.user.md)\[] | The member(s) to remove |

#### Returns

`Promise`<`void`>

### send()

> **send**(text: `string`, options?: [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

Send a message to the channel

#### Parameters

| Parameter | Type                                                                                                                                    | Description                                    |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| text      | `string`                                                                                                                                | The text of the message, or an empty string    |
| options?  | [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md) | The optional options used to build the message |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Overrides

[`Channel`](class.channel.md).[`send`](class.channel.md#send)

### sendSticker()

> **sendSticker**(sticker: [`Sticker`](class.sticker.md)): `Promise`<`void`>

Send a sticker to this channel

#### Parameters

| Parameter | Type                          | Description         |
| --------- | ----------------------------- | ------------------- |
| sticker   | [`Sticker`](class.sticker.md) | The sticker to send |

#### Returns

`Promise`<`void`>

### setBlocked()

> **setBlocked**(blocked: `boolean`): `Promise`<`void`>

Block or unblock the group

#### Parameters

| Parameter | Type      | Description                                |
| --------- | --------- | ------------------------------------------ |
| blocked   | `boolean` | Whether the group should be blocked or not |

#### Returns

`Promise`<`void`>

### setTyping()

> **setTyping**(typing: `boolean`): `Promise`<`void`>

Set the client's typing status for this channel

#### Parameters

| Parameter | Type      | Description                                |
| --------- | --------- | ------------------------------------------ |
| typing    | `boolean` | Whether the client should be typing or not |

#### Returns

`Promise`<`void`>

#### Overrides

[`Channel`](class.channel.md).[`setTyping`](class.channel.md#settyping)

### unbanMember()

> **unbanMember**(...users: [`User`](class.user.md)\[]): `Promise`<`void`>

Unban one or more permanently banned members from the group

#### Parameters

| Parameter | Type                       | Description            |
| --------- | -------------------------- | ---------------------- |
| ...users  | [`User`](class.user.md)\[] | The member(s) to unban |

#### Returns

`Promise`<`void`>
