# Identity

**`Class`**

## Constructors

### constructor()

> **new Identity**(data: `any`, client: [`Client`](class.client.md)): [`Identity`](class.identity.md)

#### Parameters

| Parameter | Type                        | Description                             |
| --------- | --------------------------- | --------------------------------------- |
| data      | `any`                       | The data used to construct the identity |
| client    | [`Client`](class.client.md) |                                         |

#### Returns

[`Identity`](class.identity.md)

## Properties

### addedAt

> **addedAt**: `Date`

Date at which the identity was first seen

### fingerprint

> **fingerprint**: `string`

Fingerprint of the key used by this identity

### safetyNumber

> **safetyNumber**: `string`

Safety number for this identity

### safetyNumberScannable

> **safetyNumberScannable**: `string`

Version of the safety number that can be converted to a QR code

### trusted

> **trusted**: `boolean`

Whether the identity is trusted (verified) or not

### user

> **user**: [`User`](class.user.md)

[User](class.user.md) this identity corresponds to
