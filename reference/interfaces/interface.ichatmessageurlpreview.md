# IChatMessageURLPreview

**`Interface`**

A URL preview from a message

## Hierarchy

* [`IReceivedMessageURLPreview`](interface.ireceivedmessageurlpreview.md)
* [`ISentMessageURLPreview`](interface.isentmessageurlpreview.md)

## Properties

### description

> **description**?: `string`

An (optional) description of the page the URL points to

### image

> **image**?: `string` | [`Attachment`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.Attachment.md)

An image attached to the URL preview, if any

### title

> **title**: `string`

The title of the page the URL points to

### url

> **url**: `string`

The URL the preview points to

Note that the URL has to be present in the message for the preview to show up
