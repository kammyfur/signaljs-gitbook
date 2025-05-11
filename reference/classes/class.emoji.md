# Emoji

**`Class`**

An emoji sent on Signal

## Hierarchy

* `String`.**`Emoji`**

## Constructors

### constructor()

> **new Emoji**(props: `any`): [`Emoji`](class.emoji.md)

#### Parameters

| Parameter | Type  |
| --------- | ----- |
| props     | `any` |

#### Returns

[`Emoji`](class.emoji.md)

#### Overrides

String.constructor

## Properties

### length

> `readonly` **length**: `number`

Returns the length of a String object.

#### Inherited from

String.length

## Methods

### [iterator](class.emoji.md)

> **\[iterator]**(): `IterableIterator`<`string`>

Iterator

#### Returns

`IterableIterator`<`string`>

#### Inherited from

String.\[iterator]

### anchor()

> **anchor**(name: `string`): `string`

Returns an `<a>` HTML anchor element and sets the name attribute to the text value

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| name      | `string` |

#### Returns

`string`

#### Inherited from

String.anchor

### big()

> **big**(): `string`

Returns a `<big>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.big

### blink()

> **blink**(): `string`

Returns a `<blink>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.blink

### bold()

> **bold**(): `string`

Returns a `<b>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.bold

### charAt()

> **charAt**(pos: `number`): `string`

Returns the character at the specified index.

#### Parameters

| Parameter | Type     | Description                                    |
| --------- | -------- | ---------------------------------------------- |
| pos       | `number` | The zero-based index of the desired character. |

#### Returns

`string`

#### Inherited from

String.charAt

### charCodeAt()

> **charCodeAt**(index: `number`): `number`

Returns the Unicode value of the character at the specified location.

#### Parameters

| Parameter | Type     | Description                                                                                                      |
| --------- | -------- | ---------------------------------------------------------------------------------------------------------------- |
| index     | `number` | The zero-based index of the desired character. If there is no character at the specified index, NaN is returned. |

#### Returns

`number`

#### Inherited from

String.charCodeAt

### codePointAt()

> **codePointAt**(pos: `number`): `number`

Returns a nonnegative integer Number less than 1114112 (0x110000) that is the code point value of the UTF-16 encoded code point starting at the string element at position pos in the String resulting from converting this object to a String. If there is no element at that position, the result is undefined. If a valid UTF-16 surrogate pair does not begin at pos, the result is the code unit at pos.

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| pos       | `number` |

#### Returns

`number`

#### Inherited from

String.codePointAt

### concat()

> **concat**(...strings: `string`\[]): `string`

Returns a string that contains the concatenation of two or more strings.

#### Parameters

| Parameter  | Type        | Description                                     |
| ---------- | ----------- | ----------------------------------------------- |
| ...strings | `string`\[] | The strings to append to the end of the string. |

#### Returns

`string`

#### Inherited from

String.concat

### endsWith()

> **endsWith**(searchString: `string`, endPosition?: `number`): `boolean`

Returns true if the sequence of elements of searchString converted to a String is the same as the corresponding elements of this object (converted to a String) starting at endPosition – length(this). Otherwise returns false.

#### Parameters

| Parameter    | Type     |
| ------------ | -------- |
| searchString | `string` |
| endPosition? | `number` |

#### Returns

`boolean`

#### Inherited from

String.endsWith

### fixed()

> **fixed**(): `string`

Returns a `<tt>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.fixed

### fontcolor()

> **fontcolor**(color: `string`): `string`

Returns a `<font>` HTML element and sets the color attribute value

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| color     | `string` |

#### Returns

`string`

#### Inherited from

String.fontcolor

### fontsize()

> **fontsize**(size: `number`): `string`

Returns a `<font>` HTML element and sets the size attribute value

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| size      | `number` |

#### Returns

`string`

#### Inherited from

String.fontsize

> **fontsize**(size: `string`): `string`

Returns a `<font>` HTML element and sets the size attribute value

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| size      | `string` |

#### Returns

`string`

#### Inherited from

String.fontsize

### includes()

> **includes**(searchString: `string`, position?: `number`): `boolean`

Returns true if searchString appears as a substring of the result of converting this object to a String, at one or more positions that are greater than or equal to position; otherwise, returns false.

#### Parameters

| Parameter    | Type     | Description                                                                |
| ------------ | -------- | -------------------------------------------------------------------------- |
| searchString | `string` | search string                                                              |
| position?    | `number` | If position is undefined, 0 is assumed, so as to search all of the String. |

#### Returns

`boolean`

#### Inherited from

String.includes

### indexOf()

