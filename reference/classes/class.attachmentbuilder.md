# AttachmentBuilder

**`Class`**

A helper to build an attachment to send to a message

## Constructors

### constructor()

> **new AttachmentBuilder**(data: `string` | [`IAttachmentBuilderData`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IAttachmentBuilderData.md)): [`AttachmentBuilder`](class.attachmentbuilder.md)

#### Parameters

| Parameter | Type                                                                                                                                                      | Description                                                 |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| data      | `string` \| [`IAttachmentBuilderData`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IAttachmentBuilderData.md) | A file path, data URI, or object to construct an attachment |

#### Returns

[`AttachmentBuilder`](class.attachmentbuilder.md)

## Properties

### uri

> **uri**: `string`

The rest of the attachment as a URI that can be passed to signal-cli
