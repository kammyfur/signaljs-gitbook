# QuoteBuilder

**`Class`**

A helper class to build a quote to send

## Constructors

### constructor()

> **new QuoteBuilder**( client: [`Client`](class.client.md), timestamp: `number`, number: `string`, text?: `string`): [`QuoteBuilder`](class.quotebuilder.md)

#### Parameters

| Parameter | Type                        | Description                                        |
| --------- | --------------------------- | -------------------------------------------------- |
| client    | [`Client`](class.client.md) |                                                    |
| timestamp | `number`                    | The timestamp at which the quoted message was sent |
| number    | `string`                    | The number of the author of the quoted message     |
| text?     | `string`                    | The text of the quoted message                     |

#### Returns

[`QuoteBuilder`](class.quotebuilder.md)

## Properties

### author

> **author**: `string`

Number of the author of the quoted message

### client

> `private` **client**: [`Client`](class.client.md)

### content

> **content**?: `string`

Text of the quoted message

### timestamp

> **timestamp**: `number`

Timestamp at which the quoted message was sent

## Methods

### build()

> **build**(): [`QuoteMessage`](class.quotemessage.md)

Transform the [QuoteBuilder](class.quotebuilder.md) into a valid [QuoteMessage](class.quotemessage.md)

#### Returns

[`QuoteMessage`](class.quotemessage.md)