> **indexOf**(searchString: `string`, position?: `number`): `number`

Returns the position of the first occurrence of a substring.

#### Parameters

| Parameter    | Type     | Description                                                                                                        |
| ------------ | -------- | ------------------------------------------------------------------------------------------------------------------ |
| searchString | `string` | The substring to search for in the string                                                                          |
| position?    | `number` | The index at which to begin searching the String object. If omitted, search starts at the beginning of the string. |

#### Returns

`number`

#### Inherited from

String.indexOf

### italics()

> **italics**(): `string`

Returns an `<i>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.italics

### lastIndexOf()

> **lastIndexOf**(searchString: `string`, position?: `number`): `number`

Returns the last occurrence of a substring in the string.

#### Parameters

| Parameter    | Type     | Description                                                                                    |
| ------------ | -------- | ---------------------------------------------------------------------------------------------- |
| searchString | `string` | The substring to search for.                                                                   |
| position?    | `number` | The index at which to begin searching. If omitted, the search begins at the end of the string. |

#### Returns

`number`

#### Inherited from

String.lastIndexOf

### link()

> **link**(url: `string`): `string`

Returns an `<a>` HTML element and sets the href attribute value

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     |
| --------- | -------- |
| url       | `string` |

#### Returns

`string`

#### Inherited from

String.link

### localeCompare()

> **localeCompare**(that: `string`): `number`

Determines whether two strings are equivalent in the current locale.

#### Parameters

| Parameter | Type     | Description                        |
| --------- | -------- | ---------------------------------- |
| that      | `string` | String to compare to target string |

#### Returns

`number`

#### Inherited from

String.localeCompare

> **localeCompare**( that: `string`, locales?: `string` | `string`\[], options?: `CollatorOptions`): `number`

Determines whether two strings are equivalent in the current or specified locale.

#### Parameters

| Parameter | Type                    | Description                                                                                                                                                                                                                                                                                                                                                                                                      |
| --------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| that      | `string`                | String to compare to target string                                                                                                                                                                                                                                                                                                                                                                               |
| locales?  | `string` \| `string`\[] | A locale string or array of locale strings that contain one or more language or locale tags. If you include more than one locale string, list them in descending order of priority so that the first entry is the preferred locale. If you omit this parameter, the default locale of the JavaScript runtime is used. This parameter must conform to BCP 47 standards; see the Intl.Collator object for details. |
| options?  | `CollatorOptions`       | An object that contains one or more properties that specify comparison options. see the Intl.Collator object for details.                                                                                                                                                                                                                                                                                        |

#### Returns

`number`

#### Inherited from

String.localeCompare

### match()

> **match**(regexp: `string` | `RegExp`): `RegExpMatchArray`

Matches a string with a regular expression, and returns an array containing the results of that search.

#### Parameters

| Parameter | Type                 | Description                                                                            |
| --------- | -------------------- | -------------------------------------------------------------------------------------- |
| regexp    | `string` \| `RegExp` | A variable name or string literal containing the regular expression pattern and flags. |

#### Returns

`RegExpMatchArray`

#### Inherited from

String.match

> **match**(matcher: `object`): `RegExpMatchArray`

Matches a string or an object that supports being matched against, and returns an array containing the results of that search, or null if no matches are found.

#### Parameters

| Parameter | Type     | Description                                    |
| --------- | -------- | ---------------------------------------------- |
| matcher   | `object` | An object that supports being matched against. |

#### Returns

`RegExpMatchArray`

#### Inherited from

String.match

### matchAll()

> **matchAll**(regexp: `RegExp`): `IterableIterator`<`RegExpMatchArray`>

Matches a string with a regular expression, and returns an iterable of matches containing the results of that search.

#### Parameters

| Parameter | Type     | Description                                                                            |
| --------- | -------- | -------------------------------------------------------------------------------------- |
| regexp    | `RegExp` | A variable name or string literal containing the regular expression pattern and flags. |

#### Returns

`IterableIterator`<`RegExpMatchArray`>

#### Inherited from

String.matchAll

### normalize()

> **normalize**(form: "NFC" | "NFD" | "NFKC" | "NFKD"): `string`

Returns the String value result of normalizing the string into the normalization form named by form as specified in Unicode Standard Annex #15, Unicode Normalization Forms.

#### Parameters

| Parameter | Type                               | Description                                                                                     |
| --------- | ---------------------------------- | ----------------------------------------------------------------------------------------------- |
| form      | "NFC" \| "NFD" \| "NFKC" \| "NFKD" | <p>Applicable values: "NFC", "NFD", "NFKC", or "NFKD", If not specified default<br>is "NFC"</p> |

#### Returns

`string`

#### Inherited from

String.normalize

> **normalize**(form?: `string`): `string`

Returns the String value result of normalizing the string into the normalization form named by form as specified in Unicode Standard Annex #15, Unicode Normalization Forms.

#### Parameters

| Parameter | Type     | Description                                                                                     |
| --------- | -------- | ----------------------------------------------------------------------------------------------- |
| form?     | `string` | <p>Applicable values: "NFC", "NFD", "NFKC", or "NFKD", If not specified default<br>is "NFC"</p> |

#### Returns

`string`

#### Inherited from

String.normalize

### padEnd()

> **padEnd**(maxLength: `number`, fillString?: `string`): `string`

Pads the current string with a given string (possibly repeated) so that the resulting string reaches a given length. The padding is applied from the end (right) of the current string.

#### Parameters

| Parameter   | Type     | Description                                                                                                                                                                                            |
| ----------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| maxLength   | `number` | <p>The length of the resulting string once the current string has been padded.<br>If this parameter is smaller than the current string's length, the current string will be returned as it is.</p>     |
| fillString? | `string` | <p>The string to pad the current string with.<br>If this string is too long, it will be truncated and the left-most part will be applied.<br>The default value for this parameter is " " (U+0020).</p> |

#### Returns

`string`

#### Inherited from

String.padEnd

### padStart()

> **padStart**(maxLength: `number`, fillString?: `string`): `string`

Pads the current string with a given string (possibly repeated) so that the resulting string reaches a given length. The padding is applied from the start (left) of the current string.

#### Parameters

| Parameter   | Type     | Description                                                                                                                                                                                            |
| ----------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| maxLength   | `number` | <p>The length of the resulting string once the current string has been padded.<br>If this parameter is smaller than the current string's length, the current string will be returned as it is.</p>     |
| fillString? | `string` | <p>The string to pad the current string with.<br>If this string is too long, it will be truncated and the left-most part will be applied.<br>The default value for this parameter is " " (U+0020).</p> |

#### Returns

`string`

#### Inherited from

String.padStart

### repeat()

> **repeat**(count: `number`): `string`

Returns a String value that is made from count copies appended together. If count is 0, the empty string is returned.

#### Parameters

| Parameter | Type     | Description                |
| --------- | -------- | -------------------------- |
| count     | `number` | number of copies to append |

#### Returns

`string`

#### Inherited from

String.repeat

### replace()

> **replace**(searchValue: `string` | `RegExp`, replaceValue: `string`): `string`

Replaces text in a string, using a regular expression or search string.

#### Parameters

| Parameter    | Type                 | Description                                                                                                                                                                                                                                                         |
| ------------ | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| searchValue  | `string` \| `RegExp` | A string or regular expression to search for.                                                                                                                                                                                                                       |
| replaceValue | `string`             | A string containing the text to replace. When the searchValue is a `RegExp`, all matches are replaced if the `g` flag is set (or only those matches at the beginning, if the `y` flag is also present). Otherwise, only the first match of searchValue is replaced. |

#### Returns

`string`

#### Inherited from

String.replace

> **replace**(searchValue: `string` | `RegExp`, replacer: `Function`): `string`

Replaces text in a string, using a regular expression or search string.

#### Parameters

| Parameter   | Type                                                 | Description                                   |
| ----------- | ---------------------------------------------------- | --------------------------------------------- |
| searchValue | `string` \| `RegExp`                                 | A string to search for.                       |
| replacer    | (substring: `string`, ...args: `any`\[]) => `string` | A function that returns the replacement text. |

#### Returns

`string`

#### Inherited from

String.replace

> **replace**(searchValue: `object`, replaceValue: `string`): `string`

Passes a string and replaceValue to the `[Symbol.replace]` method on searchValue. This method is expected to implement its own replacement algorithm.

#### Parameters

| Parameter    | Type     | Description                                                                  |
| ------------ | -------- | ---------------------------------------------------------------------------- |
| searchValue  | `object` | An object that supports searching for and replacing matches within a string. |
| replaceValue | `string` | The replacement text.                                                        |

#### Returns

`string`

#### Inherited from

String.replace

> **replace**(searchValue: `object`, replacer: `Function`): `string`

Replaces text in a string, using an object that supports replacement within a string.

#### Parameters

| Parameter   | Type                                                 | Description                                                  |
| ----------- | ---------------------------------------------------- | ------------------------------------------------------------ |
| searchValue | `object`                                             | A object can search for and replace matches within a string. |
| replacer    | (substring: `string`, ...args: `any`\[]) => `string` | A function that returns the replacement text.                |

#### Returns

`string`

#### Inherited from

String.replace

### replaceAll()

> **replaceAll**(searchValue: `string` | `RegExp`, replaceValue: `string`): `string`

Replace all instances of a substring in a string, using a regular expression or search string.

#### Parameters

| Parameter    | Type                 | Description                                                                                       |
| ------------ | -------------------- | ------------------------------------------------------------------------------------------------- |
| searchValue  | `string` \| `RegExp` | A string to search for.                                                                           |
| replaceValue | `string`             | A string containing the text to replace for every successful match of searchValue in this string. |

#### Returns

`string`

#### Inherited from

String.replaceAll

> **replaceAll**(searchValue: `string` | `RegExp`, replacer: `Function`): `string`

Replace all instances of a substring in a string, using a regular expression or search string.

#### Parameters

| Parameter   | Type                                                 | Description                                   |
| ----------- | ---------------------------------------------------- | --------------------------------------------- |
| searchValue | `string` \| `RegExp`                                 | A string to search for.                       |
| replacer    | (substring: `string`, ...args: `any`\[]) => `string` | A function that returns the replacement text. |

#### Returns

`string`

#### Inherited from

String.replaceAll

### search()

> **search**(regexp: `string` | `RegExp`): `number`

Finds the first substring match in a regular expression search.

#### Parameters

| Parameter | Type                 | Description                                          |
| --------- | -------------------- | ---------------------------------------------------- |
| regexp    | `string` \| `RegExp` | The regular expression pattern and applicable flags. |

#### Returns

`number`

#### Inherited from

String.search

> **search**(searcher: `object`): `number`

Finds the first substring match in a regular expression search.

#### Parameters

| Parameter | Type     | Description                                         |
| --------- | -------- | --------------------------------------------------- |
| searcher  | `object` | An object which supports searching within a string. |

#### Returns

`number`

#### Inherited from

String.search

### slice()

> **slice**(start?: `number`, end?: `number`): `string`

Returns a section of a string.

#### Parameters

| Parameter | Type     | Description                                                                                                                                                                                                                                            |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| start?    | `number` | The index to the beginning of the specified portion of stringObj.                                                                                                                                                                                      |
| end?      | `number` | <p>The index to the end of the specified portion of stringObj. The substring includes the characters up to, but not including, the character indicated by end.<br>If this value is not specified, the substring continues to the end of stringObj.</p> |

#### Returns

`string`

#### Inherited from

String.slice

### small()

> **small**(): `string`

Returns a `<small>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.small

