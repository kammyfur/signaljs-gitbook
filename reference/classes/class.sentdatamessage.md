# SentDataMessage

**`Class`**

## Hierarchy

* [`SentMessage`](class.sentmessage.md).**`SentDataMessage`**

## Constructors

### constructor()

> **new SentDataMessage**( time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), content: `string`, options?: [`IChatMessageOptions`](broken-reference)): [`SentDataMessage`](class.sentdatamessage.md)

#### Parameters

| Parameter | Type                                             |
| --------- | ------------------------------------------------ |
| time      | `number`                                         |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) |
| client    | [`Client`](class.client.md)                      |
| content   | `string`                                         |
| options?  | [`IChatMessageOptions`](broken-reference)        |

#### Returns

[`SentDataMessage`](class.sentdatamessage.md)

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

### content

> **content**: `string`

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdAt`](class.sentmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`SentMessage`](class.sentmessage.md).[`createdTimestamp`](class.sentmessage.md#createdtimestamp)

### options

> **options**?: [`IChatMessageOptions`](broken-reference)

## Methods

### delete()

> **delete**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

### edit()

> **edit**(text: `string`, options?: [`IChatMessageOptions`](broken-reference)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Parameters

| Parameter | Type                                      |
| --------- | ----------------------------------------- |
| text      | `string`                                  |
| options?  | [`IChatMessageOptions`](broken-reference) |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>
