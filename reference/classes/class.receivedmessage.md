# ReceivedMessage

**`Class`**

A message received from Signal

## Hierarchy

* [`DMMessage`](class.dmmessage.md)
* [`GroupMessage`](class.groupmessage.md)
* [`ReactionTarget`](class.reactiontarget.md)

## Constructors

### constructor()

> **new ReceivedMessage**( user: [`User`](class.user.md), time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), expirity?: `number`): [`ReceivedMessage`](class.receivedmessage.md)

#### Parameters

| Parameter | Type                                             | Description                                                                  |
| --------- | ------------------------------------------------ | ---------------------------------------------------------------------------- |
| user      | [`User`](class.user.md)                          | The author of the message                                                    |
| time      | `number`                                         | The timestamp the message was sent at                                        |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) | The channel the message was sent it                                          |
| client    | [`Client`](class.client.md)                      |                                                                              |
| expirity? | `number`                                         | The number of seconds remaining before the message disappears, if applicable |

#### Returns

[`ReceivedMessage`](class.receivedmessage.md)

## Properties

### author

> **author**: [`User`](class.user.md)

Author of the message

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

Channel the message was sent in

### client

> **client**: [`Client`](class.client.md)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

### isGroup

> **isGroup**: `boolean`

Whether the message was sent in a group channel or not
