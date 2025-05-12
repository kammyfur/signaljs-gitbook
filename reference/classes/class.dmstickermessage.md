# DMStickerMessage

**`Class`**

A sticker message as sent by Signal

## Hierarchy

* [`DMMessage`](class.dmmessage.md).**`DMStickerMessage`**

## Implements

* [`StickerMessage`](broken-reference)

## Constructors

### constructor()

> **new DMStickerMessage**( user: [`User`](broken-reference), data: `any`, time: `number`, client: [`Client`](class.client.md)): [`DMStickerMessage`](class.dmstickermessage.md)

#### Parameters

| Parameter | Type                        |
| --------- | --------------------------- |
| user      | [`User`](broken-reference)  |
| data      | `any`                       |
| time      | `number`                    |
| client    | [`Client`](class.client.md) |

#### Returns

[`DMStickerMessage`](class.dmstickermessage.md)

#### Overrides

[`DMMessage`](class.dmmessage.md).[`constructor`](class.dmmessage.md#constructor)

## Properties

### author

> **author**: [`User`](broken-reference)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`author`](class.dmmessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`channel`](class.dmmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`client`](class.dmmessage.md#client)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdAt`](class.dmmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdTimestamp`](class.dmmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`ephemeral`](class.dmmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresAt`](class.dmmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresInSeconds`](class.dmmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresTimestamp`](class.dmmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `false`

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`isGroup`](class.dmmessage.md#isgroup)

### sticker

> **sticker**: [`Sticker`](broken-reference)

#### Implementation of

[`StickerMessage`](broken-reference).[`sticker`](broken-reference)
