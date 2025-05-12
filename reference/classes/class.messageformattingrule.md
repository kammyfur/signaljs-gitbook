# MessageFormattingRule

**`Class`**

## Constructors

### constructor()

> **new MessageFormattingRule**(data: `any`, text?: `string`): [`MessageFormattingRule`](class.messageformattingrule.md)

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| data      | `any`    |
| text?     | `string` |

#### Returns

[`MessageFormattingRule`](class.messageformattingrule.md)

## Properties

### end

> **end**: `number`

### extract

> **extract**?: `string`

### length

> **length**: `number`

### start

> **start**: `number`

### styling

> **styling**: [`MessageFormattingStyle`](broken-reference)

## Methods

### toCLIFormat()

> **toCLIFormat**(): `string`

#### Returns

`string`

### build()

> `Static` **build**( style: [`MessageFormattingStyle`](broken-reference), start: `number`, length: `number`): [`MessageFormattingRule`](class.messageformattingrule.md)

#### Parameters

| Parameter | Type                                         |
| --------- | -------------------------------------------- |
| style     | [`MessageFormattingStyle`](broken-reference) |
| start     | `number`                                     |
| length    | `number`                                     |

#### Returns

[`MessageFormattingRule`](class.messageformattingrule.md)
