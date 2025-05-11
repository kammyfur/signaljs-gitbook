# ReceivedURLPreview

**`Class`**

A URL preview in a received message

## Constructors

### constructor()

> **new ReceivedURLPreview**(data: `any`): [`ReceivedURLPreview`](class.receivedurlpreview.md)

#### Parameters

| Parameter | Type  | Description                                                               |
| --------- | ----- | ------------------------------------------------------------------------- |
| data      | `any` | Data to reconstruct the [ReceivedURLPreview](class.receivedurlpreview.md) |

#### Returns

[`ReceivedURLPreview`](class.receivedurlpreview.md)

## Properties

### description

> **description**?: `string`

Optional description of the preview

### image

> **image**?: [`Attachment`](class.attachment.md)

Optional [Attachment](class.attachment.md) of the preview's image

### title

> **title**: `string`

Title of the preview

### url

> **url**: `string`

URL for this preview

## Methods

### build()

> **build**(): [`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)

Build a URL preview object

#### Returns

[`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)
