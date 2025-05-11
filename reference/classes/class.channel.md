# Channel

**`Class`**

A channel (either DM or group) on Signal

## Hierarchy

* [`DM`](class.dm.md)
* [`Group`](class.group.md)

## Constructors

### constructor()

> **new Channel**(): [`Channel`](class.channel.md)

#### Returns

[`Channel`](class.channel.md)

## Properties

### group

> **group**: `boolean`

Whether the channel is a group chat

### id

> **id**: `string`

Channel (DM or group) ID

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

### setTyping()

> **setTyping**(typing: `boolean`): `Promise`<`void`>

Set the client's typing status for this channel

#### Parameters

| Parameter | Type      | Description                                |
| --------- | --------- | ------------------------------------------ |
| typing    | `boolean` | Whether the client should be typing or not |

#### Returns

`Promise`<`void`>
