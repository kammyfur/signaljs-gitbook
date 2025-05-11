# ObjectCache

**`Class`**

A cache for data to be used later

## Hierarchy

* `Object`.**`ObjectCache`**

## Constructors

### constructor()

> **new ObjectCache**(props: `any`): [`ObjectCache`](class.objectcache.md)

#### Parameters

| Parameter | Type  |
| --------- | ----- |
| props     | `any` |

#### Returns

[`ObjectCache`](class.objectcache.md)

#### Overrides

Object.constructor

## Properties

### constructor

> **constructor**: `Function`

The initial value of Object.prototype.constructor is the standard built-in Object constructor.

#### Inherited from

Object.constructor

## Methods

### hasOwnProperty()

> **hasOwnProperty**(v: `PropertyKey`): `boolean`

Determines whether an object has a property with the specified name.

#### Parameters

| Parameter | Type          | Description      |
| --------- | ------------- | ---------------- |
| v         | `PropertyKey` | A property name. |

#### Returns

`boolean`

#### Inherited from

Object.hasOwnProperty

### isPrototypeOf()

> **isPrototypeOf**(v: `Object`): `boolean`

Determines whether an object exists in another object's prototype chain.

#### Parameters

| Parameter | Type     | Description                                            |
| --------- | -------- | ------------------------------------------------------ |
| v         | `Object` | Another object whose prototype chain is to be checked. |

#### Returns

`boolean`

#### Inherited from

Object.isPrototypeOf

### propertyIsEnumerable()

> **propertyIsEnumerable**(v: `PropertyKey`): `boolean`

Determines whether a specified property is enumerable.

#### Parameters

| Parameter | Type          | Description      |
| --------- | ------------- | ---------------- |
| v         | `PropertyKey` | A property name. |

#### Returns

`boolean`

#### Inherited from

Object.propertyIsEnumerable

### toLocaleString()

> **toLocaleString**(): `string`

Returns a date converted to a string using the current locale.

#### Returns

`string`

#### Inherited from

Object.toLocaleString

### toString()

> **toString**(): `string`

Returns a string representation of an object.

#### Returns

`string`

#### Inherited from

Object.toString

### valueOf()

> **valueOf**(): `Object`

Returns the primitive value of the specified object.

#### Returns

`Object`

#### Inherited from

Object.valueOf

### assign()

> `Static` **assign**\<T, U>(target: `T`, source: `U`): `T` & `U`

Copy the values of all of the enumerable own properties from one or more source objects to a target object. Returns the target object.

#### Type parameters

| Parameter      |
| -------------- |
| T _extends_ {} |
| U              |

#### Parameters

| Parameter | Type | Description                                      |
| --------- | ---- | ------------------------------------------------ |
| target    | `T`  | The target object to copy to.                    |
| source    | `U`  | The source object from which to copy properties. |

#### Returns

`T` & `U`

#### Inherited from

Object.assign

> `Static` **assign**\<T, U, V>( target: `T`, source1: `U`, source2: `V`): `T` & `U` & `V`

Copy the values of all of the enumerable own properties from one or more source objects to a target object. Returns the target object.

#### Type parameters

| Parameter      |
| -------------- |
| T _extends_ {} |
| U              |
| V              |

#### Parameters

| Parameter | Type | Description                                             |
| --------- | ---- | ------------------------------------------------------- |
| target    | `T`  | The target object to copy to.                           |
| source1   | `U`  | The first source object from which to copy properties.  |
| source2   | `V`  | The second source object from which to copy properties. |

#### Returns

`T` & `U` & `V`

#### Inherited from

Object.assign

> `Static` **assign**\<T, U, V, W>( target: `T`, source1: `U`, source2: `V`, source3: `W`): `T` & `U` & `V` & `W`

Copy the values of all of the enumerable own properties from one or more source objects to a target object. Returns the target object.

#### Type parameters

| Parameter      |
| -------------- |
| T _extends_ {} |
| U              |
| V              |
| W              |

#### Parameters

| Parameter | Type | Description                                             |
| --------- | ---- | ------------------------------------------------------- |
| target    | `T`  | The target object to copy to.                           |
| source1   | `U`  | The first source object from which to copy properties.  |
| source2   | `V`  | The second source object from which to copy properties. |
| source3   | `W`  | The third source object from which to copy properties.  |

