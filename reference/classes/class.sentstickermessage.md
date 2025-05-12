# SentStickerMessage

**`Class`**

## Hierarchy

* [`SentMessage`](class.sentmessage.md).**`SentStickerMessage`**

## Constructors

### constructor()

> **new SentStickerMessage**( time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), sticker: [`Sticker`](broken-reference)): [`SentStickerMessage`](class.sentstickermessage.md)

#### Parameters

| Parameter | Type                                             |
| --------- | ------------------------------------------------ |
| time      | `number`                                         |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) |
| client    | [`Client`](class.client.md)                      |
| sticker   | [`Sticker`](broken-reference)                    |

#### Returns

[`SentStickerMessage`](class.sentstickermessage.md)

#### Overrides

[`SentMessage`](class.sentmessage.md).[`constructor`](class.sentmessage.md#constructor)

## Properties

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`channel`](class.sentmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`client`](class.sentmessage.md#client)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdAt`](class.sentmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdTimestamp`](class.sentmessage.md#createdtimestamp)

### sticker

> **sticker**: [`Sticker`](broken-reference)

## Methods

### delete()

> **delete**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>
