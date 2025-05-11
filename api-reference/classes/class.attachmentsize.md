# AttachmentSize

**`Class`**

A size to associate with an Attachment

## Hierarchy

* `Number`.**`AttachmentSize`**

## Constructors

### constructor()

> **new AttachmentSize**(props: `any`): [`AttachmentSize`](class.attachmentsize.md)

#### Parameters

| Parameter | Type  |
| --------- | ----- |
| props     | `any` |

#### Returns

[`AttachmentSize`](class.attachmentsize.md)

#### Overrides

Number.constructor

## Properties

### EPSILON

> `static` `readonly` **EPSILON**: `number`

The value of Number.EPSILON is the difference between 1 and the smallest value greater than 1 that is representable as a Number value, which is approximately: 2.2204460492503130808472633361816 x 10‍−‍16.

#### Inherited from

Number.EPSILON

### MAX\_SAFE\_INTEGER

> `static` `readonly` **MAX\_SAFE\_INTEGER**: `number`

The value of the largest integer n such that n and n + 1 are both exactly representable as a Number value. The value of Number.MAX\_SAFE\_INTEGER is 9007199254740991 2^53 − 1.

#### Inherited from

Number.MAX\_SAFE\_INTEGER

### MAX\_VALUE

> `static` `readonly` **MAX\_VALUE**: `number`

The largest number that can be represented in JavaScript. Equal to approximately 1.79E+308.

#### Inherited from

Number.MAX\_VALUE

### MIN\_SAFE\_INTEGER

> `static` `readonly` **MIN\_SAFE\_INTEGER**: `number`

The value of the smallest integer n such that n and n − 1 are both exactly representable as a Number value. The value of Number.MIN\_SAFE\_INTEGER is −9007199254740991 (−(2^53 − 1)).

#### Inherited from

Number.MIN\_SAFE\_INTEGER

### MIN\_VALUE

> `static` `readonly` **MIN\_VALUE**: `number`

The closest number to zero that can be represented in JavaScript. Equal to approximately 5.00E-324.

#### Inherited from

Number.MIN\_VALUE

### NEGATIVE\_INFINITY

> `static` `readonly` **NEGATIVE\_INFINITY**: `number`

A value that is less than the largest negative number that can be represented in JavaScript. JavaScript displays NEGATIVE\_INFINITY values as -infinity.

#### Inherited from

Number.NEGATIVE\_INFINITY

### NaN

> `static` `readonly` **NaN**: `number`

A value that is not a number. In equality comparisons, NaN does not equal any value, including itself. To test whether a value is equivalent to NaN, use the isNaN function.

#### Inherited from

Number.NaN

### POSITIVE\_INFINITY

> `static` `readonly` **POSITIVE\_INFINITY**: `number`

A value greater than the largest number that can be represented in JavaScript. JavaScript displays POSITIVE\_INFINITY values as infinity.

#### Inherited from

Number.POSITIVE\_INFINITY

## Methods

### toBits()

> **toBits**(): `number`

Convert the size from bytes to bits

#### Returns

`number`

### toExponential()

> **toExponential**(fractionDigits?: `number`): `string`

Returns a string containing a number represented in exponential notation.

#### Parameters

| Parameter       | Type     | Description                                                                       |
| --------------- | -------- | --------------------------------------------------------------------------------- |
| fractionDigits? | `number` | Number of digits after the decimal point. Must be in the range 0 - 20, inclusive. |

#### Returns

`string`

#### Inherited from

Number.toExponential

### toFixed()

> **toFixed**(fractionDigits?: `number`): `string`

Returns a string representing a number in fixed-point notation.

#### Parameters

| Parameter       | Type     | Description                                                                       |
| --------------- | -------- | --------------------------------------------------------------------------------- |
| fractionDigits? | `number` | Number of digits after the decimal point. Must be in the range 0 - 20, inclusive. |

#### Returns

`string`

#### Inherited from

Number.toFixed

### toLocaleString()

> **toLocaleString**(locales?: `string` | `string`\[], options?: `NumberFormatOptions`): `string`

Converts a number to a string by using the current or specified locale.

#### Parameters

| Parameter | Type                    | Description                                                                                                                                                                                                                                                                                                           |
| --------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| locales?  | `string` \| `string`\[] | A locale string or array of locale strings that contain one or more language or locale tags. If you include more than one locale string, list them in descending order of priority so that the first entry is the preferred locale. If you omit this parameter, the default locale of the JavaScript runtime is used. |
| options?  | `NumberFormatOptions`   | An object that contains one or more properties that specify comparison options.                                                                                                                                                                                                                                       |

