# GroupStickerMessage

**`Class`**

A sticker message as sent by Signal

## Hierarchy

* [`GroupMessage`](broken-reference).**`GroupStickerMessage`**

## Implements

* [`StickerMessage`](class.stickermessage.md)

## Constructors

### constructor()

> **new GroupStickerMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, groupId: `string`, client: [`Client`](broken-reference)): [`GroupStickerMessage`](class.groupstickermessage.md)

#### Parameters

| Parameter | Type                         |
| --------- | ---------------------------- |
| user      | [`User`](class.user.md)      |
| data      | `any`                        |
| time      | `number`                     |
| groupId   | `string`                     |
| client    | [`Client`](broken-reference) |

#### Returns

[`GroupStickerMessage`](class.groupstickermessage.md)

#### Overrides

[`GroupMessage`](broken-reference).[`constructor`](broken-reference)

## Properties

### author

> **author**: [`User`](class.user.md)

#### Inherited from

[`GroupMessage`](broken-reference).[`author`](broken-reference)

### channel

> **channel**: [`Group`](broken-reference)

#### Inherited from

[`GroupMessage`](broken-reference).[`channel`](broken-reference)

### client

> **client**: [`Client`](broken-reference)

#### Inherited from

[`GroupMessage`](broken-reference).[`client`](broken-reference)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`GroupMessage`](broken-reference).[`createdAt`](broken-reference)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`createdTimestamp`](broken-reference)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`GroupMessage`](broken-reference).[`ephemeral`](broken-reference)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresAt`](broken-reference)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresInSeconds`](broken-reference)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresTimestamp`](broken-reference)

### isGroup

> **isGroup**: `boolean` = `true`

#### Inherited from

[`GroupMessage`](broken-reference).[`isGroup`](broken-reference)

### sticker

> **sticker**: [`Sticker`](class.sticker.md)

#### Implementation of

[`StickerMessage`](class.stickermessage.md).[`sticker`](class.stickermessage.md#sticker)
