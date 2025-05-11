# Attachment

**`Class`**

An attachment added to a message

## Constructors

### constructor()

> **new Attachment**(attachmentData: `any`): [`Attachment`](class.attachment.md)

#### Parameters

| Parameter      | Type  | Description                             |
| -------------- | ----- | --------------------------------------- |
| attachmentData | `any` | Data to use to construct the attachment |

#### Returns

[`Attachment`](class.attachment.md)

## Properties

### caption

> **caption**?: `string`

If the attachment is an image, its alternative text

### fileId

> **fileId**: `string`

Attachment file ID set by Signal

### fileName

> **fileName**: `string`

Attachment file name

### height

> **height**?: `number`

If the attachment is an image, its height

### size

> **size**: [`AttachmentSize`](class.attachmentsize.md)

Attachment size

### type

> **type**: \`message/${string}\`| \`font/${string}\`| \`audio/${string}\`| \`video/${string}\`| \`image/${string}\`| \`text/${string}\`| \`application/${string}\`| \`multipart/${string}\`| \`example/${string}\`| \`model/${string}\`| \`chemical/${string}\`

Attachment MIME type

### width

> **width**?: `number`

If the attachment is an image, its width
