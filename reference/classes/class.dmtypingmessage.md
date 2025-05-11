# DMTypingMessage

**`Class`**

A typing message sent in a [DM](class.dm.md)

## Hierarchy

* [`DMMessage`](class.dmmessage.md).**`DMTypingMessage`**

## Constructors

### constructor()

> **new DMTypingMessage**( user: [`User`](class.user.md), action: [`TypingMessageAction`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.TypingMessageAction.md), time: `number`, client: [`Client`](class.client.md)): [`DMTypingMessage`](class.dmtypingmessage.md)

#### Parameters

| Parameter | Type                                                                                                                                        | Description                                   |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| user      | [`User`](class.user.md)                                                                                                                     | The author of the message                     |
| action    | [`TypingMessageAction`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.TypingMessageAction.md) | The action associated with the typing message |
| time      | `number`                                                                                                                                    | The timestamp the message was sent at         |
| client    | [`Client`](class.client.md)                                                                                                                 |                                               |

#### Returns

[`DMTypingMessage`](class.dmtypingmessage.md)

#### Overrides

[`DMMessage`](class.dmmessage.md).[`constructor`](class.dmmessage.md#constructor)

## Properties

### action

> **action**: [`TypingMessageAction`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.TypingMessageAction.md)

Action associated with the typing message

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`author`](class.dmmessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

[DM](class.dm.md) the message was sent to

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`channel`](class.dmmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`client`](class.dmmessage.md#client)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdAt`](class.dmmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdTimestamp`](class.dmmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`ephemeral`](class.dmmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresAt`](class.dmmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresInSeconds`](class.dmmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresTimestamp`](class.dmmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `false`

Whether the message was sent in a group channel or not

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`isGroup`](class.dmmessage.md#isgroup)
