# IReceivedMessageURLPreview

**`Interface`**

A URL preview to be sent in a message

## Hierarchy

* [`IChatMessageURLPreview`](interface.ichatmessageurlpreview.md).**`IReceivedMessageURLPreview`**

## Properties

### description

> **description**?: `string`

An (optional) description of the page the URL points to

#### Inherited from

[`IChatMessageURLPreview`](interface.ichatmessageurlpreview.md).[`description`](interface.ichatmessageurlpreview.md#description)

### image

> **image**?: [`Attachment`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/classes/class.Attachment.md)

The received image attached to the URL preview

#### Overrides

[`IChatMessageURLPreview`](interface.ichatmessageurlpreview.md).[`image`](interface.ichatmessageurlpreview.md#image)

### title

> **title**: `string`

The title of the page the URL points to

#### Inherited from

[`IChatMessageURLPreview`](interface.ichatmessageurlpreview.md).[`title`](interface.ichatmessageurlpreview.md#title)

### url

> **url**: `string`

The URL the preview points to

Note that the URL has to be present in the message for the preview to show up

#### Inherited from

[`IChatMessageURLPreview`](interface.ichatmessageurlpreview.md).[`url`](interface.ichatmessageurlpreview.md#url)
