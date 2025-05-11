# GroupDeleteMessage

**`Class`**

A deletion message sent in a [Group](class.group.md)

## Hierarchy

* [`GroupMessage`](class.groupmessage.md).**`GroupDeleteMessage`**

## Implements

* [`DeleteMessage`](class.deletemessage.md)

## Constructors

### constructor()

> **new GroupDeleteMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, groupId: `string`, client: [`Client`](class.client.md), originalTime: `number`): [`GroupDeleteMessage`](class.groupdeletemessage.md)

#### Parameters

| Parameter    | Type                        | Description                                    |
| ------------ | --------------------------- | ---------------------------------------------- |
| user         | [`User`](class.user.md)     | The author of the message                      |
| data         | `any`                       | Data associated with the message               |
| time         | `number`                    | The timestamp the message was sent at          |
| groupId      | `string`                    | The group the message was sent in              |
| client       | [`Client`](class.client.md) |                                                |
| originalTime | `number`                    | The timestamp the original message was sent at |

#### Returns

[`GroupDeleteMessage`](class.groupdeletemessage.md)

#### Overrides

[`GroupMessage`](class.groupmessage.md).[`constructor`](class.groupmessage.md#constructor)

## Properties

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`author`](class.groupmessage.md#author)

### channel

> **channel**: [`Group`](class.group.md)

[Group](class.group.md) the message was sent to

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`channel`](class.groupmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`client`](class.groupmessage.md#client)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdAt`](class.groupmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdTimestamp`](class.groupmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`ephemeral`](class.groupmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresAt`](class.groupmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresInSeconds`](class.groupmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresTimestamp`](class.groupmessage.md#expirestimestamp)

### isGroup

> **isGroup**: `boolean` = `true`

Whether the message was sent in a group channel or not

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`isGroup`](class.groupmessage.md#isgroup)

### originalCreatedAt

> **originalCreatedAt**: `Date`

Date at which the original message was created

#### Implementation of

[`DeleteMessage`](class.deletemessage.md).[`originalCreatedAt`](class.deletemessage.md#originalcreatedat)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

Timestamp at which the original message was created

#### Implementation of

[`DeleteMessage`](class.deletemessage.md).[`originalCreatedTimestamp`](class.deletemessage.md#originalcreatedtimestamp)
