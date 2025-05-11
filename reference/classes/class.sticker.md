# Sticker

**`Class`**

A Signal sticker

## Constructors

### constructor()

> **new Sticker**( source: [`StickerSource`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.StickerSource.md), data: `any`, client: [`Client`](class.client.md), pack?: [`StickerPack`](class.stickerpack.md)): [`Sticker`](class.sticker.md)

#### Parameters

| Parameter | Type                                                                                                                            | Description                     |
| --------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- |
| source    | [`StickerSource`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.StickerSource.md) | The source of this sticker      |
| data      | `any`                                                                                                                           | Data representing the sticker   |
| client    | [`Client`](class.client.md)                                                                                                     |                                 |
| pack?     | [`StickerPack`](class.stickerpack.md)                                                                                           | The pack the sticker is part of |

#### Returns

[`Sticker`](class.sticker.md)

## Properties

### emoji

> **emoji**?: [`Emoji`](class.emoji.md)

[Emoji](class.emoji.md) representing this sticker, if applicable

### id

> **id**: `number`

ID to the sticker relative to the pack

### pack

> **pack**: [`StickerPack`](class.stickerpack.md)

Pack this sticker is part of
