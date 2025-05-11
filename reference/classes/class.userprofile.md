# UserProfile

**`Class`**

A user profile with additional data

## Constructors

### constructor()

> **new UserProfile**(data: `any`, client: [`Client`](class.client.md)): [`UserProfile`](class.userprofile.md)

#### Parameters

| Parameter | Type                        | Description                         |
| --------- | --------------------------- | ----------------------------------- |
| data      | `any`                       | The data to reconstruct the profile |
| client    | [`Client`](class.client.md) |                                     |

#### Returns

[`UserProfile`](class.userprofile.md)

## Properties

### blocked

> **blocked**: `boolean`

Whether this user is blocked or not

### firstName

> **firstName**?: `string`

User's first name

### lastName

> **lastName**?: `string`

User's last name

### lastUpdatedAt

> **lastUpdatedAt**: `Date`

Date the profile was updated for the last time

### mobileCoinAddress

> **mobileCoinAddress**?: `string`

User MobileCoin address

### status

> **status**: [`IUserProfileStatus`](https://github.com/RaindropsSys/signal.js-docs/blob/mane/reference/interfaces/interface.IUserProfileStatus.md)

User status message

### user

> **user**: [`User`](class.user.md)

[User](class.user.md) this profile is associated with

### userName

> **userName**?: `string`

The Signal user name for this user
