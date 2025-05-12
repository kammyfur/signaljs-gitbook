# QuoteBuilder

**`Class`**

## Constructors

### constructor()

> **new QuoteBuilder**( client: [`Client`](broken-reference), timestamp: `number`, number: `string`, text?: `string`): [`QuoteBuilder`](class.quotebuilder.md)

#### Parameters

| Parameter | Type                         |
| --------- | ---------------------------- |
| client    | [`Client`](broken-reference) |
| timestamp | `number`                     |
| number    | `string`                     |
| text?     | `string`                     |

#### Returns

[`QuoteBuilder`](class.quotebuilder.md)

## Properties

### author

> **author**: `string`

### client

> `private` **client**: [`Client`](broken-reference)

### content

> **content**?: `string`

### timestamp

> **timestamp**: `number`

## Methods

### build()

> **build**(): [`QuoteMessage`](class.quotemessage.md)

#### Returns

[`QuoteMessage`](class.quotemessage.md)
