# IAttachmentBuilderData

**`Interface`**

Data used by an [AttachmentBuilder](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.AttachmentBuilder.md) to create an [Attachment](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.Attachment.md) from an arbitrary Buffer

## Properties

### data

> **data**: `Buffer`

The Buffer to create the Attachment from

### fileName

> **fileName**?: `string`

An optional file name for the attachment

### type

> **type**?: \`message/${string}\`| \`font/${string}\`| \`audio/${string}\`| \`video/${string}\`| \`image/${string}\`| \`text/${string}\`| \`application/${string}\`| \`multipart/${string}\`| \`example/${string}\`| \`model/${string}\`| \`chemical/${string}\`

Optionally, the file type of the [Attachment](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.Attachment.md)

If this is unset, it will be sent as binary data (application/octet-stream)
