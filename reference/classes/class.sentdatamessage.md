# SentDataMessage

**`Class`**

A text message sent to Signal

## Hierarchy

* [`SentMessage`](class.sentmessage.md).**`SentDataMessage`**

## Constructors

### constructor()

> **new SentDataMessage**( time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), content: `string`, options?: [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md)): [`SentDataMessage`](class.sentdatamessage.md)

#### Parameters

| Parameter | Type                                                                                                                                    | Description                                 |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| time      | `number`                                                                                                                                | The timestamp at which the message was sent |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md)                                                                                        | The channel the message was sent in         |
| client    | [`Client`](class.client.md)                                                                                                             |                                             |
| content   | `string`                                                                                                                                | The text of the message                     |
| options?  | [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md) | The options used to build the message       |

#### Returns

[`SentDataMessage`](class.sentdatamessage.md)

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

### content

> **content**: `string`

Text of the message

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

### options

> **options**?: [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md)

Options used to build the message

## Methods

### delete()

> **delete**(): `Promise`<`void`>

Delete the message

#### Returns

`Promise`<`void`>

### edit()

> **edit**(text: `string`, options?: [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

Edit the message

#### Parameters

| Parameter | Type                                                                                                                                    | Description                               |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| text      | `string`                                                                                                                                | The new text of the message               |
| options?  | [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md) | The new options used to build the message |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>
