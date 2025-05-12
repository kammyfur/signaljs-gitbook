# GroupDataMessage

**`Class`**

A data message as sent by Signal

## Hierarchy

* [`GroupMessage`](broken-reference).**`GroupDataMessage`**

## Implements

* [`DataMessage`](broken-reference)

## Constructors

### constructor()

> **new GroupDataMessage**( user: [`User`](class.user.md), data: `any`, time: `number`, groupId: `string`, client: `any`): [`GroupDataMessage`](class.groupdatamessage.md)

#### Parameters

| Parameter | Type                    |
| --------- | ----------------------- |
| user      | [`User`](class.user.md) |
| data      | `any`                   |
| time      | `number`                |
| groupId   | `string`                |
| client    | `any`                   |

#### Returns

[`GroupDataMessage`](class.groupdatamessage.md)

#### Overrides

[`GroupMessage`](broken-reference).[`constructor`](broken-reference)

## Properties

### attachments

> **attachments**: [`Attachment`](broken-reference)\[] = `[]`

#### Implementation of

[`DataMessage`](broken-reference).[`attachments`](broken-reference)

### author

> **author**: [`User`](class.user.md)

#### Inherited from

[`GroupMessage`](broken-reference).[`author`](broken-reference)

### channel

> **channel**: [`Group`](broken-reference)

#### Inherited from

[`GroupMessage`](broken-reference).[`channel`](broken-reference)

### client

> **client**: [`Client`](broken-reference)

#### Inherited from

[`GroupMessage`](broken-reference).[`client`](broken-reference)

### content

> **content**?: `string`

#### Implementation of

[`DataMessage`](broken-reference).[`content`](broken-reference)

### createdAt

> **createdAt**: `Date`

#### Inherited from

[`GroupMessage`](broken-reference).[`createdAt`](broken-reference)

### createdTimestamp

> **createdTimestamp**: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`createdTimestamp`](broken-reference)

### ephemeral

> **ephemeral**: `boolean` = `false`

#### Inherited from

[`GroupMessage`](broken-reference).[`ephemeral`](broken-reference)

### expiresAt

> **expiresAt**?: `Date`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresAt`](broken-reference)

### expiresInSeconds

> **expiresInSeconds**?: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresInSeconds`](broken-reference)

### expiresTimestamp

> **expiresTimestamp**?: `number`

#### Inherited from

[`GroupMessage`](broken-reference).[`expiresTimestamp`](broken-reference)

### formatting

> **formatting**: [`MessageFormatting`](broken-reference)

#### Implementation of

[`DataMessage`](broken-reference).[`formatting`](broken-reference)

### isGroup

> **isGroup**: `boolean` = `true`

#### Inherited from

[`GroupMessage`](broken-reference).[`isGroup`](broken-reference)

### mentions

> **mentions**: [`UserMention`](class.usermention.md)\[] = `[]`

#### Implementation of

[`DataMessage`](broken-reference).[`mentions`](broken-reference)

### previews

> **previews**: [`IReceivedMessageURLPreview`](../interfaces/interface.ireceivedmessageurlpreview.md)\[] = `[]`

#### Implementation of

[`DataMessage`](broken-reference).[`previews`](broken-reference)

### quote

> **quote**?: [`QuoteMessage`](class.quotemessage.md)

#### Implementation of

[`DataMessage`](broken-reference).[`quote`](broken-reference)

## Methods

### markAsRead()

> **markAsRead**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

### markAsViewed()

> **markAsViewed**(): `Promise`<`void`>

#### Returns

`Promise`<`void`>

### reply()

> **reply**(text: `string`, options?: [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md)): `Promise`<[`SentDataMessage`](broken-reference)>

#### Parameters

| Parameter | Type                                                                    |
| --------- | ----------------------------------------------------------------------- |
| text      | `string`                                                                |
| options?  | [`IChatMessageOptions`](../interfaces/interface.ichatmessageoptions.md) |

#### Returns

`Promise`<[`SentDataMessage`](broken-reference)>
