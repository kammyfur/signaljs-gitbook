# GroupEditMessage

**`Class`**

An edit message sent in a [Group](class.group.md)

## Hierarchy

* [`GroupDataMessage`](class.groupdatamessage.md).**`GroupEditMessage`**

## Implements

* [`EditMessage`](class.editmessage.md)

## Constructors

### constructor()

> **new GroupEditMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, groupId: `string`, originalTime: `number`, client: [`Client`](class.client.md)): [`GroupEditMessage`](class.groupeditmessage.md)

#### Parameters

| Parameter    | Type                        | Description                                    |
| ------------ | --------------------------- | ---------------------------------------------- |
| user         | [`User`](class.user.md)     | The author of the message                      |
| data         | `any`                       | Data associated with the message               |
| time         | `number`                    | The timestamp the message was sent at          |
| groupId      | `string`                    | The group the message was sent in              |
| originalTime | `number`                    | The timestamp the original message was sent at |
| client       | [`Client`](class.client.md) |                                                |

#### Returns

[`GroupEditMessage`](class.groupeditmessage.md)

#### Overrides

[`GroupDataMessage`](class.groupdatamessage.md).[`constructor`](class.groupdatamessage.md#constructor)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

Attachments associated with the message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`attachments`](class.editmessage.md#attachments)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`attachments`](class.groupdatamessage.md#attachments)

### author

> **author**: [`User`](class.user.md)

Author of the message

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`author`](class.groupdatamessage.md#author)

### channel

> **channel**: [`Group`](class.group.md)

[Group](class.group.md) the message was sent to

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`channel`](class.groupdatamessage.md#channel)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`client`](class.groupdatamessage.md#client)

### content

> **content**?: `string`

Message text

#### Implementation of

[`EditMessage`](class.editmessage.md).[`content`](class.editmessage.md#content)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`content`](class.groupdatamessage.md#content)

### createdAt

> **createdAt**: `Date`

Date the message was sent at

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`createdAt`](class.groupdatamessage.md#createdat)

### createdTimestamp

> **createdTimestamp**: `number`

Timestamp the message was sent at

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`createdTimestamp`](class.groupdatamessage.md#createdtimestamp)

### ephemeral

> **ephemeral**: `boolean` = `false`

Whether the message will disappear automatically or not (disappearing messages)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`ephemeral`](class.groupdatamessage.md#ephemeral)

### expiresAt

> **expiresAt**?: `Date`

Date at which the message will disappear, if applicable

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`expiresAt`](class.groupdatamessage.md#expiresat)

### expiresInSeconds

> **expiresInSeconds**?: `number`

Number of seconds remaining before the message disappears, if applicable

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`expiresInSeconds`](class.groupdatamessage.md#expiresinseconds)

### expiresTimestamp

> **expiresTimestamp**?: `number`

Timestamp at which the message will disappear, if applicable

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`expiresTimestamp`](class.groupdatamessage.md#expirestimestamp)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

Formatting rules collection for this message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`formatting`](class.editmessage.md#formatting)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`formatting`](class.groupdatamessage.md#formatting)

### isGroup

> **isGroup**: `boolean` = `true`

Whether the message was sent in a group channel or not

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`isGroup`](class.groupdatamessage.md#isgroup)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

Mentions in the message

#### Implementation of

[`EditMessage`](class.editmessage.md).[`mentions`](class.editmessage.md#mentions)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`mentions`](class.groupdatamessage.md#mentions)

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

[`GroupDataMessage`](class.groupdatamessage.md).[`previews`](class.groupdatamessage.md#previews)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

Quoted message, if applicable

#### Implementation of

[`EditMessage`](class.editmessage.md).[`quote`](class.editmessage.md#quote)

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`quote`](class.groupdatamessage.md#quote)

## Methods

### delete()

> **delete**(): `Promise`<`void`>

Delete the message

#### Returns

`Promise`<`void`>

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`delete`](class.groupdatamessage.md#delete)

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

Mark the message as read

#### Returns

`Promise`<`void`>

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`markAsRead`](class.groupdatamessage.md#markasread)

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

Mark the message as viewed

#### Returns

`Promise`<`void`>

#### Inherited from

[`GroupDataMessage`](class.groupdatamessage.md).[`markAsViewed`](class.groupdatamessage.md#markasviewed)

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

[`GroupDataMessage`](class.groupdatamessage.md).[`reply`](class.groupdatamessage.md#reply)
