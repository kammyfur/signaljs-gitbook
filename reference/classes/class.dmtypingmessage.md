# DMTypingMessage

**`Class`**

A typing message as sent by Signal

## Hierarchy

* [`DMMessage`](broken-reference).**`DMTypingMessage`**

## Constructors

### constructor()

> **new DMTypingMessage**( user: [`User`](class.user.md), action: [`TypingMessageAction`](broken-reference), time: `number`, client: [`Client`](broken-reference)): [`DMTypingMessage`](class.dmtypingmessage.md)

#### Parameters

| Parameter | Type                                      |
| --------- | ----------------------------------------- |
| user      | [`User`](class.user.md)                   |
| action    | [`TypingMessageAction`](broken-reference) |
| time      | `number`                                  |
| client    | [`Client`](broken-reference)              |

#### Returns

[`DMTypingMessage`](class.dmtypingmessage.md)

#### Overrides

[`DMMessage`](broken-reference).[`constructor`](broken-reference)

## Properties

### action

> **action**: [`TypingMessageAction`](broken-reference)

### author

> **author**: [`User`](class.user.md)

#### Inherited from

[`DMMessage`](broken-reference).[`author`](broken-reference)

### channel

> **channel**: [`DM`](broken-reference)

#### Inherited from

[`DMMessage`](broken-reference).[`channel`](broken-reference)

### client

> **client**: [`Client`](broken-reference)

#### Inherited from

[`DMMessage`](broken-reference).[`client`](broken-reference)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`DMMessage`](broken-reference).[`createdAt`](broken-reference)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`DMMessage`](broken-reference).[`createdTimestamp`](broken-reference)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`DMMessage`](broken-reference).[`ephemeral`](broken-reference)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`DMMessage`](broken-reference).[`expiresAt`](broken-reference)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`DMMessage`](broken-reference).[`expiresInSeconds`](broken-reference)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`DMMessage`](broken-reference).[`expiresTimestamp`](broken-reference)

### isGroup

> **isGroup**: `boolean` = `false`

#### Inherited from

[`DMMessage`](broken-reference).[`isGroup`](broken-reference)
