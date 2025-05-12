# DataMessage

**`Class`**

A data (text) message sent on Signal

## Hierarchy

* [`EditMessage`](class.editmessage.md)

## Constructors

### constructor()

> **new DataMessage**(): [`DataMessage`](class.datamessage.md)

#### Returns

[`DataMessage`](class.datamessage.md)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

[Attachment](class.attachment.md)s associated with the message

### content

> **content**?: `string`

Message text

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

Mentions in the message

### previews

> **previews**: [`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)\[] = `[]`

URL previews present in the message

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

Quoted message, if applicable
