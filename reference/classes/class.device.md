# Device

**`Class`**

A device associated with the client's Signal account

## Constructors

### constructor()

> **new Device**(data: `any`, client: [`Client`](class.client.md)): [`Device`](class.device.md)

#### Parameters

| Parameter | Type                        | Description                    |
| --------- | --------------------------- | ------------------------------ |
| data      | `any`                       | Data to reconstruct the device |
| client    | [`Client`](class.client.md) |                                |

#### Returns

[`Device`](class.device.md)

## Properties

### client

> `private` **client**: [`Client`](class.client.md)

### createdAt

> **createdAt**: `Date`

Date the device was created (first seen) at

### id

> **id**: `number`

Device ID

### lastSeenAt

> **lastSeenAt**: `Date`

Date the device was last seen at

### name

> **name**?: `string`

Name of the device, if applicable

## Methods

### remove()

> **remove**(): `Promise`<`void`>

Remove this device from the Signal account

#### Returns

`Promise`<`void`>
