# IChatMessageOptions

**`Interface`**

Options to be used when sending a message to a channel

## Properties

### attachments

> **attachments**?: [`AttachmentBuilder`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.AttachmentBuilder.md)\[]

All the attachments to be sent with the message, unless they are too large

### formatting

> **formatting**?: [`MessageFormatting`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.MessageFormatting.md)

Formatting options to add to the message

### mentions

> **mentions**?: [`UserMention`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.UserMention.md)\[]

One or more users to mention with this message

Note that the text that was where the mention(s) is/are will be discarded.

### original

> **original**?: `number`

The timestamp of an older message, used only internally and only if the new message is an edit

### preview

> **preview**?: [`ISentMessageURLPreview`](interface.isentmessageurlpreview.md)

A URL preview to add to the message

### quote

> **quote**?: [`QuoteBuilder`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.QuoteBuilder.md)

A quote to add to the message, which should reference an older message (see QuoteBuilder)
