# SentStickerMessage

**`Class`**

A sticker as sent to Signal

## Hierarchy

* [`SentMessage`](class.sentmessage.md).**`SentStickerMessage`**

## Constructors

### constructor()

> **new SentStickerMessage**( time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), sticker: [`Sticker`](class.sticker.md)): [`SentStickerMessage`](class.sentstickermessage.md)

#### Parameters

| Parameter | Type                                             | Description                                 |
| --------- | ------------------------------------------------ | ------------------------------------------- |
| time      | `number`                                         | The timestamp at which the sticker was sent |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) | The channel the sticker was sent at         |
| client    | [`Client`](class.client.md)                      |                                             |
| sticker   | [`Sticker`](class.sticker.md)                    | The sticker that was sent                   |

#### Returns

[`SentStickerMessage`](class.sentstickermessage.md)

#### Overrides

[`SentMessage`](class.sentmessage.md).[`constructor`](class.sentmessage.md#constructor)

## Properties

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

Channel in which the message was created

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`channel`](class.sentmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`client`](class.sentmessage.md#client)

### createdAt

> **createdAt**: `Date`

Date at which the message was created

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdAt`](class.sentmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp at which the message was created

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdTimestamp`](class.sentmessage.md#createdtimestamp)

### sticker

> **sticker**: [`Sticker`](class.sticker.md)

[Sticker](class.sticker.md) that was sent

## Methods

### delete()

> **delete**(): `Promise`<`void`>

Delete the sticker message

#### Returns

`Promise`<`void`>
