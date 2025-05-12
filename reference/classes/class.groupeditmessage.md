# GroupEditMessage

**`Class`**

An edit message as sent by Signal

## Hierarchy

* [`GroupDataMessage`](broken-reference).**`GroupEditMessage`**

## Implements

* [`EditMessage`](class.editmessage.md)

## Constructors

### constructor()

> **new GroupEditMessage**( user: [`User`](broken-reference), data: `any`, time: `number`, groupId: `string`, originalTime: `number`, client: [`Client`](class.client.md)): [`GroupEditMessage`](class.groupeditmessage.md)

#### Parameters

| Parameter    | Type                        |
| ------------ | --------------------------- |
| user         | [`User`](broken-reference)  |
| data         | `any`                       |
| time         | `number`                    |
| groupId      | `string`                    |
| originalTime | `number`                    |
| client       | [`Client`](class.client.md) |

#### Returns

[`GroupEditMessage`](class.groupeditmessage.md)

#### Overrides

[`GroupDataMessage`](broken-reference).[`constructor`](broken-reference)

## Properties

### attachments

> **attachments**: [`Attachment`](class.attachment.md)\[] = `[]`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`attachments`](class.editmessage.md#attachments)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`attachments`](broken-reference)

### author

> **author**: [`User`](broken-reference)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`author`](broken-reference)

### channel

> **channel**: [`Group`](class.group.md)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`channel`](broken-reference)

### client

> **client**: [`Client`](class.client.md)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`client`](broken-reference)

### content

> **content**?: `string`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`content`](class.editmessage.md#content)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`content`](broken-reference)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`createdAt`](broken-reference)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`createdTimestamp`](broken-reference)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`ephemeral`](broken-reference)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`expiresAt`](broken-reference)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`expiresInSeconds`](broken-reference)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`expiresTimestamp`](broken-reference)

### formatting

> **formatting**: [`MessageFormatting`](class.messageformatting.md)

#### Implementation of

[`EditMessage`](class.editmessage.md).[`formatting`](class.editmessage.md#formatting)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`formatting`](broken-reference)

### isGroup

> **isGroup**: `boolean` = `true`

#### Inherited from

[`GroupDataMessage`](broken-reference).[`isGroup`](broken-reference)

### mentions

> **mentions**: [`UserMention`](broken-reference)\[] = `[]`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`mentions`](class.editmessage.md#mentions)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`mentions`](broken-reference)

### originalCreatedAt

> **originalCreatedAt**: `Date`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`originalCreatedAt`](class.editmessage.md#originalcreatedat)

### originalCreatedTimestamp

> **originalCreatedTimestamp**: `number`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`originalCreatedTimestamp`](class.editmessage.md#originalcreatedtimestamp)

### previews

> **previews**: [`IReceivedMessageURLPreview`](broken-reference)\[] = `[]`

#### Implementation of

[`EditMessage`](class.editmessage.md).[`previews`](class.editmessage.md#previews)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`previews`](broken-reference)

### quote

> **quote**?: [`QuoteMessage`](broken-reference)

#### Implementation of

[`EditMessage`](class.editmessage.md).[`quote`](class.editmessage.md#quote)

#### Inherited from

[`GroupDataMessage`](broken-reference).[`quote`](broken-reference)

## Methods

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

#### Inherited from

[`GroupDataMessage`](broken-reference).[`markAsRead`](broken-reference)

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

#### Inherited from

[`GroupDataMessage`](broken-reference).[`markAsViewed`](broken-reference)

### reply()

> **reply**(text: `string`, options?: [`IChatMessageOptions`](broken-reference)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Parameters

| Parameter | Type                                      |
| --------- | ----------------------------------------- |
| text      | `string`                                  |
| options?  | [`IChatMessageOptions`](broken-reference) |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Inherited from

[`GroupDataMessage`](broken-reference).[`reply`](broken-reference)
