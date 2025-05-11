# EditMessage

**`Class`**

A message editing an older message

## Hierarchy

* [`DataMessage`](class.datamessage.md).**`EditMessage`**

## Constructors

### constructor()

> **new EditMessage**(): [`EditMessage`](class.editmessage.md)

#### Returns

[`EditMessage`](class.editmessage.md)

#### Inherited from

[`DataMessage`](class.datamessage.md).[`constructor`](class.datamessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

[Attachment](class.attachment.md)s associated with the message

#### Inherited from

[`DataMessage`](class.datamessage.md).[`attachments`](class.datamessage.md#attachments)

### content

> **content**?: `string`

Message text

#### Inherited from

[`DataMessage`](class.datamessage.md).[`content`](class.datamessage.md#content)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

#### Inherited from

[`DataMessage`](class.datamessage.md).[`formatting`](class.datamessage.md#formatting)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

Mentions in the message

#### Inherited from

[`DataMessage`](class.datamessage.md).[`mentions`](class.datamessage.md#mentions)

### originalCreatedAt

> **originalCreatedAt**: `Date`

Date at which the original message was created

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

Timestamp at which the original message was created

### previews

> **previews**: [`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)\[] = `[]`

URL previews present in the message

#### Inherited from

[`DataMessage`](class.datamessage.md).[`previews`](class.datamessage.md#previews)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

Quoted message, if applicable

#### Inherited from

[`DataMessage`](class.datamessage.md).[`quote`](class.datamessage.md#quote)
