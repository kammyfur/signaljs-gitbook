# MessageFormatting

**`Class`**

A collection of rules to apply formatting styles to a message

## Constructors

### constructor()

> **new MessageFormatting**(plain?: `string`, data?: `any`): [`MessageFormatting`](class.messageformatting.md)

#### Parameters

| Parameter | Type     | Description                    |
| --------- | -------- | ------------------------------ |
| plain?    | `string` | Plain text message             |
| data?     | `any`    | List of Signal-formatted rules |

#### Returns

[`MessageFormatting`](class.messageformatting.md)

## Properties

### rules

> **rules**: [`MessageFormattingRule`](class.messageformattingrule.md)\[]

Array of [MessageFormattingRule](class.messageformattingrule.md)

## Methods

### fromRules()

> `Static` **fromRules**(rules: [`MessageFormattingRule`](class.messageformattingrule.md)\[]): [`MessageFormatting`](class.messageformatting.md)

Convert from a list of formatting rules

#### Parameters

| Parameter | Type                                                         |
| --------- | ------------------------------------------------------------ |
| rules     | [`MessageFormattingRule`](class.messageformattingrule.md)\[] |

#### Returns

[`MessageFormatting`](class.messageformatting.md)
