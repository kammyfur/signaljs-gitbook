# CLIDispatcher

**`Class`**

A dispatcher used to send requests to signal-cli and receive a response

## Constructors

### constructor()

> **new CLIDispatcher**(): [`CLIDispatcher`](class.clidispatcher.md)

#### Returns

[`CLIDispatcher`](class.clidispatcher.md)

## Methods

### dispatch()

> `Static` **dispatch**( method: `string`, params: `any`, proc: `ChildProcess`): `Promise`<`any`>

Dispatch a request to signal-cli

#### Parameters

| Parameter | Type           | Description                                                                                                                                   |
| --------- | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| method    | `string`       | <p>The method to associate with the request.<br>Use <code>signal-cli --help</code> to get a full list</p>                                     |
| params    | `any`          | <p>The parameters to pass with the request.<br>Use <code>signal-cli &#x3C;method> --help</code> to get a full list for the current method</p> |
| proc      | `ChildProcess` | The signal-cli process to dispatch to                                                                                                         |

#### Returns

`Promise`<`any`>
