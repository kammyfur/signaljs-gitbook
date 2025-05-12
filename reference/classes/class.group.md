# Group

**`Class`**

## Hierarchy

* [`Channel`](broken-reference).**`Group`**

## Constructors

### constructor()

> **new Group**(groupId: `string`, client: [`Client`](class.client.md)): [`Group`](class.group.md)

#### Parameters

| Parameter | Type                        |
| --------- | --------------------------- |
| groupId   | `string`                    |
| client    | [`Client`](class.client.md) |

#### Returns

[`Group`](class.group.md)

#### Overrides

[`Channel`](broken-reference).[`constructor`](broken-reference)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### group

> **group**: `boolean` = `true`

#### Overrides

[`Channel`](broken-reference).[`group`](broken-reference)

### id

> **id**: `string`

#### Overrides

[`Channel`](broken-reference).[`id`](broken-reference)

## Methods

### addAdmin()

> **addAdmin**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>

### addMember()

> **addMember**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>

### banMember()

> **banMember**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>

### editor()

> **editor**(): `Promise`<[`GroupEditor`](broken-reference)>

#### Returns

`Promise`<[`GroupEditor`](broken-reference)>

### leave()

> **leave**(deleteLocalData: `boolean` = `false`, successorAdmins?: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter        | Type                          | Default value |
| ---------------- | ----------------------------- | ------------- |
| deleteLocalData  | `boolean`                     | false         |
| successorAdmins? | [`User`](broken-reference)\[] | undefined     |

#### Returns

`Promise`<`void`>

### removeAdmin()

> **removeAdmin**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>

### removeMember()

> **removeMember**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>

### send()

> **send**(text: `string`, options?: [`IChatMessageOptions`](broken-reference)): `Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Parameters

| Parameter | Type                                      |
| --------- | ----------------------------------------- |
| text      | `string`                                  |
| options?  | [`IChatMessageOptions`](broken-reference) |

#### Returns

`Promise`<[`SentDataMessage`](class.sentdatamessage.md)>

#### Overrides

[`Channel`](broken-reference).[`send`](broken-reference)

### sendSticker()

> **sendSticker**(sticker: [`Sticker`](broken-reference)): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| sticker   | [`Sticker`](broken-reference) |

#### Returns

`Promise`<`void`>

### setBlocked()

> **setBlocked**(blocked: `boolean`): `Promise`<`void`>

#### Parameters

| Parameter | Type      |
| --------- | --------- |
| blocked   | `boolean` |

#### Returns

`Promise`<`void`>

### setTyping()

> **setTyping**(typing: `boolean`): `Promise`<`void`>

#### Parameters

| Parameter | Type      |
| --------- | --------- |
| typing    | `boolean` |

#### Returns

`Promise`<`void`>

#### Overrides

[`Channel`](broken-reference).[`setTyping`](broken-reference)

### unbanMember()

> **unbanMember**(...users: [`User`](broken-reference)\[]): `Promise`<`void`>

#### Parameters

| Parameter | Type                          |
| --------- | ----------------------------- |
| ...users  | [`User`](broken-reference)\[] |

#### Returns

`Promise`<`void`>
