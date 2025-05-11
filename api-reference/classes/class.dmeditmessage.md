# DMEditMessage

**`Class`**

An edit message sent in a [DM](class.dm.md)

## Hierarchy

* [`DMDataMessage`](class.dmdatamessage.md).**`DMEditMessage`**

## Implements

* [`EditMessage`](class.editmessage.md)

## Constructors

### constructor()

> **new DMEditMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, originalTime: `number`, client: [`Client`](class.client.md)): [`DMEditMessage`](class.dmeditmessage.md)

#### Parameters

| Parameter    | Type                        | Description                                    |
| ------------ | --------------------------- | ---------------------------------------------- |
| user         | [`User`](class.user.md)     | The author of the message                      |
| data         | `any`                       | Data associated with the message               |
| time         | `number`                    | The timestamp the message was sent at          |
| originalTime | `number`                    | The timestamp the original message was sent at |
| client       | [`Client`](class.client.md) |                                                |

#### Returns

[`DMEditMessage`](class.dmeditmessage.md)

#### Overrides

[`DMDataMessage`](class.dmdatamessage.md).[`constructor`](class.dmdatamessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

[Attachment](class.attachment.md)s associated with the message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`attachments`](class.editmessage.md#attachments)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`attachments`](class.dmdatamessage.md#attachments)

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`author`](class.dmdatamessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

[DM](class.dm.md) the message was sent to

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`channel`](class.dmdatamessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`client`](class.dmdatamessage.md#client)

### content

> **content**?: `string`

Message text

#### Implementation of

[`EditMessage`](class.editmessage.md).[`content`](class.editmessage.md#content)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`content`](class.dmdatamessage.md#content)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`createdAt`](class.dmdatamessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`createdTimestamp`](class.dmdatamessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`ephemeral`](class.dmdatamessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresAt`](class.dmdatamessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresInSeconds`](class.dmdatamessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`expiresTimestamp`](class.dmdatamessage.md#expirestimestamp)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`formatting`](class.editmessage.md#formatting)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`formatting`](class.dmdatamessage.md#formatting)

### isGroup

> **isGroup**: `boolean` = `false`

Whether the message was sent in a group channel or not

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`isGroup`](class.dmdatamessage.md#isgroup)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

Mentions in the message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`mentions`](class.editmessage.md#mentions)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`mentions`](class.dmdatamessage.md#mentions)

### originalCreatedAt

> **originalCreatedAt**: `Date`

Date at which the original message was created

#### Implementation of

[`EditMessage`](class.editmessage.md).[`originalCreatedAt`](class.editmessage.md#originalcreatedat)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

Timestamp at which the original message was created

#### Implementation of

[`EditMessage`](class.editmessage.md).[`originalCreatedTimestamp`](class.editmessage.md#originalcreatedtimestamp)

### previews

> **previews**: [`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)\[] = `[]`

URL previews present in the message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`previews`](class.editmessage.md#previews)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`previews`](class.dmdatamessage.md#previews)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

Quoted message, if applicable

#### Implementation of

[`EditMessage`](class.editmessage.md).[`quote`](class.editmessage.md#quote)

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`quote`](class.dmdatamessage.md#quote)

## Methods

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

Mark the message as read

#### Returns

`Promise`<`void`>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`markAsRead`](class.dmdatamessage.md#markasread)

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

Mark the message as viewed

#### Returns

`Promise`<`void`>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`markAsViewed`](class.dmdatamessage.md#markasviewed)

### reply()

> **reply**(text: `string`, options?: [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

Reply to (quote) the message

#### Parameters

| Parameter | Type                                                                                                                                    | Description                                 |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| text      | `string`                                                                                                                                | The text of the reply                       |
| options?  | [`IChatMessageOptions`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IChatMessageOptions.md) | The options used to build the reply message |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Inherited from

[`DMDataMessage`](class.dmdatamessage.md).[`reply`](class.dmdatamessage.md#reply)
