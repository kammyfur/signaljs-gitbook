# SignalCLIError

**`Class`**

An error in signal-cli

## Hierarchy

* `Error`.**`SignalCLIError`**

## Constructors

### constructor()

> **new SignalCLIError**( message: `string`, executable?: `string`, args?: `string`\[]): [`SignalCLIError`](class.signalclierror.md)

#### Parameters

| Parameter   | Type        | Description                                                 |
| ----------- | ----------- | ----------------------------------------------------------- |
| message     | `string`    | The error message                                           |
| executable? | `string`    | The full path to the signal-cli executable                  |
| args?       | `string`\[] | The list of all the command parameters used with signal-cli |

#### Returns

[`SignalCLIError`](class.signalclierror.md)

#### Overrides

Error.constructor

## Properties

### arguments

> **arguments**: `string`\[]

List of all the command parameters used with signal-cli

### executable

> **executable**: `string`

Full path to the signal-cli executable

### message

> **message**: `string`

#### Inherited from

Error.message

### name

> **name**: `string`

#### Inherited from

Error.name

### stack

> **stack**?: `string`

#### Inherited from

Error.stack
