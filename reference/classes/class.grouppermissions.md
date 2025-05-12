# GroupPermissions

**`Class`**

## Constructors

### constructor()

> **new GroupPermissions**( groupData: `any`, editor: [`GroupEditor`](broken-reference), client: [`Client`](class.client.md)): [`GroupPermissions`](class.grouppermissions.md)

#### Parameters

| Parameter | Type                              |
| --------- | --------------------------------- |
| groupData | `any`                             |
| editor    | [`GroupEditor`](broken-reference) |
| client    | [`Client`](class.client.md)       |

#### Returns

[`GroupPermissions`](class.grouppermissions.md)

## Properties

### addMember

> **addMember**: [`GroupPermissionLevel`](../enumerations/enumeration.grouppermissionlevel.md)

### client

> `private` **client**: [`Client`](class.client.md)

### editDetails

> **editDetails**: [`GroupPermissionLevel`](../enumerations/enumeration.grouppermissionlevel.md)

### editor

> **editor**: [`GroupEditor`](broken-reference)

### sendMessage

> **sendMessage**: [`GroupPermissionLevel`](../enumerations/enumeration.grouppermissionlevel.md)

## Methods

### change()

> **change**(permission: [`GroupPermissionName`](../enumerations/enumeration.grouppermissionname.md), level: [`GroupPermissionLevel`](../enumerations/enumeration.grouppermissionlevel.md)): `Promise`<`void`>

#### Parameters

| Parameter  | Type                                                                          |
| ---------- | ----------------------------------------------------------------------------- |
| permission | [`GroupPermissionName`](../enumerations/enumeration.grouppermissionname.md)   |
| level      | [`GroupPermissionLevel`](../enumerations/enumeration.grouppermissionlevel.md) |

#### Returns

`Promise`<`void`>
