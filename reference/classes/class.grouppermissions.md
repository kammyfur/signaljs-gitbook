# GroupPermissions

**`Class`**

Permissions associated with a group

## Constructors

### constructor()

> **new GroupPermissions**( groupData: `any`, editor: [`GroupEditor`](class.groupeditor.md), client: [`Client`](class.client.md)): [`GroupPermissions`](class.grouppermissions.md)

#### Parameters

| Parameter | Type                                  | Description                         |
| --------- | ------------------------------------- | ----------------------------------- |
| groupData | `any`                                 | The data associated with this group |
| editor    | [`GroupEditor`](class.groupeditor.md) | The originating GroupEditor         |
| client    | [`Client`](class.client.md)           |                                     |

#### Returns

[`GroupPermissions`](class.grouppermissions.md)

## Properties

### addMember

> **addMember**: [`GroupPermissionLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionLevel.md)

Current permission level for the "Who can add members" permission

### client

> `private` **client**: [`Client`](class.client.md)

### editDetails

> **editDetails**: [`GroupPermissionLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionLevel.md)

Current permission level for the "Who can edit group info" permission

### editor

> **editor**: [`GroupEditor`](class.groupeditor.md)

Originating [GroupEditor](class.groupeditor.md)

### sendMessage

> **sendMessage**: [`GroupPermissionLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionLevel.md)

Current permission level for the "Who can send messages" permission

## Methods

### change()

> **change**(permission: [`GroupPermissionName`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionName.md), level: [`GroupPermissionLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionLevel.md)): `Promise`<`void`>

Change a permission's level

#### Parameters

| Parameter  | Type                                                                                                                                          | Description          |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| permission | [`GroupPermissionName`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionName.md)   | The permission name  |
| level      | [`GroupPermissionLevel`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/enumerations/enumeration.GroupPermissionLevel.md) | The permission level |

#### Returns

`Promise`<`void`>