### split()

> **split**(separator: `string` | `RegExp`, limit?: `number`): `string`\[]

Split a string into substrings using the specified separator and return them as an array.

#### Parameters

| Parameter | Type                 | Description                                                                                                                                                    |
| --------- | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| separator | `string` \| `RegExp` | A string that identifies character or characters to use in separating the string. If omitted, a single-element array containing the entire string is returned. |
| limit?    | `number`             | A value used to limit the number of elements returned in the array.                                                                                            |

#### Returns

`string`\[]

#### Inherited from

String.split

> **split**(splitter: `object`, limit?: `number`): `string`\[]

Split a string into substrings using the specified separator and return them as an array.

#### Parameters

| Parameter | Type     | Description                                                         |
| --------- | -------- | ------------------------------------------------------------------- |
| splitter  | `object` | An object that can split a string.                                  |
| limit?    | `number` | A value used to limit the number of elements returned in the array. |

#### Returns

`string`\[]

#### Inherited from

String.split

### startsWith()

> **startsWith**(searchString: `string`, position?: `number`): `boolean`

Returns true if the sequence of elements of searchString converted to a String is the same as the corresponding elements of this object (converted to a String) starting at position. Otherwise returns false.

#### Parameters

| Parameter    | Type     |
| ------------ | -------- |
| searchString | `string` |
| position?    | `number` |

