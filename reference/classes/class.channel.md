# Channel

**`Class`**

## Hierarchy

* [`DM`](broken-reference)
* [`Group`](broken-reference)

## Constructors

### constructor()

> **new Channel**(): [`Channel`](class.channel.md)

#### Returns

[`Channel`](class.channel.md)

## Properties

### group

> **group**: `boolean`

### id

> **id**: `string`

## Methods

### send()

> **send**(text: `string`, options?: [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md)): `Promise`<[`SentDataMessage`](broken-reference)>

#### Parameters

| Parameter | Type                                                                    |
| --------- | ----------------------------------------------------------------------- |
| text      | `string`                                                                |
| options?  | [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md) |

#### Returns

`Promise`<[`SentDataMessage`](broken-reference)>

### setTyping()

> **setTyping**(typing: `boolean`): `Promise`<`void`>

#### Parameters

| Parameter | Type      |
| --------- | --------- |
| typing    | `boolean` |

#### Returns

`Promise`<`void`>
