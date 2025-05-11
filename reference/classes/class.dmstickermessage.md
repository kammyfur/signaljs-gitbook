# DMStickerMessage

**`Class`**

A sticker message sent in a [DM](class.dm.md)

## Hierarchy

* [`DMMessage`](class.dmmessage.md).**`DMStickerMessage`**

## Implements

* [`StickerMessage`](class.stickermessage.md)

## Constructors

### constructor()

> **new DMStickerMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, client: [`Client`](class.client.md)): [`DMStickerMessage`](class.dmstickermessage.md)

#### Parameters

| Parameter | Type                        | Description                           |
| --------- | --------------------------- | ------------------------------------- |
| user      | [`User`](class.user.md)     | The author of the message             |
| data      | `any`                       | Data associated with the sticker      |
| time      | `number`                    | The timestamp the message was sent at |
| client    | [`Client`](class.client.md) |                                       |

#### Returns

[`DMStickerMessage`](class.dmstickermessage.md)

#### Overrides

[`DMMessage`](class.dmmessage.md).[`constructor`](class.dmmessage.md#constructor)

## Properties

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`author`](class.dmmessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

[DM](class.dm.md) the message was sent to

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`channel`](class.dmmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`client`](class.dmmessage.md#client)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdAt`](class.dmmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdTimestamp`](class.dmmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`ephemeral`](class.dmmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresAt`](class.dmmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresInSeconds`](class.dmmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresTimestamp`](class.dmmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `false`

Whether the message was sent in a group channel or not

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`isGroup`](class.dmmessage.md#isgroup)

### sticker

> **sticker**: [`Sticker`](class.sticker.md)

Sticker that was sent

#### Implementation of

[`StickerMessage`](class.stickermessage.md).[`sticker`](class.stickermessage.md#sticker)
