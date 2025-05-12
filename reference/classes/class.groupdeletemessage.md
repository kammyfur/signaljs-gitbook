# GroupDeleteMessage

**`Class`**

A deletion message as sent by Signal

## Hierarchy

* [`GroupMessage`](class.groupmessage.md).**`GroupDeleteMessage`**

## Implements

* [`DeleteMessage`](broken-reference)

## Constructors

### constructor()

> **new GroupDeleteMessage**( user: [`User`](broken-reference), data: `any`, time: `number`, groupId: `string`, client: [`Client`](class.client.md), originalTime: `number`): [`GroupDeleteMessage`](class.groupdeletemessage.md)

#### Parameters

| Parameter    | Type                        |
| ------------ | --------------------------- |
| user         | [`User`](broken-reference)  |
| data         | `any`                       |
| time         | `number`                    |
| groupId      | `string`                    |
| client       | [`Client`](class.client.md) |
| originalTime | `number`                    |

#### Returns

[`GroupDeleteMessage`](class.groupdeletemessage.md)

#### Overrides

[`GroupMessage`](class.groupmessage.md).[`constructor`](class.groupmessage.md#constructor)

## Properties

### author

> **author**: [`User`](broken-reference)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`author`](class.groupmessage.md#author)

### channel

> **channel**: [`Group`](class.group.md)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`channel`](class.groupmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`client`](class.groupmessage.md#client)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdAt`](class.groupmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdTimestamp`](class.groupmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`ephemeral`](class.groupmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresAt`](class.groupmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresInSeconds`](class.groupmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresTimestamp`](class.groupmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `true`

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`isGroup`](class.groupmessage.md#isgroup)

### originalCreatedAt

> **originalCreatedAt**: `Date`

#### Implementation of

[`DeleteMessage`](broken-reference).[`originalCreatedAt`](broken-reference)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

#### Implementation of

[`DeleteMessage`](broken-reference).[`originalCreatedTimestamp`](broken-reference)