#### Returns

`boolean`

#### Inherited from

String.startsWith

### strike()

> **strike**(): `string`

Returns a `<strike>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.strike

### sub()

> **sub**(): `string`

Returns a `<sub>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.sub

### substr()

> **substr**(from: `number`, length?: `number`): `string`

Gets a substring beginning at the specified location and having the specified length.

#### Deprecated

A legacy feature for browser compatibility

#### Parameters

| Parameter | Type     | Description                                                                                             |
| --------- | -------- | ------------------------------------------------------------------------------------------------------- |
| from      | `number` | The starting position of the desired substring. The index of the first character in the string is zero. |
| length?   | `number` | The number of characters to include in the returned substring.                                          |

#### Returns

`string`

#### Inherited from

String.substr

### substring()

> **substring**(start: `number`, end?: `number`): `string`

Returns the substring at the specified location within a String object.

#### Parameters

| Parameter | Type     | Description                                                                                                                                                                                                                                                              |
| --------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| start     | `number` | The zero-based index number indicating the beginning of the substring.                                                                                                                                                                                                   |
| end?      | `number` | <p>Zero-based index number indicating the end of the substring. The substring includes the characters up to, but not including, the character indicated by end.<br>If end is omitted, the characters from start through the end of the original string are returned.</p> |

