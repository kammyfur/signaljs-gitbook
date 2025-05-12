# DMEditMessage

**`Class`**

An edit message as sent by Signal

## Hierarchy

* [`DMDataMessage`](class.dmdatamessage.md).**`DMEditMessage`**

## Implements

* [`EditMessage`](broken-reference)

## Constructors

### constructor()

> **new DMEditMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, originalTime: `number`, client: [`Client`](broken-reference)): [`DMEditMessage`](class.dmeditmessage.md)

#### Parameters

| Parameter    | Type                         |
| ------------ | ---------------------------- |
| user         | [`User`](class.user.md)      |
| data         | `any`                        |
| time         | `number`                     |
| originalTime | `number`                     |
| client       | [`Client`](broken-reference) |

#### Returns

[`DMEditMessage`](class.dmeditmessage.md)

#### Overrides

[`DMDataMessage`](class.dmdatamessage.md).[`constructor`](class.dmdatamessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](broken-reference)\[] = `[]`

#### Implementation of

[`EditMessage`](broken-reference).[`attachments`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`attachments`](class.dmdatamessage.md#attachments)

### author

> **author**: [`User`](class.user.md)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`author`](class.dmdatamessage.md#author)

### channel

> **channel**: [`DM`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`channel`](class.dmdatamessage.md#channel)

### client

> **client**: [`Client`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`client`](class.dmdatamessage.md#client)

### content

> **content**?: `string`

#### Implementation of

[`EditMessage`](broken-reference).[`content`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`content`](class.dmdatamessage.md#content)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`createdAt`](class.dmdatamessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`createdTimestamp`](class.dmdatamessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`ephemeral`](class.dmdatamessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresAt`](class.dmdatamessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresInSeconds`](class.dmdatamessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresTimestamp`](class.dmdatamessage.md#expirestimestamp)

### formatting

> **formatting**: [`MessageFormatting`](broken-reference)

#### Implementation of

[`EditMessage`](broken-reference).[`formatting`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`formatting`](class.dmdatamessage.md#formatting)

### isGroup

> **isGroup**: `boolean` = `false`

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`isGroup`](class.dmdatamessage.md#isgroup)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

#### Implementation of

[`EditMessage`](broken-reference).[`mentions`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`mentions`](class.dmdatamessage.md#mentions)

### originalCreatedAt

> **originalCreatedAt**: `Date`

#### Implementation of

[`EditMessage`](broken-reference).[`originalCreatedAt`](broken-reference)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

#### Implementation of

[`EditMessage`](broken-reference).[`originalCreatedTimestamp`](broken-reference)

### previews

> **previews**: [`IReceivedMessageURLPreview`](../interfaces/interface.ireceivedmessageurlpreview.md)\[] = `[]`

#### Implementation of

[`EditMessage`](broken-reference).[`previews`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`previews`](class.dmdatamessage.md#previews)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

#### Implementation of

[`EditMessage`](broken-reference).[`quote`](broken-reference)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`quote`](class.dmdatamessage.md#quote)

## Methods

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`markAsRead`](class.dmdatamessage.md#markasread)

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`markAsViewed`](class.dmdatamessage.md#markasviewed)

### reply()

> **reply**(text: `string`, options?: [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md)): `Promise`<[`SentDataMessage`](broken-reference)>

#### Parameters

| Parameter | Type                                                                    |
| --------- | ----------------------------------------------------------------------- |
| text      | `string`                                                                |
| options?  | [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md) |

#### Returns

`Promise`<[`SentDataMessage`](broken-reference)>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`reply`](class.dmdatamessage.md#reply)