#### Returns

`T` & `U` & `V` & `W`

#### Inherited from

Object.assign

> `Static` **assign**(target: `object`, ...sources: `any`\[]): `any`

Copy the values of all of the enumerable own properties from one or more source objects to a target object. Returns the target object.

#### Parameters

| Parameter  | Type     | Description                                              |
| ---------- | -------- | -------------------------------------------------------- |
| target     | `object` | The target object to copy to.                            |
| ...sources | `any`\[] | One or more source objects from which to copy properties |

#### Returns

`any`

#### Inherited from

Object.assign

### create()

> `Static` **create**(o: `object`): `any`

Creates an object that has the specified prototype or that has null prototype.

#### Parameters

| Parameter | Type     | Description                                |
| --------- | -------- | ------------------------------------------ |
| o         | `object` | Object to use as a prototype. May be null. |

#### Returns

`any`

#### Inherited from

Object.create

> `Static` **create**(o: `object`, properties: `PropertyDescriptorMap` & `ThisType`<`any`>): `any`

Creates an object that has the specified prototype, and that optionally contains specified properties.

#### Parameters

| Parameter  | Type                                        | Description                                                       |
| ---------- | ------------------------------------------- | ----------------------------------------------------------------- |
| o          | `object`                                    | Object to use as a prototype. May be null                         |
| properties | `PropertyDescriptorMap` & `ThisType`<`any`> | JavaScript object that contains one or more property descriptors. |

#### Returns

`any`

#### Inherited from

Object.create

### defineProperties()

> `Static` **defineProperties**\<T>(o: `T`, properties: `PropertyDescriptorMap` & `ThisType`<`any`>): `T`

Adds one or more properties to an object, and/or modifies attributes of existing properties.

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter  | Type                                        | Description                                                                                                                               |
| ---------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| o          | `T`                                         | Object on which to add or modify the properties. This can be a native JavaScript object or a DOM object.                                  |
| properties | `PropertyDescriptorMap` & `ThisType`<`any`> | JavaScript object that contains one or more descriptor objects. Each descriptor object describes a data property or an accessor property. |

#### Returns

`T`

#### Inherited from

Object.defineProperties

### defineProperty()

> `Static` **defineProperty**\<T>( o: `T`, p: `PropertyKey`, attributes: `PropertyDescriptor` & `ThisType`<`any`>): `T`

Adds a property to an object, or modifies attributes of an existing property.

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter  | Type                                     | Description                                                                                                                                                  |
| ---------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| o          | `T`                                      | Object on which to add or modify the property. This can be a native JavaScript object (that is, a user-defined object or a built in object) or a DOM object. |
| p          | `PropertyKey`                            | The property name.                                                                                                                                           |
| attributes | `PropertyDescriptor` & `ThisType`<`any`> | Descriptor for the property. It can be for a data property or an accessor property.                                                                          |

#### Returns

`T`

#### Inherited from

Object.defineProperty

### entries()

> `Static` **entries**\<T>(o: {} | `ArrayLike`<`T`>): \[`string`, `T`]\[]

Returns an array of key/values of the enumerable properties of an object

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type                   | Description                                                                                                                                |
| --------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | {} \| `ArrayLike`<`T`> | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

\[`string`, `T`]\[]

#### Inherited from

Object.entries

> `Static` **entries**(o: `object`): \[`string`, `any`]\[]

Returns an array of key/values of the enumerable properties of an object

#### Parameters

| Parameter | Type     | Description                                                                                                                                |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | `object` | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

\[`string`, `any`]\[]

#### Inherited from

Object.entries

### freeze()

> `Static` **freeze**\<T>(f: `T`): `T`

Prevents the modification of existing property attributes and values, and prevents the addition of new properties.

#### Type parameters

| Parameter              |
| ---------------------- |
| T _extends_ `Function` |

#### Parameters

| Parameter | Type | Description                             |
| --------- | ---- | --------------------------------------- |
| f         | `T`  | Object on which to lock the attributes. |

#### Returns

`T`

#### Inherited from

Object.freeze

> `Static` **freeze**\<T, U>(o: `T`): `Readonly`<`T`>