#### Returns

`string`

#### Inherited from

String.substring

### sup()

> **sup**(): `string`

Returns a `<sup>` HTML element

#### Deprecated

A legacy feature for browser compatibility

#### Returns

`string`

#### Inherited from

String.sup

### toLocaleLowerCase()

> **toLocaleLowerCase**(locales?: `string` | `string`\[]): `string`

Converts all alphabetic characters to lowercase, taking into account the host environment's current locale.

#### Parameters

| Parameter | Type                    |
| --------- | ----------------------- |
| locales?  | `string` \| `string`\[] |

#### Returns

`string`

#### Inherited from

String.toLocaleLowerCase

### toLocaleUpperCase()

> **toLocaleUpperCase**(locales?: `string` | `string`\[]): `string`

Returns a string where all alphabetic characters have been converted to uppercase, taking into account the host environment's current locale.

#### Parameters

| Parameter | Type                    |
| --------- | ----------------------- |
| locales?  | `string` \| `string`\[] |

#### Returns

`string`

#### Inherited from

String.toLocaleUpperCase

### toLowerCase()

> **toLowerCase**(): `string`

Converts all the alphabetic characters in a string to lowercase.

#### Returns

`string`

#### Inherited from

String.toLowerCase

### toString()

> **toString**(): `string`

Returns a string representation of a string.

#### Returns

`string`

#### Inherited from

String.toString

### toUpperCase()

> **toUpperCase**(): `string`

Converts all the alphabetic characters in a string to uppercase.

#### Returns

`string`

#### Inherited from

String.toUpperCase

### trim()

> **trim**(): `string`

Removes the leading and trailing white space and line terminator characters from a string.

#### Returns

`string`

#### Inherited from

String.trim

### trimEnd()

> **trimEnd**(): `string`

Removes the trailing white space and line terminator characters from a string.

#### Returns

`string`

#### Inherited from

String.trimEnd

### trimLeft()

> **trimLeft**(): `string`

Removes the leading white space and line terminator characters from a string.

#### Deprecated

A legacy feature for browser compatibility. Use `trimStart` instead

#### Returns

`string`

#### Inherited from

String.trimLeft

### trimRight()

> **trimRight**(): `string`

Removes the trailing white space and line terminator characters from a string.

#### Deprecated

A legacy feature for browser compatibility. Use `trimEnd` instead

#### Returns

`string`

#### Inherited from

String.trimRight

### trimStart()

> **trimStart**(): `string`

Removes the leading white space and line terminator characters from a string.

#### Returns

`string`

#### Inherited from

String.trimStart

### valueOf()

> **valueOf**(): `string`

Returns the primitive value of the specified object.

#### Returns

`string`

#### Inherited from

String.valueOf

### fromCharCode()

> `Static` **fromCharCode**(...codes: `number`\[]): `string`

#### Parameters

| Parameter | Type        |
| --------- | ----------- |
| ...codes  | `number`\[] |

#### Returns

`string`

#### Inherited from

String.fromCharCode

### fromCodePoint()

> `Static` **fromCodePoint**(...codePoints: `number`\[]): `string`

Return the String value whose elements are, in order, the elements in the List elements. If length is 0, the empty string is returned.

#### Parameters

| Parameter     | Type        |
| ------------- | ----------- |
| ...codePoints | `number`\[] |

#### Returns

`string`

#### Inherited from

String.fromCodePoint

### raw()

> `Static` **raw**(template: `object`, ...substitutions: `any`\[]): `string`

String.raw is usually used as a tag function of a Tagged Template String. When called as such, the first argument will be a well formed template call site object and the rest parameter will contain the substitution values. It can also be called directly, for example, to interleave strings and values from your own tag function, and in this case the only thing it needs from the first argument is the raw property.

#### Parameters

| Parameter        | Type     | Description                                             |
| ---------------- | -------- | ------------------------------------------------------- |
| template         | `object` | A well-formed template string call site representation. |
| ...substitutions | `any`\[] | A set of substitution values.                           |

#### Returns

`string`

#### Inherited from

String.raw
