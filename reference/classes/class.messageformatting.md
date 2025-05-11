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

### fromMarkdown()

> `Static` **fromMarkdown**(text: `string`): [`MessageFormatting`](class.messageformatting.md)

Transform a Markdown-formatted text into a [MessageFormatting](class.messageformatting.md), converting the compatible formatting options.

#### Parameters

| Parameter | Type     | Description     |
| --------- | -------- | --------------- |
| text      | `string` | The text to use |

#### Returns

[`MessageFormatting`](class.messageformatting.md)

### fromRules()

> `Static` **fromRules**(rules: [`MessageFormattingRule`](class.messageformattingrule.md)\[]): [`MessageFormatting`](class.messageformatting.md)

Convert from a list of formatting rules

#### Parameters

| Parameter | Type                                                         |
| --------- | ------------------------------------------------------------ |
| rules     | [`MessageFormattingRule`](class.messageformattingrule.md)\[] |

#### Returns

[`MessageFormatting`](class.messageformatting.md)

### plainFromMarkdown()

> `Static` **plainFromMarkdown**(text: `string`): `string`

Transform a Markdown-formatted text into a plain text string that can be easily displayed.

#### Parameters

| Parameter | Type     | Description     |
| --------- | -------- | --------------- |
| text      | `string` | The text to use |

#### Returns

`string`
