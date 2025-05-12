# DMMessage

**`Class`**

A message sent in a [DM](class.dm.md)

## Hierarchy

* [`ReceivedMessage`](class.receivedmessage.md).**`DMMessage`**

## Constructors

### constructor()

> **new DMMessage**( user: [`User`](class.user.md), time: `number`, dm: [`DM`](class.dm.md), client: [`Client`](class.client.md), expirity?: `number`): [`DMMessage`](class.dmmessage.md)

#### Parameters

| Parameter | Type                        | Description                                                                  |
| --------- | --------------------------- | ---------------------------------------------------------------------------- |
| user      | [`User`](class.user.md)     | The author of the message                                                    |
| time      | `number`                    | The timestamp the message was sent at                                        |
| dm        | [`DM`](class.dm.md)         | The DM the message was sent in                                               |
| client    | [`Client`](class.client.md) |                                                                              |
| expirity? | `number`                    | The number of seconds remaining before the message disappears, if applicable |

#### Returns

[`DMMessage`](class.dmmessage.md)

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`constructor`](class.receivedmessage.md#constructor)

## Properties

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`author`](class.receivedmessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

[DM](class.dm.md) the message was sent to

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`channel`](class.receivedmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`client`](class.receivedmessage.md#client)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`createdAt`](class.receivedmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`createdTimestamp`](class.receivedmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`ephemeral`](class.receivedmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresAt`](class.receivedmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresInSeconds`](class.receivedmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresTimestamp`](class.receivedmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `false`

Whether the message was sent in a group channel or not

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`isGroup`](class.receivedmessage.md#isgroup)