Prevents the modification of existing property attributes and values, and prevents the addition of new properties.

#### Type parameters

| Parameter                                                             |
| --------------------------------------------------------------------- |
| T _extends_ {}                                                        |
| U _extends_ `string` \| `number` \| `bigint` \| `boolean` \| `symbol` |

#### Parameters

| Parameter | Type | Description                             |
| --------- | ---- | --------------------------------------- |
| o         | `T`  | Object on which to lock the attributes. |

#### Returns

`Readonly`<`T`>

#### Inherited from

Object.freeze

> `Static` **freeze**\<T>(o: `T`): `Readonly`<`T`>

Prevents the modification of existing property attributes and values, and prevents the addition of new properties.

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type | Description                             |
| --------- | ---- | --------------------------------------- |
| o         | `T`  | Object on which to lock the attributes. |

#### Returns

`Readonly`<`T`>

#### Inherited from

Object.freeze

### fromEntries()

> `Static` **fromEntries**\<T>(entries: `Iterable`<_readonly_ \[`PropertyKey`, `T`]>): `object`

Returns an object created by key-value entries for properties and methods

#### Type parameters

| Parameter | Default |
| --------- | ------- |
| T         | `any`   |

#### Parameters

| Parameter | Type                                         | Description                                                                    |
| --------- | -------------------------------------------- | ------------------------------------------------------------------------------ |
| entries   | `Iterable`<_readonly_ \[`PropertyKey`, `T`]> | An iterable object that contains key-value entries for properties and methods. |

#### Returns

`object`

#### Inherited from

Object.fromEntries

> `Static` **fromEntries**(entries: `Iterable`<_readonly_ `any`\[]>): `any`

Returns an object created by key-value entries for properties and methods

#### Parameters

| Parameter | Type                            | Description                                                                    |
| --------- | ------------------------------- | ------------------------------------------------------------------------------ |
| entries   | `Iterable`<_readonly_ `any`\[]> | An iterable object that contains key-value entries for properties and methods. |

#### Returns

`any`

#### Inherited from

Object.fromEntries

### getOwnPropertyDescriptor()

> `Static` **getOwnPropertyDescriptor**(o: `any`, p: `PropertyKey`): `PropertyDescriptor`

Gets the own property descriptor of the specified object. An own property descriptor is one that is defined directly on the object and is not inherited from the object's prototype.

#### Parameters

| Parameter | Type          | Description                        |
| --------- | ------------- | ---------------------------------- |
| o         | `any`         | Object that contains the property. |
| p         | `PropertyKey` | Name of the property.              |

#### Returns

`PropertyDescriptor`

#### Inherited from

Object.getOwnPropertyDescriptor

### getOwnPropertyDescriptors()

> `Static` **getOwnPropertyDescriptors**\<T>(o: `T`): { \[P in string | number | symbol]: TypedPropertyDescriptor\<T\[P]> } & {}

Returns an object containing all own property descriptors of an object

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type | Description                                                                                                                                |
| --------- | ---- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | `T`  | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

{ \[P in string | number | symbol]: TypedPropertyDescriptor\<T\[P]> } & {}

#### Inherited from

Object.getOwnPropertyDescriptors

### getOwnPropertyNames()

> `Static` **getOwnPropertyNames**(o: `any`): `string`\[]

Returns the names of the own properties of an object. The own properties of an object are those that are defined directly on that object, and are not inherited from the object's prototype. The properties of an object include both fields (objects) and functions.

#### Parameters

| Parameter | Type  | Description                              |
| --------- | ----- | ---------------------------------------- |
| o         | `any` | Object that contains the own properties. |

#### Returns

`string`\[]

#### Inherited from

Object.getOwnPropertyNames

### getOwnPropertySymbols()

> `Static` **getOwnPropertySymbols**(o: `any`): `symbol`\[]

Returns an array of all symbol properties found directly on object o.

#### Parameters

| Parameter | Type  | Description                          |
| --------- | ----- | ------------------------------------ |
| o         | `any` | Object to retrieve the symbols from. |

#### Returns

`symbol`\[]

#### Inherited from

Object.getOwnPropertySymbols

### getPrototypeOf()

