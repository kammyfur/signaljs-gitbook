# GroupTypingMessage

**`Class`**

A typing message as sent by Signal

## Hierarchy

* [`GroupMessage`](class.groupmessage.md).**`GroupTypingMessage`**

## Constructors

### constructor()

> **new GroupTypingMessage**( user: [`User`](broken-reference), action: [`TypingMessageAction`](../enumerations/enumeration.typingmessageaction.md), time: `number`, groupId: `string`, client: [`Client`](class.client.md)): [`GroupTypingMessage`](class.grouptypingmessage.md)

#### Parameters

| Parameter | Type                                                                        |
| --------- | --------------------------------------------------------------------------- |
| user      | [`User`](broken-reference)                                                  |
| action    | [`TypingMessageAction`](../enumerations/enumeration.typingmessageaction.md) |
| time      | `number`                                                                    |
| groupId   | `string`                                                                    |
| client    | [`Client`](class.client.md)                                                 |

#### Returns

[`GroupTypingMessage`](class.grouptypingmessage.md)

#### Overrides

[`GroupMessage`](class.groupmessage.md).[`constructor`](class.groupmessage.md#constructor)

## Properties

### action

> **action**: [`TypingMessageAction`](../enumerations/enumeration.typingmessageaction.md)

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
