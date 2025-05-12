# DM

**`Class`**

A Signal 1-to-1 chat

## Hierarchy

* [`Channel`](class.channel.md).**`DM`**

## Constructors

### constructor()

> **new DM**( userId: `string`, number: `string`, client: [`Client`](class.client.md)): [`DM`](class.dm.md)

#### Parameters

| Parameter | Type                        | Description             |
| --------- | --------------------------- | ----------------------- |
| userId    | `string`                    | The ID of the user      |
| number    | `string`                    | The user's phone number |
| client    | [`Client`](class.client.md) |                         |

#### Returns

[`DM`](class.dm.md)

#### Overrides

[`Channel`](class.channel.md).[`constructor`](class.channel.md#constructor)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### group

> **group**: `boolean` = `false`

Whether the channel is a group chat

#### Overrides

[`Channel`](class.channel.md).[`group`](class.channel.md#group)

### id

> **id**: `string`

Channel (DM or group) ID

#### Inherited from

[`Channel`](class.channel.md).[`id`](class.channel.md#id)

### number

> **number**: `string`

Recipient's phone number

## Methods

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