> `Static` **getPrototypeOf**(o: `any`): `any`

Returns the prototype of an object.

#### Parameters

| Parameter | Type  | Description                               |
| --------- | ----- | ----------------------------------------- |
| o         | `any` | The object that references the prototype. |

#### Returns

`any`

#### Inherited from

Object.getPrototypeOf

### is()

> `Static` **is**(value1: `any`, value2: `any`): `boolean`

Returns true if the values are the same value, false otherwise.

#### Parameters

| Parameter | Type  | Description       |
| --------- | ----- | ----------------- |
| value1    | `any` | The first value.  |
| value2    | `any` | The second value. |

#### Returns

`boolean`

#### Inherited from

Object.is

### isExtensible()

> `Static` **isExtensible**(o: `any`): `boolean`

Returns a value that indicates whether new properties can be added to an object.

#### Parameters

| Parameter | Type  | Description     |
| --------- | ----- | --------------- |
| o         | `any` | Object to test. |

#### Returns

`boolean`

#### Inherited from

Object.isExtensible

### isFrozen()

> `Static` **isFrozen**(o: `any`): `boolean`

Returns true if existing property attributes and values cannot be modified in an object, and new properties cannot be added to the object.

#### Parameters

| Parameter | Type  | Description     |
| --------- | ----- | --------------- |
| o         | `any` | Object to test. |

#### Returns

`boolean`

#### Inherited from

Object.isFrozen

### isSealed()

> `Static` **isSealed**(o: `any`): `boolean`

Returns true if existing property attributes cannot be modified in an object and new properties cannot be added to the object.

#### Parameters

| Parameter | Type  | Description     |
| --------- | ----- | --------------- |
| o         | `any` | Object to test. |

#### Returns

`boolean`

#### Inherited from

Object.isSealed

### keys()

> `Static` **keys**(o: `object`): `string`\[]

Returns the names of the enumerable string properties and methods of an object.

#### Parameters

| Parameter | Type     | Description                                                                                                                                |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | `object` | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

`string`\[]

#### Inherited from

Object.keys

> `Static` **keys**(o: `object`): `string`\[]

Returns the names of the enumerable string properties and methods of an object.

#### Parameters

| Parameter | Type     | Description                                                                                                                                |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | `object` | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

`string`\[]

#### Inherited from

Object.keys

### preventExtensions()

> `Static` **preventExtensions**\<T>(o: `T`): `T`

Prevents the addition of new properties to an object.

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type | Description                    |
| --------- | ---- | ------------------------------ |
| o         | `T`  | Object to make non-extensible. |

#### Returns

`T`

#### Inherited from

Object.preventExtensions

### seal()

> `Static` **seal**\<T>(o: `T`): `T`

Prevents the modification of attributes of existing properties, and prevents the addition of new properties.

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type | Description                             |
| --------- | ---- | --------------------------------------- |
| o         | `T`  | Object on which to lock the attributes. |

#### Returns

`T`

#### Inherited from

Object.seal

### setPrototypeOf()

> `Static` **setPrototypeOf**(o: `any`, proto: `object`): `any`

Sets the prototype of a specified object o to object proto or null. Returns the object o.

#### Parameters

| Parameter | Type     | Description                             |
| --------- | -------- | --------------------------------------- |
| o         | `any`    | The object to change its prototype.     |
| proto     | `object` | The value of the new prototype or null. |

#### Returns

`any`

#### Inherited from

Object.setPrototypeOf

### values()

> `Static` **values**\<T>(o: {} | `ArrayLike`<`T`>): `T`\[]

Returns an array of values of the enumerable properties of an object

#### Type parameters

| Parameter |
| --------- |
| T         |

#### Parameters

| Parameter | Type                   | Description                                                                                                                                |
| --------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | {} \| `ArrayLike`<`T`> | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

`T`\[]

#### Inherited from

Object.values

> `Static` **values**(o: `object`): `any`\[]

Returns an array of values of the enumerable properties of an object

#### Parameters

| Parameter | Type     | Description                                                                                                                                |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| o         | `object` | Object that contains the properties and methods. This can be an object that you created or an existing Document Object Model (DOM) object. |

#### Returns

`any`\[]

#### Inherited from

Object.values
