# ReceivedMessage

**`Class`**

## Hierarchy

* [`DMMessage`](class.dmmessage.md)
* [`GroupMessage`](class.groupmessage.md)
* [`ReactionTarget`](class.reactiontarget.md)

## Constructors

### constructor()

> **new ReceivedMessage**( user: [`User`](broken-reference), time: `number`, channel: [`Group`](class.group.md) | [`DM`](class.dm.md), client: [`Client`](class.client.md), expirity?: `number`): [`ReceivedMessage`](class.receivedmessage.md)

#### Parameters

| Parameter | Type                                             |
| --------- | ------------------------------------------------ |
| user      | [`User`](broken-reference)                       |
| time      | `number`                                         |
| channel   | [`Group`](class.group.md) \| [`DM`](class.dm.md) |
| client    | [`Client`](class.client.md)                      |
| expirity? | `number`                                         |

#### Returns

[`ReceivedMessage`](class.receivedmessage.md)

## Properties

### author

> **author**: [`User`](broken-reference)

### channel

> **channel**: [`Group`](class.group.md) | [`DM`](class.dm.md)

### client

> **client**: [`Client`](class.client.md)

### createdAt

> **createdAt**: `Date`

### createdTimestamp

> **createdTimestamp**: `number`

### ephemeral

> **ephemeral**: `boolean` = `false`

### expiresAt

> **expiresAt**?: `Date`

### expiresInSeconds

> **expiresInSeconds**?: `number`

### expiresTimestamp

> **expiresTimestamp**?: `number`

### isGroup

> **isGroup**: `boolean`
