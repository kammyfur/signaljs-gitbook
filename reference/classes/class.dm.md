# DM

**`Class`**

## Hierarchy

* [`Channel`](broken-reference).**`DM`**

## Constructors

### constructor()

> **new DM**( userId: `string`, number: `string`, client: [`Client`](class.client.md)): [`DM`](class.dm.md)

#### Parameters

| Parameter | Type                        |
| --------- | --------------------------- |
| userId    | `string`                    |
| number    | `string`                    |
| client    | [`Client`](class.client.md) |

#### Returns

[`DM`](class.dm.md)

#### Overrides

[`Channel`](broken-reference).[`constructor`](broken-reference)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### group

> **group**: `boolean` = `false`

#### Overrides

[`Channel`](broken-reference).[`group`](broken-reference)

### id

> **id**: `string`

#### Overrides

[`Channel`](broken-reference).[`id`](broken-reference)

### number

> **number**: `string`

## Methods

### send()

> **send**(text: `string`, options?: [`IChatMessageOptions`](broken-reference)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Parameters

| Parameter | Type                                      |
| --------- | ----------------------------------------- |
| text      | `string`                                  |
| options?  | [`IChatMessageOptions`](broken-reference) |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Overrides

[`Channel`](broken-reference).[`send`](broken-reference)

### sendSticker()

> **sendSticker**(sticker: [`Sticker`](broken-reference)): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| sticker   | [`Sticker`](broken-reference) |

#### Returns

`Promise`<`void`>

### setTyping()

> **setTyping**(typing: `boolean`): `Promise`<`void`>

#### Parameters

| Parameter | Type      |
| --------- | --------- |
| typing    | `boolean` |

#### Returns

`Promise`<`void`>

#### Overrides

[`Channel`](broken-reference).[`setTyping`](broken-reference)
