# GroupDataMessage

**`Class`**

A data (text) message sent in a [Group](class.group.md)

## Hierarchy

* [`GroupMessage`](class.groupmessage.md).**`GroupDataMessage`**

## Implements

* [`DataMessage`](class.datamessage.md)

## Constructors

### constructor()

> **new GroupDataMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, groupId: `string`, client: `any`): [`GroupDataMessage`](class.groupdatamessage.md)

#### Parameters

| Parameter | Type                    | Description                           |
| --------- | ----------------------- | ------------------------------------- |
| user      | [`User`](class.user.md) | The author of the message             |
| data      | `any`                   | Data associated with the message      |
| time      | `number`                | The timestamp the message was sent at |
| groupId   | `string`                | The group the message was sent in     |
| client    | `any`                   |                                       |

#### Returns

[`GroupDataMessage`](class.groupdatamessage.md)

#### Overrides

[`GroupMessage`](class.groupmessage.md).[`constructor`](class.groupmessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

Attachments associated with the message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`attachments`](class.datamessage.md#attachments)

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`author`](class.groupmessage.md#author)

### channel

> **channel**: [`Group`](class.group.md)

[Group](class.group.md) the message was sent to

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`channel`](class.groupmessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`client`](class.groupmessage.md#client)

### content

> **content**?: `string`

Message text

#### Implementation of

[`DataMessage`](class.datamessage.md).[`content`](class.datamessage.md#content)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdAt`](class.groupmessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`createdTimestamp`](class.groupmessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`ephemeral`](class.groupmessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresAt`](class.groupmessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresInSeconds`](class.groupmessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`expiresTimestamp`](class.groupmessage.md#expirestimestamp)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

#### Implementation of

[`DataMessage`](class.datamessage.md).[`formatting`](class.datamessage.md#formatting)

### isGroup

> **isGroup**: `boolean` = `true`

Whether the message was sent in a group channel or not

#### Inherited from

[`GroupMessage`](class.groupmessage.md).[`isGroup`](class.groupmessage.md#isgroup)

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

### delete()

> **delete**(): `Promise`<`void`>

Delete the message

#### Returns

`Promise`<`void`>

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
