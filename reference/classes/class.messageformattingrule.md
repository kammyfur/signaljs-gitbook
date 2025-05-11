# MessageFormattingRule

**`Class`**

A rule used to apply formatting styles to a message

## Constructors

### constructor()

> **new MessageFormattingRule**(data: `any`, text?: `string`): [`MessageFormattingRule`](class.messageformattingrule.md)

#### Parameters

| Parameter | Type     | Description                             |
| --------- | -------- | --------------------------------------- |
| data      | `any`    | Data to reconstruct the formatting rule |
| text?     | `string` | Non-formatted message text              |

#### Returns

[`MessageFormattingRule`](class.messageformattingrule.md)

## Properties

### end

> **end**: `number`

Ending position of the rule

### extract

> **extract**?: `string`

Chunk of text covered by this rule

### length

> **length**: `number`

Length of the rule

### start

> **start**: `number`

Starting position of the rule

### styling

> **styling**: [`MessageFormattingStyle`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.MessageFormattingStyle.md)

Style the rule has to apply

## Methods

### toCLIFormat()

> **toCLIFormat**(): `string`

Convert the formatting rule to a format that can be passed to signal-cli

#### Returns

`string`

### build()

> `Static` **build**( style: [`MessageFormattingStyle`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.MessageFormattingStyle.md), start: `number`, length: `number`): [`MessageFormattingRule`](class.messageformattingrule.md)

Build a formatting rule

#### Parameters

| Parameter | Type                                                                                                                                              | Description            |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| style     | [`MessageFormattingStyle`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.MessageFormattingStyle.md) | The style to apply     |
| start     | `number`                                                                                                                                          | The start position     |
| length    | `number`                                                                                                                                          | The length of the rule |

#### Returns

[`MessageFormattingRule`](class.messageformattingrule.md)
