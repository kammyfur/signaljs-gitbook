# UserMention

**`Class`**

A mention of a user in a message

## Constructors

### constructor()

> **new UserMention**( user: [`User`](class.user.md) | \`+${number}\`, start?: `number`, length?: `number`): [`UserMention`](class.usermention.md)

#### Parameters

| Parameter | Type                                      | Description                                                                                                                                                             |
| --------- | ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| user      | [`User`](class.user.md) \| \`+${number}\` | The [User](class.user.md) (or [IUserResolvable](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IUserResolvable.md)) to mention |
| start?    | `number`                                  | Where the mention should start in the message                                                                                                                           |
| length?   | `number`                                  | How long the mention should be in the message                                                                                                                           |

#### Returns

[`UserMention`](class.usermention.md)

## Properties

### length

> **length**?: `number` = `1`

The length of the mention in the message

### number

> **number**: `string`

The user's phone number

### start

> **start**: `number`

The start of the mention in the message

### uuid

> **uuid**?: `string`

The user's UUID

## Methods

### toCLIFormat()

> **toCLIFormat**(): `string`

Convert the mention to a format that can be passed to signal-cli

#### Returns

`string`
