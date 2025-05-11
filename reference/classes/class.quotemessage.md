# QuoteMessage

**`Class`**

A message constructed from a quote

## Constructors

### constructor()

> **new QuoteMessage**(quoteData: `any`, client: [`Client`](class.client.md)): [`QuoteMessage`](class.quotemessage.md)

#### Parameters

| Parameter | Type                        | Description                            |
| --------- | --------------------------- | -------------------------------------- |
| quoteData | `any`                       | Data to reconstruct the quoted message |
| client    | [`Client`](class.client.md) |                                        |

#### Returns

[`QuoteMessage`](class.quotemessage.md)

## Properties

### attachments

> **attachments**?: [`Attachment`](class.attachment.md)\[]

Attachments in the quoted message

### author

> **author**: [`User`](class.user.md)

Author of the quoted message

### content

> **content**?: `string`

Text of the quoted message

### createdAt

> **createdAt**: `Date`

Date the quoted message was sent at

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the quoted message was sent at
