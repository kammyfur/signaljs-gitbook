# DMReactionMessage

**`Class`**

A reaction message sent in a [DM](class.dm.md)

## Hierarchy

* [`DMMessage`](class.dmmessage.md).**`DMReactionMessage`**

## Implements

* [`ReactionMessage`](class.reactionmessage.md)

## Constructors

### constructor()

> **new DMReactionMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, client: [`Client`](class.client.md)): [`DMReactionMessage`](class.dmreactionmessage.md)

#### Parameters

| Parameter | Type                        | Description                           |
| --------- | --------------------------- | ------------------------------------- |
| user      | [`User`](class.user.md)     | The author of the message             |
| data      | `any`                       | Data associated with the reaction     |
| time      | `number`                    | The timestamp the message was sent at |
| client    | [`Client`](class.client.md) |                                       |

#### Returns

[`DMReactionMessage`](class.dmreactionmessage.md)

#### Overrides

[`DMMessage`](class.dmmessage.md).[`constructor`](class.dmmessage.md#constructor)

## Properties

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

### emoji

> **emoji**: [`Emoji`](class.emoji.md)

Emoji that was used for the reaction

#### Implementation of

[`ReactionMessage`](class.reactionmessage.md).[`emoji`](class.reactionmessage.md#emoji)

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

### removed

> **removed**: `boolean`

Whether the reaction is a removal

#### Implementation of

[`ReactionMessage`](class.reactionmessage.md).[`removed`](class.reactionmessage.md#removed)

### target

> **target**: [`ReactionTarget`](class.reactiontarget.md)

Message targetted by the reaction

#### Implementation of

[`ReactionMessage`](class.reactionmessage.md).[`target`](class.reactionmessage.md#target)
