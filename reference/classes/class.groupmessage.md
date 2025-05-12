# GroupMessage

**`Class`**

## Hierarchy

* [`ReceivedMessage`](class.receivedmessage.md).**`GroupMessage`**

## Constructors

### constructor()

> **new GroupMessage**( user: [`User`](broken-reference), time: `number`, group: [`Group`](class.group.md), client: [`Client`](class.client.md), expirity?: `number`): [`GroupMessage`](class.groupmessage.md)

#### Parameters

| Parameter | Type                        |
| --------- | --------------------------- |
| user      | [`User`](broken-reference)  |
| time      | `number`                    |
| group     | [`Group`](class.group.md)   |
| client    | [`Client`](class.client.md) |
| expirity? | `number`                    |

#### Returns

[`GroupMessage`](class.groupmessage.md)

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`constructor`](class.receivedmessage.md#constructor)

## Properties

### author

> **author**: [`User`](broken-reference)

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`author`](class.receivedmessage.md#author)

### channel

> **channel**: [`Group`](class.group.md)

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`channel`](class.receivedmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`client`](class.receivedmessage.md#client)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`createdAt`](class.receivedmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`createdTimestamp`](class.receivedmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`ephemeral`](class.receivedmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresAt`](class.receivedmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresInSeconds`](class.receivedmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`ReceivedMessage`](class.receivedmessage.md).[`expiresTimestamp`](class.receivedmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `true`

#### Overrides

[`ReceivedMessage`](class.receivedmessage.md).[`isGroup`](class.receivedmessage.md#isgroup)
