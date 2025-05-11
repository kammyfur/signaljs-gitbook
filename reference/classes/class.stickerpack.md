# StickerPack

**`Class`**

A Signal sticker pack

## Constructors

### constructor()

> **new StickerPack**(data: `any`, client: [`Client`](class.client.md)): [`StickerPack`](class.stickerpack.md)

#### Parameters

| Parameter | Type                        | Description                   |
| --------- | --------------------------- | ----------------------------- |
| data      | `any`                       | The sticker pack's ID or data |
| client    | [`Client`](class.client.md) |                               |

#### Returns

[`StickerPack`](class.stickerpack.md)

## Properties

### author

> **author**: `string`

Sticker pack author

### cover

> **cover**: [`Sticker`](class.sticker.md)

Sticker used as a cover for this pack

### id

> **id**: `string`

Sticker pack ID

### installed

> **installed**?: `boolean`

Whether the sticker pack is installed or not

### items

> **items**: [`Sticker`](class.sticker.md)\[]

Stickers the pack contents

### title

> **title**: `string`

Sticker pack name

### url

> **url**: `string`

URL to install the sticker pack
