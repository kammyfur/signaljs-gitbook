# SentMessage

**`Class`**

A message sent to Signal by this client

## Hierarchy

* [`SentDataMessage`](class.sentdatamessage.md)
* [`SentStickerMessage`](class.sentstickermessage.md)

## Constructors

### constructor()

> **new SentMessage**( time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md)): [`SentMessage`](class.sentmessage.md)

#### Parameters

| Parameter | Type                                             | Description                                 |
| --------- | ------------------------------------------------ | ------------------------------------------- |
| time      | `number`                                         | The timestamp at which the sticker was sent |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) | The channel the sticker was sent at         |
| client    | [`Client`](class.client.md)                      |                                             |

#### Returns

[`SentMessage`](class.sentmessage.md)

## Properties

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

Channel in which the message was created

### client

> **client**: [`Client`](class.client.md)

### createdAt

> **createdAt**: `Date`

Date at which the message was created

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp at which the message was created
