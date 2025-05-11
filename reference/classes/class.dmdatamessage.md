# DMDataMessage

**`Class`**

A data (text) message sent in a [DM](class.dm.md)

## Hierarchy

* [`DMMessage`](class.dmmessage.md).**`DMDataMessage`**

## Implements

* [`DataMessage`](class.datamessage.md)

## Constructors

### constructor()

> **new DMDataMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, client: [`Client`](class.client.md)): [`DMDataMessage`](class.dmdatamessage.md)

#### Parameters

| Parameter | Type                        | Description                           |
| --------- | --------------------------- | ------------------------------------- |
| user      | [`User`](class.user.md)     | The author of the message             |
| data      | `any`                       | Data associated with the message      |
| time      | `number`                    | The timestamp the message was sent at |
| client    | [`Client`](class.client.md) |                                       |

#### Returns

[`DMDataMessage`](class.dmdatamessage.md)

#### Overrides

[`DMMessage`](class.dmmessage.md).[`constructor`](class.dmmessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

[Attachment](class.attachment.md)s associated with the message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`attachments`](class.datamessage.md#attachments)

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`author`](class.dmmessage.md#author)

### channel

> **channel**: [`DM`](class.dm.md)

[DM](class.dm.md) the message was sent to

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`channel`](class.dmmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`client`](class.dmmessage.md#client)

### content

> **content**?: `string`

Message text

#### Implementation of

[`DataMessage`](class.datamessage.md).[`content`](class.datamessage.md#content)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdAt`](class.dmmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`createdTimestamp`](class.dmmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`ephemeral`](class.dmmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresAt`](class.dmmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresInSeconds`](class.dmmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`expiresTimestamp`](class.dmmessage.md#expirestimestamp)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`formatting`](class.datamessage.md#formatting)

### isGroup

> **isGroup**: `boolean` = `false`

Whether the message was sent in a group channel or not

#### Inherited from

[`DMMessage`](class.dmmessage.md).[`isGroup`](class.dmmessage.md#isgroup)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

Mentions in the message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`mentions`](class.datamessage.md#mentions)

### previews

> **previews**: [`IReceivedMessageURLPreview`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IReceivedMessageURLPreview.md)\[] = `[]`

URL previews present in the message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`previews`](class.datamessage.md#previews)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

Quoted message, if applicable

#### Implementation of

[`DataMessage`](class.datamessage.md).[`quote`](class.datamessage.md#quote)

## Methods

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

Mark the message as read

#### Returns

`Promise`<`void`>

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

Mark the message as viewed

#### Returns

`Promise`<`void`>

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
