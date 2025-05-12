# DMDeleteMessage

**`Class`**

A deletion message as sent by Signal

## Hierarchy

* [`DMMessage`](broken-reference).**`DMDeleteMessage`**

## Implements

* [`DeleteMessage`](class.deletemessage.md)

## Constructors

### constructor()

> **new DMDeleteMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, client: [`Client`](broken-reference), originalTime: `number`): [`DMDeleteMessage`](class.dmdeletemessage.md)

#### Parameters

| Parameter    | Type                         |
| ------------ | ---------------------------- |
| user         | [`User`](class.user.md)      |
| data         | `any`                        |
| time         | `number`                     |
| client       | [`Client`](broken-reference) |
| originalTime | `number`                     |

#### Returns

[`DMDeleteMessage`](class.dmdeletemessage.md)

#### Overrides

[`DMMessage`](broken-reference).[`constructor`](broken-reference)

## Properties

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

### originalCreatedAt

> **originalCreatedAt**: `Date`

#### Implementation of

[`DeleteMessage`](class.deletemessage.md).[`originalCreatedAt`](class.deletemessage.md#originalcreatedat)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

#### Implementation of

[`DeleteMessage`](class.deletemessage.md).[`originalCreatedTimestamp`](class.deletemessage.md#originalcreatedtimestamp)
