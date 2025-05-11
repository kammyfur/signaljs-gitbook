# ReactionTarget

**`Class`**

The target message for a reaction

## Hierarchy

* [`ReceivedMessage`](class.receivedmessage.md).**`ReactionTarget`**

## Constructors

### constructor()

> **new ReactionTarget**( data: `any`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md)): [`ReactionTarget`](class.reactiontarget.md)

#### Parameters

| Parameter | Type                                             | Description                                |
| --------- | ------------------------------------------------ | ------------------------------------------ |
| data      | `any`                                            | The data to reconstruct the target message |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) | The channel the target message is in       |
| client    | [`Client`](class.client.md)                      |                                            |

#### Returns

[`ReactionTarget`](class.reactiontarget.md)

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`constructor`](class.receivedmessage.md#constructor)

## Properties

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`author`](class.receivedmessage.md#author)

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

Channel the message was sent in

#### Inherited from

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

> **isGroup**: `boolean`

Whether the message was sent in a group channel or not

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`isGroup`](class.receivedmessage.md#isgroup)