#### Returns

`string`

#### Inherited from

Number.toLocaleString

> **toLocaleString**(locales?: `LocalesArgument`, options?: `NumberFormatOptions`): `string`

Converts a number to a string by using the current or specified locale.

#### Parameters

| Parameter | Type                  | Description                                                                                                                                                                                                                                                                                                                                                              |
| --------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| locales?  | `LocalesArgument`     | A locale string, array of locale strings, Intl.Locale object, or array of Intl.Locale objects that contain one or more language or locale tags. If you include more than one locale string, list them in descending order of priority so that the first entry is the preferred locale. If you omit this parameter, the default locale of the JavaScript runtime is used. |
| options?  | `NumberFormatOptions` | An object that contains one or more properties that specify comparison options.                                                                                                                                                                                                                                                                                          |

#### Returns

`string`

#### Inherited from

Number.toLocaleString

### toPrecision()

> **toPrecision**(precision?: `number`): `string`

Returns a string containing a number represented either in exponential or fixed-point notation with a specified number of digits.

#### Parameters

| Parameter  | Type     | Description                                                           |
| ---------- | -------- | --------------------------------------------------------------------- |
| precision? | `number` | Number of significant digits. Must be in the range 1 - 21, inclusive. |

#### Returns

`string`

#### Inherited from

Number.toPrecision

### toString()

> **toString**(radix?: `number`): `string`

Returns a string representation of an object.

#### Parameters

| Parameter | Type     | Description                                                                                      |
| --------- | -------- | ------------------------------------------------------------------------------------------------ |
| radix?    | `number` | Specifies a radix for converting numeric values to strings. This value is only used for numbers. |

#### Returns

`string`

#### Inherited from

Number.toString

### valueOf()

> **valueOf**(): `number`

Returns the primitive value of the specified object.

#### Returns

`number`

#### Inherited from

Number.valueOf

### isFinite()

> `Static` **isFinite**(number: `unknown`): `boolean`

Returns true if passed value is finite. Unlike the global isFinite, Number.isFinite doesn't forcibly convert the parameter to a number. Only finite values of the type number, result in true.

#### Parameters

| Parameter | Type      | Description      |
| --------- | --------- | ---------------- |
| number    | `unknown` | A numeric value. |

#### Returns

`boolean`

#### Inherited from

Number.isFinite

### isInteger()

> `Static` **isInteger**(number: `unknown`): `boolean`

Returns true if the value passed is an integer, false otherwise.

#### Parameters

| Parameter | Type      | Description      |
| --------- | --------- | ---------------- |
| number    | `unknown` | A numeric value. |

#### Returns

`boolean`

#### Inherited from

Number.isInteger

### isNaN()

> `Static` **isNaN**(number: `unknown`): `boolean`

Returns a Boolean value that indicates whether a value is the reserved value NaN (not a number). Unlike the global isNaN(), Number.isNaN() doesn't forcefully convert the parameter to a number. Only values of the type number, that are also NaN, result in true.

#### Parameters

| Parameter | Type      | Description      |
| --------- | --------- | ---------------- |
| number    | `unknown` | A numeric value. |

#### Returns

`boolean`

#### Inherited from

Number.isNaN

### isSafeInteger()

> `Static` **isSafeInteger**(number: `unknown`): `boolean`

Returns true if the value passed is a safe integer.

#### Parameters

| Parameter | Type      | Description      |
| --------- | --------- | ---------------- |
| number    | `unknown` | A numeric value. |

#### Returns

`boolean`

#### Inherited from

Number.isSafeInteger

### parseFloat()

> `Static` **parseFloat**(string: `string`): `number`

Converts a string to a floating-point number.

#### Parameters

| Parameter | Type     | Description                                     |
| --------- | -------- | ----------------------------------------------- |
| string    | `string` | A string that contains a floating-point number. |

#### Returns

`number`

#### Inherited from

Number.parseFloat

### parseInt()

> `Static` **parseInt**(string: `string`, radix?: `number`): `number`

Converts A string to an integer.

#### Parameters

| Parameter | Type     | Description                                                                                                                                                                                                                               |
| --------- | -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| string    | `string` | A string to convert into a number.                                                                                                                                                                                                        |
| radix?    | `number` | <p>A value between 2 and 36 that specifies the base of the number in <code>string</code>.<br>If this argument is not supplied, strings with a prefix of '0x' are considered hexadecimal.<br>All other strings are considered decimal.</p> |

#### Returns

`number`

#### Inherited from

Number.parseInt
